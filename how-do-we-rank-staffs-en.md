# How We Evaluate Embedded Software Engineers' Skill Levels

We classify abilities into six different levels, from LV0 to LV5. Upon reaching different ability levels, individuals possess corresponding skills and take on appropriate responsibilities. The ability level evaluation is determined through multiple rounds of voting using the [Delphi technique](https://www.knowledgehut.com/blog/project-management/delphi-technique-in-pmp) by current maintainers and the line manager. **Ratings must be conducted level by level, and skipping levels is not allowed**. In particular, individuals lacking technical skills are not permitted to skip LV2 and be promoted to LV3+.

## LV5

- Based on LV4, capable of independently analyzing and breaking down problems, integrating various resources to complete tasks.
- Able to guide LV4 and below partners, independently lead the development team, and ensure delivery.
- Capable of handling various emergencies and communicating with the line manager on behalf of the team.
- Has an in-depth understanding of the company's embedded systems and hardware platforms, and can assist stakeholders in continuous improvement and architecture optimization.

LV5 will be granted maintainer privileges.

## LV4

- Based on LV3, able to independently undertake module-level development work, and quickly learn new domain knowledge.
- **For complex embedded systems, able to independently complete debugging, error analysis, find the root cause of problems, and fix them, ensuring the timely progress of development tasks.**
- Able to guide LV3 and below partners, assisting them in completing development tasks.
- Able to independently create technical reports and share knowledge.
- Able to detect and point out errors and knowledge blind spots of LV4 and above, and correct the errors.
- **Able to independently open up a new knowledge domain for the team from scratch, supporting a specific technical direction in embedded systems (such as power management, communication protocols, real-time systems, etc.) through research reports, technical sharing, and prototype development.**

LV4 can be considered as a key candidate for maintainer training.

## LV3

- Based on LV2, able to independently undertake embedded code development work lasting more than a week.
- **Able to independently analyze bugs or abnormalities encountered in embedded systems, possessing strong software debugging and signal analysis capabilities.** (This is the entry threshold for LV3)
- Able to quickly understand the task's essence and find solutions with minimal mentor assistance, completing the task.
- Familiar with common embedded communication protocols (I2C, SPI, UART, CAN, etc.).
- Proficient in using hardware debugging tools such as oscilloscopes and logic analyzers.
- Proficient in reading English technical materials and chip manuals.
- Able to proficiently deliver public technical reports.

## LV2

- Based on LV1, has a systematic understanding of courses such as data structures, introduction to algorithms, computer organization principles/microcomputer principles/computer architecture, etc., has studied them, and can quickly review and master them.
- Has a good understanding and memory of microcontroller architecture, interrupt handling, and real-time operating system knowledge.
- Able to proficiently operate at least one development board. Here, "proficient operation" means:
  - Understanding the hardware structure of the development board, including main chips, interfaces, power systems, etc.
  - Able to independently set up the development environment, including driver installation and development toolchain configuration
  - Able to independently compile, flash, and debug firmware
  - Familiar with common peripherals of the development board (such as GPIO, timers, UART, ADC, etc.) and their programming methods
  - Able to read and understand the schematic diagram and datasheet of the development board
  - Able to write simple test programs to verify the functionality of the development board
  - Understanding the performance limitations and applicable scenarios of the development board
- Have a deeper understanding of C++, including:
  - Understanding and ability to apply object-oriented programming principles
  - Familiarity with C++ memory management mechanisms and resource management techniques (RAII principles, smart pointers, etc.)
  - Understanding and ability to avoid common pitfalls in C++ in embedded environments (such as dynamic memory allocation, exception handling, etc.)
- Proficient in using C/C++ for embedded system development.
- Able to proficiently use embedded development environments, including IDEs, compilers, debuggers, etc.
- Proficient in using version control tools like git for team code collaboration.
- Able to use scripting languages (Python/Bash) to complete simple automated testing tasks.
- Able to debug software independently and debug their own code. Knows how to use debuggers.
- Knows and has used build tools like Makefile and CMake.

## LV1

- Proficient in at least one programming language, must be proficient in C/C++.
- Basic Python/Bash scripting skills. (Here, "basic" means being able to fully understand a given script through Google or books.)
- Able to complete function-level development under mentor guidance, read code independently, and understand local code logic.
- Capable of completing project testing, experimental data collection and cleaning, and document report writing under guidance.
- Able to communicate with mentors and colleagues as required, keep written records of work, and summarize problems and experiences.
- Has basic experience in embedded Linux or microcontroller development.
- Basic git and GitHub/gitlab skills. (Here, "basic" means clone, commit, push, branch, merge; GitHub operations refer to initiating PR/MR, updating PR/MR, and synchronizing with multiple remotes.)

LV1 is not capable of handling complex embedded system development work.

## LV0

- This is the default state for all students who have not been exposed to software development.
- Indicates no experience writing code in any programming language, and no experience using compilers.
- No concept of basic computer science knowledge such as data structures.

LV0 is not capable of handling embedded software development work.
