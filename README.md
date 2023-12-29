# Experiment--04-Half-Subtractor-and-Full-subtractor
# Name:vignesh.v
# Reference number:23004027
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
1.Use module projname(input,output) to start the Verilog programmming.

2.Assign inputs and outputs using the word input and output respectively.

3.Use defined keywords like wire,assign and required logic gates to represent the boolean expression.

4.Use each output to represnt onre for differnce and the other for borrow.

5.End the verilog program using keyword endmodule





## Program:
# Half Subtracter:
![WhatsApp Image 2023-12-29 at 22 54 09_26105274](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/c7827502-1498-4b6f-8835-88d8a1241e9b)

# Full Subtracter:
![WhatsApp Image 2023-12-29 at 22 55 13_834f9799](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/28270718-2e80-412a-b90f-c4a919b227b6)

# Truthtable:
# Half Subtracter:
![WhatsApp Image 2023-12-29 at 22 57 48_5ffb71c2](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/a3f8d7b2-a54c-4a8d-adbe-4019c287fd49)

# Full Subtracter:
![WhatsApp Image 2023-12-29 at 22 57 48_7fdeaf1e](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/e74dafc9-f89b-4256-994d-2ce6a4171c58)

### RTL realization:
# Half Subtracter:
![WhatsApp Image 2023-12-29 at 22 57 48_ab153138](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/9928203d-2782-41f8-87bb-747fe27063dd)

# Full Subtracter:
![WhatsApp Image 2023-12-29 at 22 57 49_3d1691a6](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/8b792f6e-17d0-4edc-a90d-e594c59fe3e9)

## Output:
# Half Subtracter:
![WhatsApp Image 2023-12-29 at 22 57 07_f350bdfd](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/f7932ef2-1474-4f70-b433-1f93c78ca3a3)

# Full Subtracter:
![WhatsApp Image 2023-12-29 at 22 57 08_5856f047](https://github.com/23004027/Experiment--04-Half-Subtractor-and-Full-subtractor/assets/138956447/d5ceff0a-96f1-4b4f-9ae2-69e03b914831)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
