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
Program:module hs(sum,carry,a,b);
input a,b;
output sum,carry;
xor sum1 (sum,a,b);
and carry1(carry,a,b);
endmodule
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: DANUSH REDDY
RegisterNumber:212223040029  
*/
Logic symbol & Truthtable
RTL realization

### Output:
###Full addar&half addar RTL:![image](https://github.com/danushreddy7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149035740/25155b22-da37-47bf-b5fe-ba49d33ce8bf)

###fulladdar&half addar TIMING DIAGRAM:![image](https://github.com/danushreddy7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149035740/99af3336-395b-4556-9281-7e38f26b1a99)



###full addar and half addar TRUTH TABLE:![image](https://github.com/danushreddy7/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149035740/eeea169e-a806-4c0a-aa99-515f92271970)


### Result:
