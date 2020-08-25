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

![](/res/lvlprgmcode.png)

- High-level language
  - Level of abstraction closer to problem domain
  - Provides productivity and portability

- Assembly language
  - Textual representation of instructions

- Hardware representation
  - Binary digits
  - Encoded instructions and data
