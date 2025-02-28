# RISC-V Instruction Analysis  

I thoroughly reviewed the **RISC-V software documentation** to gain a comprehensive understanding of the **R, I, S, B, U, and J** instruction formats. These formats define the structure of different types of **RISC-V instructions** and how their **opcode, function codes, and register fields** are arranged within a **32-bit instruction word**.  

After understanding these formats, I analyzed the **riscv-objdump** output of my application code to extract **15 unique RISC-V instructions**. For each of these instructions, I carefully examined their **binary representation** and determined their exact **32-bit instruction codes** according to their respective instruction formats.  

## Process Involved:  

1. **Identifying the opcode, function fields, and register operands** for each instruction.  
2. **Matching each instruction** to its respective format (**R, I, S, B, U, or J**).  
3. **Decoding the 32-bit binary representation** to understand how different fields are structured within each instruction.  

This analysis provided valuable insights into how **RISC-V instructions** are encoded and executed at the **assembly and machine code level**. 
