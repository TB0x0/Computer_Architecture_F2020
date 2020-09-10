# The Hardware-Software Interface

The compiler associates variables with registers and data structures like arrays with locations in memory

It is then able to place the correct starting address into the data transfer instructions

 - The data transfer instruction that copies data from memory to a register is called a load

<img src="/res/lwchart.png" />


**Alignment Restriction:** a requirement that data be aligned in memory on natural boundaries. This allows for faster data transfer.

- In MIPS words start at addresses that are multiples of 4

## Variables

- Most programs have more variables than computers have registers
- The compiler keeps the most frequently used variables in registers and places the rest in memory 
