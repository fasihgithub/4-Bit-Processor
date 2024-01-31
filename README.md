# 4 Bit Processor
4-bit Processor Simulation
This project simulates a 4-bit processor with four 4-bit data registers and a 7-bit instruction register. The processor executes operations based on a 3-bit opcode, using the specified first and second registers.

Overview
The 4-bit processor is designed to perform basic operations on data stored in registers. Each instruction consists of a 3-bit opcode, specifying the operation, and two 2-bit register specifiers. The project aims to provide a simple yet functional implementation of a processor architecture.

Processor Architecture
Registers:

Four 4-bit data registers (R0, R1, R2, R3).
Instruction Register (IR) of 7 bits.
Instruction Format:

7 bits in IR: 3 bits for opcode, 2 bits for the first register, 2 bits for the second register.
Operations:

Opcodes define basic operations like ADD, SUB, AND, OR, etc.
Execution:

Fetch the instruction, decode opcode and registers, perform the operation, and update registers.
Instruction Set
Example Opcodes:

000: ADD
001: SUB
010: AND
011: OR
... and so on.
Example Instructions:

0010010: SUB R1, R2, R0 (Subtract contents of R2 from R0 and store the result in R1)
0101101: OR R3, R1, R3 (Perform logical OR on contents of R1 and R3, store the result in R3)
