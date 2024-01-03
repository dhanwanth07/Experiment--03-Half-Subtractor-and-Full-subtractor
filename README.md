## Name:A.Dhanwanth
## Reg:212223050011
## Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware 
PCs, Cyclone II , USB flasher
## Software 
Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.
## Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin
## Program:

## Half Subtractor
![Screenshot 2024-01-03 154549](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/230450eb-9304-4920-ab59-f078d9c61f84)


## Full Subtractor

![Screenshot 2024-01-03 154603](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/ca0a04ec-539d-4b9f-9edf-9cd4a98ba5e6)


Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: 

## Truthtable

## Half Subtractor
![Screenshot 2024-01-03 154611](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/e256434a-1388-4835-b179-80641aa90fb7)


## Full Subtractor

![Screenshot 2024-01-03 154620](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/ac43949e-323c-4f49-b7bd-a2643b271860)


##  RTL realization

## Half Subtractor

![Screenshot 2024-01-03 154626](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/81401eca-631e-4b1b-a730-230ef0127b69)

## Full Subtractor

![Screenshot 2024-01-03 154633](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/3b4af0e9-2e21-4103-b98f-71551d9c19e5)


## Timing diagram 

## Half Subtractor

![Screenshot 2024-01-03 154641](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/c924227b-2957-4441-8d14-51dd96dfc51e)

## Full Subtractor

![Screenshot 2024-01-03 154647](https://github.com/dhanwanth07/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/152170135/0af17396-4074-4270-88c0-8574943a162a)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
