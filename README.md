# monty
# Project: 0x19. C - Stacks, Queues - LIFO, FIFO

## Author: Tolulope Ajayi

Welcome to the `tolulope-web` repository for the project **0x19. C - Stacks, Queues - LIFO, FIFO**. This project is part of a group effort to develop an interpreter for Monty ByteCodes files in C. Below you will find a list of tasks, notes, and requirements for this project.

## Table of Contents
- [Project Description](#project-description)
- [Resources](#resources)
- [Learning Objectives](#learning-objectives)
- [Copyright and Plagiarism](#copyright-and-plagiarism)
- [Requirements](#requirements)
- [Tasks and Notes](#tasks-and-notes)
    - [Task 0: push, pall](#task-0-push-pall)
    - [Task 1: pint](#task-1-pint)
    - [Task 2: pop](#task-2-pop)
    - [Task 3: swap](#task-3-swap)
    - [Task 4: add](#task-4-add)
    - [Task 5: nop](#task-5-nop)
    - [Task 6: sub](#task-6-sub)
    - [Task 7: div](#task-7-div)
    - [Task 8: mul](#task-8-mul)
    - [Task 9: mod](#task-9-mod)
    - [Task 10: comments](#task-10-comments)
    - [Task 11: pchar](#task-11-pchar)
    - [Task 12: pstr](#task-12-pstr)
    - [Task 13: rotl](#task-13-rotl)
    - [Task 14: rotr](#task-14-rotr)
    - [Task 15: stack, queue](#task-15-stack-queue)
    - [Task 16: Brainf*ck](#task-16-brainfck)
    - [Task 17: Add two digits](#task-17-add-two-digits)
    - [Task 18: Multiplication](#task-18-multiplication)
    - [Task 19: Multiplication level up](#task-19-multiplication-level-up)

## Project Description
This project involves creating an interpreter for Monty ByteCodes files in C. The project tasks include implementing various opcodes and handling different stack and queue behaviors.

## Resources
- Google
- How to use extern to share variables between source files in C
- Stacks and Queues in C
- Stack operations
- Queue operations

## Learning Objectives
By the end of this project, you are expected to be able to explain:
- What LIFO and FIFO mean
- What a stack is and when to use it
- What a queue is and when to use it
- Common implementations of stacks and queues
- Common use cases of stacks and queues
- The proper way to use global variables

## Copyright and Plagiarism
Please note that plagiarism is strictly forbidden in this project. You are required to come up with your solutions to meet the learning objectives and are not allowed to publish any content of this project.

## Requirements
### General
- Allowed editors: vi, vim, emacs
- Compilation on Ubuntu 20.04 LTS using gcc with options: -Wall -Werror -Wextra -pedantic -std=c89
- All files should end with a new line
- A README.md file is mandatory
- Code should follow the Betty style
- Maximum of one global variable allowed
- No more than 5 functions per file
- C standard library is allowed
- Prototypes of all functions should be included in a header file named monty.h
- Header files should be include guarded
- Tasks should be done in the order specified
- Only one project repository per group
- Recommended to work on a set of tests collaboratively

## Tasks and Notes
### Task 0: push, pall
- **Note:** Implement the push and pall opcodes.
- **The push opcode:** Pushes an element to the stack.
- **Usage:** push <int>
- **The pall opcode:** Prints all values on the stack.
- **Usage:** pall

### Task 1: pint
- **Note:** Implement the pint opcode.
- **The pint opcode:** Prints the value at the top of the stack.

### Task 2: pop
- **Note:** Implement the pop opcode.
- **The pop opcode:** Removes the top element of the stack.

### Task 3: swap
- **Note:** Implement the swap opcode.
- **The swap opcode:** Swaps the top two elements of the stack.

### Task 4: add
- **Note:** Implement the add opcode.
- **The add opcode:** Adds the top two elements of the stack.

### Task 5: nop
- **Note:** Implement the nop opcode.
- **The nop opcode:** Does nothing.

### Task 6: sub
- **Note:** Implement the sub opcode.
- **The sub opcode:** Subtracts the second top element from the top element of the stack.

### Task 7: div
- **Note:** Implement the div opcode.
- **The div opcode:** Divides the second top element by the top element of the stack.

### Task 8: mul
- **Note:** Implement the mul opcode.
- **The mul opcode:** Multiplies the second top element with the top element of the stack.

### Task 9: mod
- **Note:** Implement the mod opcode.
- **The mod opcode:** Computes the remainder of division between the second top element and the top element of the stack.

### Task 10: comments
- **Note:** Implement the ability to add comments in the code.
- When a line starts with `#`, treat it as a comment (does nothing).

### Task 11: pchar
- **Note:** Implement the pchar opcode.
- **The pchar opcode:** Prints the character at the top of the stack.

### Task 12: pstr
- **Note:** Implement the pstr opcode.
- **The pstr opcode:** Prints the string starting at the top of the stack.

### Task 13: rotl
- **Note:** Implement the rotl opcode.
- **The rotl opcode:** Rotates the stack to the top.

### Task 14: rotr
- **Note:** Implement the rotr opcode.
- **The rotr opcode:** Rotates the stack to the bottom.

### Task 15: stack, queue
- **Note:** Implement the stack and queue opcodes.
- **The stack opcode:** Sets the format of the data to a stack (LIFO). This is the default behavior of the program.
- **The queue opcode:** Sets the format of the data to a queue (FIFO).

### Task 16: Brainf*ck
- **Note:** Write a Brainf*ck script that prints "School

