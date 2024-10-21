# 8bitALU
Arithmetic Logic Unit (ALU) Design Project
Project Overview
This project involves the design and implementation of an Arithmetic Logic Unit (ALU), capable of performing both arithmetic and logical operations. The ALU processes two 8-bit inputs and outputs an 8-bit result based on the operation selected. The project was designed and simulated using Verilog, and hardware validation was done using an FPGA.

The ALU is capable of performing the following operations:
Logical Operations: AND, OR, NOT, XOR, NOR, XNOR.
Arithmetic Operations: Addition, Subtraction, Multiplication, Division.
Other Operations: Bit shifts (Left/Right), Increment, Decrement, Set, Clear, Swap, Reverse bits.
Processor Operations
The implemented operations include:

IDLE: No operation.
ADD: Y = A + B
SUB: Y = A - B
MUL: Y = A * B
DIV: Y = A / B
AND: Y = A & B
OR: Y = A | B
NOT: Y = ~A
XOR: Y = A ^ B
XNOR: Y = ~(A ^ B)
Left/Right Shift: Shifts bits of Y by 2 positions.
Other: Clear, Set, Increment, Decrement, Swap values, Reverse bits.
Design Details
1. ALU Block Diagram
The ALU processes two 8-bit inputs (A, B) and produces an 8-bit output (Y).
2. Schematic and Simulation
Schematic: The schematic diagram shows the logical structure of the ALU.
Simulation: Various test cases were run to verify the ALU’s functionality. Operations such as ADD, SUB, and logical operations were simulated to ensure correct results.
3. Testbench and Results
Simulated test cases for different operations such as addition, subtraction, AND, OR, and more, were provided.
Power Report: Total on-chip power consumption was measured.

Timing Report: Maximum delay of 16 ns was recorded.

Utilization Report: Resource utilization details are provided for the design.

Synthesis Summary:

Total Power: 2.264 W
Dynamic Power: 2.188 W
Static Power: 0.076 W
Max Delay: 16 ns
5. I/O Pin Mapping
The input and output pins were mapped to the Basys 3 FPGA board for hardware validation.
6. FPGA Validation
The ALU design was validated on the Basys 3 FPGA board, ensuring that it functions as expected in a hardware environment.
Tools and Resources
Design Software: The project was designed and simulated using Vivado.
Hardware: Basys 3 FPGA board for testing and validation.

Conclusion
The project successfully implemented an ALU with 16 different functions using Verilog. The ALU was simulated and synthesized, with power, timing, and utilization reports generated. Hardware validation was completed on an FPGA, confirming the functionality of the design.
