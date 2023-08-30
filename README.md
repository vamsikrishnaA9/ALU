# 4 Bit ALU
Arithmetic logic unit design implemented using CMOS transistors 

This is a 4-bit ALU designed on LT Spice by using CMOS transistors. It has the operations of XOR, XNOR, Addition, Subtraction, Multiplication, Leftshift, Arithmetic left-shift, Arithmetic right-shift, Circular left-shift and right shift, 4-bit magnitude comparator and Equality comparator. 
Operations of the ALU are selected by the selection inputs, which drive the 4x16 decoder and trigger the 4-bit operations. The truth Table for functional selections is given below

**A B C D     -       Operation**
0 0 0 0      -       XOR 
0 0 0 1      -       XNOR 
0 0 1 0      -       Multiplication 
0 0 1 1      -       Addition 
0 1 0 0      -       Subtraction 
0 1 0 1      -       Arithmetic Shift left 
0 1 1 0      -       Rotate Shift Right 
0 1 1 1      -       Rotate Shift Left 
1 0 0 0      -       Logical shift Left 
1 0 0 1      -       Arithmetic Right Shift 
1 0 1 0      -       Magnitude Comparator 
1 0 1 1      -       Equality Comparator 

_All the 4-bit Operation Outputs are driven by the 16x1 Multiplexers and give the final output._

