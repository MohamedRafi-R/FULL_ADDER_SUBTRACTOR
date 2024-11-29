# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![Screenshot 2024-11-29 181034](https://github.com/user-attachments/assets/f21d6468-284e-46d5-8d31-2a12154d0c60)

**Procedure**

Write the detailed procedure here 1 Type the program in Quartus software. 2
Compile and run the program. 3 Generate the RTL schematic and save the logic
diagram. 4 Create nodes for inputs and outputs to generate the timing diagram. 5 For
different input combinations generate the timing diagram.

**Program:**
![Screenshot 2024-11-29 181759](https://github.com/user-attachments/assets/1e50f5cb-412d-43b3-8301-a081f38b4c19)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**
![Screenshot 2024-11-29 181942](https://github.com/user-attachments/assets/1a810e44-1b85-41f2-8862-1c3f10b83da9)

**Output Timing Waveform**
![Screenshot 2024-11-29 182043](https://github.com/user-attachments/assets/ec30b667-776a-49b3-954d-b7a9d2f4e3dd)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



