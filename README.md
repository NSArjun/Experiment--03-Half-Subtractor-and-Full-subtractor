# Experiment--04-Half-Subtractor-and-Full-subtractor
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
STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.

## Program:
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: ARJUN N S
RegisterNumber:  23013905
## CODE:
### HALF SUBTRACTOR:
![Exp4 hs code](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/a885ff02-f391-4ff8-9266-e95778fe660e)


### FULL SUBTRACTOR:
![Exp4 fs code](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/68ebc117-a29c-4b4c-8e1e-6d7e18554681)


## OUTPUT:
## Truthtable:
### HALF SUBTRACTOR:
![Exp4 truthtable hs](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/9e15da11-e759-4cdb-8680-a0310db20e95)

### FULL SUBTRACTOR:
![Exp4 truthtable fs](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/1292b6e4-258b-47a5-b88a-8835c6f3c491)

##  RTL:
### HALF SUBTRACTOR:
![Exp4 hs RTL diagram](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/53615605-3695-43eb-8376-bb3d744ffafc)

### FULL SUBTRACTOR:
![Exp4 fs RTL diagram](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/8bae1bf3-d243-4795-821c-9ca4d33f37eb)


## Timing diagram:
### HALF SUBTRACTOR:
![hs wave](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/b7e3955a-8fbc-4f9d-ab8a-19b5c983f8c9)

### FULL SUBTRACTOR:
![fs wave](https://github.com/NSArjun/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/148233801/954abcf7-846e-4b9f-8532-8d8af9611397)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
