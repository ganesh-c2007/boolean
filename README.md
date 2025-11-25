AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

F2=xy’z+x’y’z+w’xy+wx’y+wxy

Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

Theory

Logic Diagram

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

Program:
```

module xyz2 (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by:Ganesh.c

RegisterNumber: 25017481 */


RTL realization

[xyz2.pdf](https://github.com/user-attachments/files/23737869/xyz2.pdf)

Output: RTL

[exp2.pdf](https://github.com/user-attachments/files/23737881/exp2.pdf)

Result:  Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
