# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
## AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin
#### Figure -01 HALF ADDER 
 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -02 FULL ADDER 

![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)



## Procedure
Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
## Program:
#### HALF ADDER
![CODE_HALF](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/d3df7156-3990-4639-85a1-2f2e333626e2)

#### FULL ADDER
![CODE_FULL](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/e3891da5-e2d0-4477-8c87-314fa1125332)

## Output:
### RTL realization
#### HALF ADDER
![RTL_HALF](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/c1367e3a-3151-43d5-9674-57b73e8da7af)

#### FULL ADDER
![RTL_FULL](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/c5544bc9-e556-4d8d-882d-4e3660fcd7d6)

### TIMING DIAGRAM
#### HALF ADDER
![TIMINGHALF](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/82a7e7db-581d-45fe-a71c-8163c0412b25)

#### FULL ADDER
![TIMINGFULL](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/be224c8b-3523-4a01-9b4d-e6c3c58e63a8)

### TRUTH TABLE 
#### HALF ADDER
![TTHALF](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/f3938eb8-a255-4efb-9a90-751415ae8f28)

#### FULL ADDER
![TTFULL](https://github.com/MOHAMEDAHSAN/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/139331378/8ea7fbb8-eb0f-491e-9890-6196f363f4ec)

## Result:
Thus the Implementation of Half Adder and Full Adder circuit are studied and the truth table for different logic gates are verified.
