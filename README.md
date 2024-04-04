# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![image](https://github.com/Dilliarasu0105/FULL_ADDER_SUBTRACTOR/assets/144979593/39042e5e-a8e8-4790-bb78-af42a02ab778)

![image](https://github.com/Dilliarasu0105/FULL_ADDER_SUBTRACTOR/assets/144979593/ce02da14-d97a-4937-ab65-0cff668ff7d0)

**Procedure**

STEP 1: Use module project name(input,output) to start the Verilog programmming.


STEP 2: Assign inputs and outputs using the word input and output respectively.


STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean expression.


STEP 4: Use each output to represnt onre for differnce and the other for borrow. STEP 5: End the verilog program using keyword endmodule.
 

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by:DILLIARASU M 

RegisterNumber:212223230049

![image](https://github.com/Dilliarasu0105/FULL_ADDER_SUBTRACTOR/assets/144979593/bab34140-8c14-4701-80a6-c1ac0c14901a)

![image](https://github.com/Dilliarasu0105/FULL_ADDER_SUBTRACTOR/assets/144979593/10bd26d0-207a-41f2-9a45-f56b51883633)

*/

**RTL Schematic**

![image](https://github.com/Dilliarasu0105/FULL_ADDER_SUBTRACTOR/assets/144979593/2566c8fb-f2b3-48c7-9e83-e7dc350b9ae0)

**Output Timing Waveform**
![image](https://github.com/Dilliarasu0105/FULL_ADDER_SUBTRACTOR/assets/144979593/1abb84e6-7cb0-4aa2-9ca2-fa8e0f0df16d)

![image](https://github.com/Dilliarasu0105/FULL_ADDER_SUBTRACTOR/assets/144979593/ee1c322f-4bf7-4b27-b68d-36bdee63d322)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



