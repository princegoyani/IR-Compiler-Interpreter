# IR Compiler

A small compiler that generates and interprets an intermediate representation (linked-list of instructions) for a toy language.

## Overview

- **Compiler**: Parses input programs, builds an IR (linked list of `InstructionNode`), supporting assignments, I/O, jumps, conditionals, loops, and switches.
- **Interpreter**: Provided `execute_program()` walks the IR and mutates memory accordingly.

Specified in CSE430 Spring 2025 – Project 3  [oai_citation:2‡CSE430S25_Project3.pdf](file-service://file-KaE3DHM9E4bwGEoQfZ3663).

## Features

- **IR Generation**: Produces a data-structure–based IR instead of assembly.
- **Control Flow**: Handles conditional jumps, loops (`while`, `for`), and `switch` statements.
- **Input/Output**: Integrates buffered I/O instructions.
- **Modular Design**: Separation between parsing (`parse_Generate_Intermediate_Representation`) and execution (`execute_program`).

## Tech Stack

- C++11  
- GNU GCC on Ubuntu 22.04  

## Repo Structure
