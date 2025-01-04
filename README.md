# HALF_ADDER_SUBTRACTOR

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

![Screenshot 2024-12-04 194907](https://github.com/user-attachments/assets/ca319d71-11b9-4efa-8298-1374cc14fd4c)

![ex32 truth table](https://github.com/user-attachments/assets/ad15f028-e352-4100-8afe-654f822e0740)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: judetarun RegisterNumber: 24003400

![Screenshot 2024-12-04 194525](https://github.com/user-attachments/assets/bd41367b-af2b-4634-be23-bd4b21c646ca)

![ex32](https://github.com/user-attachments/assets/507eef3b-39a6-4f0e-bd85-554a6bec858f)

**RTL Schematic**

![Screenshot 2024-12-04 194600](https://github.com/user-attachments/assets/4df38b76-2945-40e4-9566-da6a0e1c9ef2)
![image](https://github.com/user-attachments/assets/7658e909-1537-438f-9f3a-dcfa983d49c4)


**Output/TIMING Waveform**

![Screenshot 2024-12-04 194734](https://github.com/user-attachments/assets/3f01a35a-7421-46c8-a33d-f9a5af0a2e0f)

![ex32 wave](https://github.com/user-attachments/assets/5e13b8a7-ef8f-4bbb-89a7-bafe6d341454)

**Result:**
The truth table of the spcificed logic gates half adder and half subtractor circuit was successfully implemented and verificed using verilog prograingin quartus II.
