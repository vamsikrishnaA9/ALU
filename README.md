#4 Bit ALU
Aithematic logic unit design implemented using cmos transistors

This a 4Bit ALU designed on LT Spice by using CMOS transistors. It has the operations of XOR, XNOR, Addition, Subtraction, Multiplication, Leftshift, Arithmetic leftshift, Arithmetic rightshift, Circular leftshift and right shift, 4 bit magnitude comparator and Equality comparator. 
Operations of the ALU are selected by the slection inputs, which drives the 4x16 decoder and triggers the 4bit operaions. Truth Table for functional selections are given below

A B C D      -       Operation
0 0 0 0      -       XOR
0 0 0 1      -       XNOR
0 0 1 0      -       Multiplication
0 0 1 1      -       Addition 
0 1 0 0      -       Subtraction
0 1 0 1      -       Arithmetic Shift left
0 1 1 0      -       Rotate Shift Right
0 1 1 1      -       Rotate Shift Left
1 0 0 0      -       Logical lShift Left
1 0 0 1      -       Arithematic Right Shift
1 0 1 0      -       Magnitude Comparator
1 0 1 1      -       Equality Comparator

All the 4 bit Operation Outputs are drived by the 16x1 Multiplexers and gives the final output.

