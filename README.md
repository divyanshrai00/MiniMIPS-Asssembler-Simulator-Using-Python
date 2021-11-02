# MiniMIPS-Asssembler-Simulator-Using-Python
This project is implemented in Python </br>

**Features of Assembler**
- The assembler was designed for various R-type, I-type and J-type instructions
- The designed assembler is also capable of assembling procedure calls (as jal instruction is included), it provides the provision for comments as well as it also shows an error message if the reference to particular label used is not available in the code.
- For signed arithmetic, signed offset and PC relative addressing appropriate algorithms for twos complement and sign extension were used.

**Features of Simulator**
- Writing a source code (MiniMIPS assembly code)
- Loading a source code stored in .txt format
- Assembling and viewing machine instructions
- Observing the PC and its updating
- Observing the symbol reference table generated in first pass
- Step execution for debugging and tracing the execution flow
- Execution the whole program at once
- Observing the contents of all the 32 registers of MiniMIPS
- Observing the memory contents (and hence stack contents)
- Getting “Execution completion” message
- Getting “Reference to label not available” error

**Instructions Incorporated**
- The list of instructions are as follows:
- R-Type: add, sub, and, or, xor, nor, jr, slt
- I-Type: addi, andi, ori, xori, lw, sw, beq, bne, bltz
- J-Type: j, jal
![simulator](https://user-images.githubusercontent.com/74989402/139793102-ad333362-5a52-4b8a-97a4-07442e68857d.PNG)
