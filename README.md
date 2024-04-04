### study-of-basic-gates

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

Program for logic gates and verify its truth table in quartus using Verilog programming
```
module digi(a,b,c,d,e,x,y,z);

input a,b;

output c,d,e,x,y,z;

and(c,a,b);

or(d,a,b);

xor(e,a,b);

nand(x,a,b);

nor(y,a,b);

xnor(z,a,b);

endmodule
```
 Developed by:Yuvan M
 RegisterNumber: 212223240188
 
**Logic symbol & Truthtable**
![WhatsApp Image 2024-03-14 at 15 48 16_138cbb4e](https://github.com/Yuvan291205/study-of-basic-gates/assets/138849170/87292468-e473-4907-9ec7-d1075832c179)
![WhatsApp Image 2024-03-14 at 15 49 43_70675a3d](https://github.com/Yuvan291205/study-of-basic-gates/assets/138849170/cc0dfb88-7b08-41bd-ad35-07f8e64babb0)

**RTL realization Output:** 
![WhatsApp Image 2024-03-14 at 15 49 14_cd300739](https://github.com/Yuvan291205/study-of-basic-gates/assets/138849170/aa2306d0-bf8f-4a5b-9a27-13cccc0397d9)



**RTL**
![WhatsApp Image 2024-03-14 at 15 49 14_4de826aa](https://github.com/Yuvan291205/study-of-basic-gates/assets/138849170/5f9b59f8-f9ed-4e3b-822e-275f48f68923))

**Result:**
output is verified

