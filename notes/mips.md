# MIPS Instruction Set

To command a computer's hardware you must speak its language using instructions contained in an instruction set.


## Characteristics of the MIPS Instruction Set

- Each MIPS instruction performs only one operation
- It must always have exactly three variables
- MIPS has a 32x32 bit register

**Register Operands**
- $t0 - $t9 are for temporary values
- $s0 - $s7 are for saved variables
- lw: load word, loads a word from the register
- sw: store word, stores a word in the register

**Memory Operands**
- MIPS uses byte addressing. Each word represents 4 bytes
- In an array multiply by 4 to get the correct element

*Example:* a[200] becomes `lw $t0, 800($t1)`

- MIPS storage is broken into fields. Fields are given names to make them easier to reference.

<img src="/res/mipsfields.png" />

op: opcode, the basic operation of the instruction

rs: the first register source operand

rt: the second register source operand

rd: the register destination operand, the result is stored here

shamt: shift amount

funct: function, selects special variants of opcodes
