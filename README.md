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

Developed by: VISWA PRAKAASH N J

RegisterNumber:  23001661

Code:

Half Subtractor:

![Exp4 hs code - Copy](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/3da386f1-ddbc-4d6f-ba66-0c75070f5fc9)

Full Subtractor:

![Exp4 fs code](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/14db87ad-3a79-49a4-9e57-1610a6c31a6a)

Truth table:

Half subtractor:

![Exp4 truthtable hs](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/aefb72fd-13e0-4127-a02f-061af656fde2)

Full   Subtractor:

![Exp4 truthtable fs](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/3bffbfb4-5059-4da4-80e2-2307c19ce089)

RTL Diagram:

Half Subtractor:

![Exp4 hs RTL diagram](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/0f79d4d1-e3df-4be1-934a-efba0707f727)

Full Subtractor:

![Exp4 fs RTL diagram](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/1dceddff-dffd-489b-aa94-87ea869e24e0)

## Output:

Half Subtractor:

![Exp3 hs wave](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/083bfa6c-768f-4451-aad7-ccf9244f21b0)

Full Subtractor:

![Exp3 fs wave](https://github.com/ViswaPrakaashNJ/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150996664/6a735c4a-3cd5-415b-ab8e-6a3d34821f9c)





## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
