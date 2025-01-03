study-of-basic-gates

AIM:

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

Equipments Required:

Software – Quartus prime

Theory

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

AND gate

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB Y= A.B

OR gate

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation. Y= A+B

NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs. Y= A'

NAND gate

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion. Y= (AB)’

NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion. Y= (A+B)’

Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation. Y= A⊕B

Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion. Y= A⊕B

Procedure

Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

PROGRAM

Program for logic gates and verify its truth table in quartus using Verilog programming

Developed by: Abishek P, 24901317

![image](https://github.com/user-attachments/assets/1e0f3061-e916-4ba3-a0cf-f38bf3399067)


Logic symbol & Truthtable
![387982053-17d7fc98-b3b2-42db-be5d-c9cfcf6f83e4](https://github.com/user-attachments/assets/e89ce4f7-9829-4472-be45-8aee8c0940e4)

RTL realization Output:
![393238558-c743df8c-42f5-4234-8588-244101a28b0a](https://github.com/user-attachments/assets/b2cf79a8-93cb-422d-bf0c-9cdfab2c0ad9)

RTL:
![393242241-7272d12c-190d-48fb-860d-9c178d388b46](https://github.com/user-attachments/assets/aefd2fa0-0fa0-4480-8ff2-839dfc9a99a0)

Result:
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.
