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

**Boolean Minimization**
![WhatsApp Image 2024-12-23 at 08 38 07_7a5e7434](https://github.com/user-attachments/assets/7e40e511-1c44-499d-ba77-d1d6242f1dc3)
![WhatsApp Image 2024-12-23 at 08 38 07_1db6be56](https://github.com/user-attachments/assets/7baa26d5-9442-4f0e-a9d8-66502eb670c0)



**Truth Table**
![WhatsApp Image 2024-12-23 at 08 38 30_38445c90](https://github.com/user-attachments/assets/386e57f8-518a-4f9f-91f0-f894f1e2bba4)

**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module DE2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

```
module DE2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Developed by: Gokul S
RegisterNumber:24900980


**RTL realization**
![image](https://github.com/user-attachments/assets/4bf05445-58f9-4929-8de6-bde0018722dc)


**Output:**
**Waveform**
![image](https://github.com/user-attachments/assets/07493375-a2c6-4cf6-b12e-8a33e85d298f)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

