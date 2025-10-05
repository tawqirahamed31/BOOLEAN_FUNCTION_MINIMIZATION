# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

i)
module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule

**RTL realization**

F1:

<img width="903" height="473" alt="image" src="https://github.com/user-attachments/assets/7619ccd7-801e-42a3-b107-65514915e411" />

F2:

<img width="965" height="526" alt="image" src="https://github.com/user-attachments/assets/44e579c2-a461-41ad-a03c-c192c93f6564" />


**Timing Diagram**

F1:

<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/85ba0904-91ac-4a71-bce8-6635d5ff2679" />


F2:

<img width="1919" height="1033" alt="image" src="https://github.com/user-attachments/assets/78492061-6e4f-4016-88a0-bd636c888486" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

