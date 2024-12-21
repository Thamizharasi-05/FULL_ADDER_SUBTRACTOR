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

Full Adder

![Screenshot 2024-12-21 104046](https://github.com/user-attachments/assets/c571a6dd-f8ae-4804-823e-be8ac54731b5)

Full Subtractor

![Screenshot 2024-12-21 104113](https://github.com/user-attachments/assets/7df223eb-92d8-41b0-90ac-94a000e7a54f)

**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

Designed By: Thamizharasi G

Reference Number: 24001123

**Program:**

Full Adder

![Screenshot 2024-12-21 103955](https://github.com/user-attachments/assets/0dae6d78-97bb-4c44-88a2-fbd01968389d)

Full Subtractor

![Screenshot 2024-12-21 104541](https://github.com/user-attachments/assets/dc4d8fcc-c4dd-4053-b50a-eb255b699af2)

**RTL Schematic**

Full Adder

![Screenshot 2024-12-21 103633](https://github.com/user-attachments/assets/f3b45a47-33f2-49f9-a286-6fe59826554b)

Full Subtractor

![Screenshot 2024-12-21 104608](https://github.com/user-attachments/assets/6600bb4d-7a57-485f-a680-42fff4ab2306)

**Output Timing Waveform**

Full Adder

![Screenshot 2024-12-21 111643](https://github.com/user-attachments/assets/9abdb452-a671-46b9-9cda-59d381b8c7be)

Full Subtractor

![Screenshot 2024-12-21 112046](https://github.com/user-attachments/assets/f7dd4557-7a0c-455b-a4fd-949bf6edea7a)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



