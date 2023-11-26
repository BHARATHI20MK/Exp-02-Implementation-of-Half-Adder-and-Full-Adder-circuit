# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
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

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: BHARATHI M K

RegisterNumber: 2310873 

Code:

Half Adder:
![ha code](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/830a009b-3cea-4a96-972a-ccfda6757e2f)

Full Adder:
![fa code](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/3e79f7b3-a164-4a6a-b660-ee28491ca0c6)


Truthtable:
Half adder:
![WhatsApp Image 2023-11-26 at 15 12 20_80be655f](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/64038f37-32ad-4859-b180-f2e15b42b73d)

Full adder:
![WhatsApp Image 2023-11-26 at 15 12 25_fc984f2a](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/1eab1bf6-1d72-44c9-b278-e80e389a1cd3)

RTL Diagram:
Half adder:
![ha rtl](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/8270e6b3-7f9a-4160-b4ac-acce3a3bc5a5)
Full adder:
![fa rtl](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/b67a6784-fe85-4cbf-8d8a-3e8357605bb8)

Output:
Half adder:
![ha wf](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/099ed68b-51a1-4235-b9a8-50896a27a7f0)
Full adder:
![fa wf](https://github.com/BHARATHI20MK/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474125/6bd849d5-9df7-4c77-accd-c955f9c78e98)

Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified
