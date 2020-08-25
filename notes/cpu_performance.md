# CPU Performance

## Relative Performance

**Performance = 1 / Execution Time**

*Example:* time taken to run a program

- A takes 10s to run the program, B takes 15s

- Execution Time<sub>B</sub> / Execution Time<sub>A</sub>

- 15s / 10s = 1.5

- Therefore A is 1.5 times faster than B

## Measuring Execution Time

- Elapsed Time
  - Total response time including all aspects
  - Determines system performance

- CPU Time
  - Time spent processing a given job (discounts I/O and shared time)
  - User CPU time plus system CPU time
  - Different programs are affected differently by CPU and system performance.

## CPU Clocking

<img src="/res/cpuclock.png">

- Clock period: Duration of a clock cycle

- Clock frequency: Cycles per second

## CPU Time

<img src="/res/cputime.png">

Performance is improved by:

- Reducing number of clock cycles

- Increasing clock rate

Hardware designers often trade off clock rate against cycle count.

*Example:*

Computer A has 2GHz clock and 10s CPU time

Design computer B to be faster.

- 6s CPU time (makes faster clock but causes 1.2 x clock cycles)

How fast do we need B's clock to be?

<img src="/res/cpuclockexample.png">


## Instruction Count (IC) and Cycles per Instruction (CPI)

ISA = Instruction set architecture

<img src="/res/ICandCPI.png">

Program instruction count is determined by the program, ISA, and compiler.

Average cycles per instruction (CPI) is determined by CPU hardware.

 - Different instructions have different CPI

*Example:*

Computer A has a cycle time of 250ps and a CPI of 2.0

Computer B has a cycle time of 500ps and a CPI of 1.2

They both have the same ISA. Which computer is faster and by how much?

<img src="/res/cpiexample.png">

## Performance Summary

<img src="/res/perfsummary.png">

**Performance depends on:**

- Algorithm (affects IC and possibly CPI)

- Programming language (affects IC and CPI)

- Compiler (affects IC and CPI)

- Instruction Set Architecture (affects IC, CPI, and T<sub>c</sub>)
