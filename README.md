# PIPELINE PROCESSER DESIGN
*COMPANY NAME : CODTECH IT SOLUTION*

*NAME : RAHUL SARDAR*

*INTERN ID : CT08IRH*

*DOMAIN : VLSI*

*BATCH DURATION : January 5th, 2025 to February 5th, 2025*

*MENTOR NAME : NEELA SANTOSH*

# Introduction: 
A pipeline processor is an architecture that enhances processing speed by 
breaking down instruction execution into multiple stages. This method allows 
different instructions to be processed simultaneously at various stages, 
improving overall efficiency.

 #  Design and Methodology: 
 
A basic 4-stage pipelined processor is designed using Verilog, comprising the 
following elements:
1. Instruction Memory – Stores program instructions.
2. Register File – Contains general-purpose registers for storing 
intermediate values.
3. Arithmetic Logic Unit (ALU) – Performs arithmetic and logical 
computations.
4. Pipeline Registers – Transfers data between different pipeline stages to 
maintain smooth execution.
![image](https://github.com/user-attachments/assets/eac00cd9-f4f3-40d1-afc8-fd73a037c30a)

 
 # Instruction Set: 
 
The processor executes basic operations like: 

• ADD, SUB for arithmetic operations. 

• AND, OR for logical operations.

• BEQ, BNE for conditional branching.

#  Simulation & OUTPUT : 
![image](https://github.com/user-attachments/assets/001db1cc-93c9-4cc1-b5d4-185ea57a49d3)


![image](https://github.com/user-attachments/assets/e3a24bd5-0be1-4474-bf42-5c0ac6e2881c)

# CONCLUSION 
The designed 4-stage pipelined processor using Verilog successfully demonstrates efficient instruction execution by dividing operations into multiple stages. The implemented design includes key components like instruction memory, register file, ALU, and pipeline registers. Simulation results confirm correct functionality, ensuring smooth execution of arithmetic, logical, and branching operations. This approach enhances processing speed by enabling concurrent execution of multiple instructions, showcasing the advantages of pipeline architecture in processor design.

