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

Developed by:DHARSHINI S
RegisterNumber:212223110010*/

module boolean(e, f, a, b, c, d);
output e, f;
input a, b, c, d;
assign e = a || (b && c) || ((!b) && d);
assign f = ((!b) && c)|| (b && (!c) && (!d));
endmodule


**RTL realization**
![WhatsApp Image 2024-03-21 at 1 06 06 PM](https://github.com/23010890/BOOLEAN_FUNCTION_MINIMIZATION/assets/154983666/6a824445-3dfe-4570-b62f-c69840760e88)

**RTL**

![WhatsApp Image 2024-03-21 at 12 37 30 PM](https://github.com/23010890/BOOLEAN_FUNCTION_MINIMIZATION/assets/154983666/612a4714-79dc-4603-9389-5fe91ab60aaa)

**Timing Diagram**
![WhatsApp Image 2024-03-21 at 1 06 25 PM](https://github.com/23010890/BOOLEAN_FUNCTION_MINIMIZATION/assets/154983666/75ec0f62-e6e6-46bd-9281-d8bc850e20a7)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

