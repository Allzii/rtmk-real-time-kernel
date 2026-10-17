# RTMK – Real-Time Kernel

A small real-time kernel developed in C as a university project in Computer Engineering at Halmstad University.

The kernel runs on the Arduino Due with the SAM3X8E microcontroller and implements fundamental real-time operating system concepts such as task scheduling, timing, context switching and inter-process communication.

## Features

- Task creation and management
- Task Control Blocks (TCBs)
- Deadline-based task scheduling
- Ready, Waiting and Timer lists
- Context switching between tasks
- System tick handling
- Task delays using `wait()`
- Runtime deadline management
- Mailbox-based inter-process communication
- Blocking send and receive operations
- Non-blocking send and receive operations
- Dynamic mailbox creation and removal
- Interrupt handling

## Technologies

- C
- Assembly
- Real-Time Systems
- Operating Systems
- Arduino Due
- SAM3X8E / ARM Cortex-M3
- Task Scheduling
- Inter-Process Communication
- Interrupts
- IAR Embedded Workbench

## System Overview

The kernel manages tasks using separate Ready, Waiting and Timer lists.

Tasks are scheduled based on deadlines, while timing functionality is handled through system ticks and task delays. Communication between tasks is implemented using mailboxes with both blocking and non-blocking send and receive operations.

Context switching is handled using a combination of C and assembly code.

## Source Code

The full source code is kept private but can be shared upon request.
