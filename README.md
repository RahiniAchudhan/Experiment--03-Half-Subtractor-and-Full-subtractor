# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by: RAHINI A

RegisterNumber:  23012479
*/

# HALF SUBTRACTOR:

![HALF SUB PROGRAM](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/069fce14-d5e8-467c-92d6-098e0ed74b7b)

# RTL VIEW OF HALFSUBTRACTOR:

![RTL HALF SUB](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/e86c6c9b-fbeb-46c6-9dd3-4d9cb7015ef0)

# TRUTH TABLE:

![TRUTH HALF SUB](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/5cb5493b-54fd-41ed-9722-219a80d62a13)

# WAVEFORM OF HALFSUBTRACTOR:

![WAVE HALF SUB](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/8ccaa062-e4db-44a8-802c-58b9c133e9d3)


# FULL SUBTRACTOR:

![full sub program](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/05f43306-462e-437e-b3e4-a1330b8deaf5)

# RTL VIEW OF FULLSUBTRACTOR:

![RTL FULLSUB](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/93c871f3-7193-43c4-8f66-5f1f207b3ebe)

# TRUTH TABLE:

![TRUTH FULLSUB](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/1dd740d6-a351-483f-a638-d151f9f148cf)

# WAVEFORM OF FULLSUBTRACTOR:

![WAVE FULLSUB](https://github.com/RahiniAchudhan/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145742838/9b407083-0ba7-43b0-99eb-73707b975f02)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
