# Computer Architecture Introduction

## The Computer Revolution

Progress in computer technology makes novel applications feasible

- Computers in cars
- Cell phones
- Internet

Computers are pervasive

## Classes of Computers

<ul>
  <li>Desktop computers</li>
    <ul>
      <li>General Purpose, variety of software</li>
      <li>Subject to cost/performance tradeoff</li>
    </ul>
  <li>Servers</li>
    <ul>
      <li>Network based</li>
      <li>High capacity, performance, and reliability</li>
      <li>Sizes range from small towers to building sized</li>
    </ul>
  <li>Embedded computers</li>
    <ul>
      <li>Hidden as components of systems</li>
      <li>Strict power, performance, and cost restraints</li>
    </ul>
</ul>


## Moore's Law

**The number of transistors per square inch on integrated circuits doubles about every two years** - Gordon Moore 1965

## Learning Objectives

- How programs are translated into machine language and how hardware executes them

- Hardware/Software interfacing

- What determines program performance and how to improve it

- How hardware designers improve performance

- What is parallel processing

## Understanding Performance

- *Algorithms*: Determine number of operations executed

- *Programming language, compiler, architecture*: Determine number of machine instructions executed per operation

- *Processor and memory system*: Determine how fast instructions are executed

- *I/O System (including OS)*: Determine how fast I/O operations are executed

## Components of a Program

1. Application Software: Written in high-level languages

2. System Software: Compiler translates programmer code to machine code. Operating System (service code) handles I/O, memory and storage management, and task scheduling/resource sharing.

3. Hardware: Processor, memory, I/O controllers

## Levels of Program Code

<img align="right" src="/res/lvlprgmcode.png">

- High-level language
  - Level of abstraction closer to problem domain
  - Provides productivity and portability

- Assembly language
  - Textual representation of instructions

- Hardware representation
  - Binary digits
  - Encoded instructions and data


## Components of a Computer

- User-interface devices: Keyboard, mouse, display

- Storage devices: Disk, CD/DVD, flash, SSD

- Network adapters: Allow communication across the net

## AMD Barcelona Quad Core

<img src="/res/barcelona.png">


## Abstractions

Abstraction helps us deal with complexity by hiding low-level details

- Instruction Set Architecture (ISA): The hardware/software interface

- Application Binary Interface: The ISA plus system software interface

- Implementation: Details underlying an interface

## Data Storage

- Volatile Main Memory: Loses instructions when powered off.

- Non-volatile Secondary Memory: Disk, flash, optical disk

## Controller Area Network (CAN)

Developed by Robert Bosch GmbH in 1983. Released in 1986.

- Vehicle bus standard designed to allow microcontrollers and devices to communicate with each other in applications without a host computer.

- Message based protocol designed for multiplex electrical wiring in vehicles. Also used in other contexts.

- 1991 Mercedes-Benz W140 was first production vehicle with CAN bus system

## Response Time and Throughput

- Response time: How long it takes to do a task

- Throughput: Total work done per unit of time

Both of these come into play when talking about performance.

## Relative Performance

**Performance = 1 / Execution Time**

*Example:* time taken to run a program

- A takes 10s to run the program, B takes 15s

- Execution Time<sub>B</sub> / Execution Time<sub>A</sub>

- 15s / 10s = 1.5

- Therefore A is 1.5 times faster than B
