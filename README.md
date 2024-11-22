# EXP3: HALF ADDER AND SUBTRACTOR
## NAME:MOHAMMED HAMZA M
## REGISTRATION NUMBER:24900511



Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
![HALF SUBTRACTOR TRUTH TABLE](https://github.com/user-attachments/assets/04c27b96-9f2c-4cee-a34c-ebad84ba0890)
![HALF ADDER TRUTH TABLE](https://github.com/user-attachments/assets/a7bb5d10-a3eb-45e9-a295-283eb468b7cf)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
![HALF SUBTRACTOR CODE](https://github.com/user-attachments/assets/207102fd-75f5-461b-a287-7b111bd58bd5)
![HALF ADDER CODE](https://github.com/user-attachments/assets/f46e894e-74e4-483e-bd3e-135c59e9ba86)

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/

**RTL Schematic**
![HALF SUBTRACTOR GATE](https://github.com/user-attachments/assets/467bfe08-b552-43a0-97d3-2afb42fcdca8)
![HALF ADDER GATE](https://github.com/user-attachments/assets/a31a5940-a8d0-4d7e-b193-512c53b8357d)


**Output/TIMING Waveform**
![HALF SUBTRACTOR WAVEFORM](https://github.com/user-attachments/assets/b474ec30-f051-4c7c-8af0-3274e2e4e318)
![HALF ADDER WAVEFORM](https://github.com/user-attachments/assets/ecda225e-265e-40ae-aae8-adefe77e7836)

**Result:**
