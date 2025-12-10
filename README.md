<img width="1919" height="1199" alt="Screenshot 2025-12-09 220834" src="https://github.com/user-attachments/assets/4607c137-7fe8-4cd9-9f28-91482b7d69f7" /><img width="1919" height="1199" alt="Screenshot 2025-12-09 220834" src="https://github.com/user-attachments/assets/a2bf625a-45ee-47b7-a1f5-fac1d165e735" />### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
module LabExcercise1(a,b,c,d,e,f,g,h);
input a,b;
output c,d,e,f,g,h;
assign c = a & b;
assign d = a | b;
assign e = a ^ b;
assign f = ~(a & b);
assign g = ~(a | b);
assign h = ~(a ^ b);
endmodule






 Developed by:Rajalakshmi V RegisterNumber: 25016476
 
**Logic symbol & Truthtable**
<img width="605" height="539" alt="Screenshot 2025-12-10 102622" src="https://github.com/user-attachments/assets/0711de30-f7a0-443d-a70e-ff9d298309e6" />


**RTL realization Output:** 
<img width="1919" height="1199" alt="de1" src="https://github.com/user-attachments/assets/17f9b1f1-9206-434e-961b-e5f89068c8fe" />

**RTL**
<img width="1917" height="1199" alt="Screenshot 2025-12-09 212121" src="https://github.com/user-attachments/assets/923ed0b2-d6d3-4b4b-aeb9-8470c1742b66" />

**Result:** Thus the basic logic gates are studied and the truth tables are verified.



