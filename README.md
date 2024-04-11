### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
```
module logic_gate(a,b,y1,y2,y3,y4,y5,y6,y7);
input a,b;
output y1,y2,y3,y4,y5,y6,y7;
and(y1,a,b);
or(y2,a,b);
not(y3,a);
nand(y4,a,b);
nor(y5,a,b);
xor(y6,a,b);
xnor(y7,a,b);
endmodule
```

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: ROSHINI S
 RegisterNumber: 212223230174
 Depatment: AIDS
 
**Logic symbol & Truthtable**
![319458613-e333ab21-f7bf-4aa0-8a6b-f69c57451122](https://github.com/23008859/study-of-basic-gates/assets/139117979/74530593-4b2d-425b-9496-b84cc7888656)
![319458650-7c6f142b-46a3-4e36-a4c7-76008d1b9832](https://github.com/23008859/study-of-basic-gates/assets/139117979/3889afff-15cd-4a0a-839b-c3f462606bce)
![319459057-19d8cb59-7eab-4f7b-a45d-296947b83146](https://github.com/23008859/study-of-basic-gates/assets/139117979/47b749fe-ff6a-4695-b89e-dd8de3b5ca7f)
![319458770-a0137613-8911-48f3-b17b-8f2829320975](https://github.com/23008859/study-of-basic-gates/assets/139117979/aa6c4eaa-7411-4287-b43c-63ab8e966c03)
![319458802-eb93295d-0d69-4b8f-bedd-99ec4f99c4aa](https://github.com/23008859/study-of-basic-gates/assets/139117979/243d43ae-53f7-4c21-8eb8-4d443f4a121c)
![321156830-d286b753-55ac-4244-a3bd-9b43f11fab22](https://github.com/23008859/study-of-basic-gates/assets/139117979/144a73e0-941a-4607-a0e8-ef8030462865)
![321156597-395f90c6-e3da-451d-baa9-93e89af26ad9](https://github.com/23008859/study-of-basic-gates/assets/139117979/7658262b-9469-4a78-bf60-d0f68bd100eb)


**RTL realization Output:** 
![314435924-ff9b3046-63ed-449d-bba6-e1a0cff0279b](https://github.com/23008859/study-of-basic-gates/assets/139117979/450b0109-3e47-440a-a1dc-ee2efd94d551)
![319249934-e4c2528d-b615-49a1-8c0d-eae421b8adcc](https://github.com/23008859/study-of-basic-gates/assets/139117979/1c31c5c3-315d-4dfb-9382-58e0f74eda96)
![319255215-91e6f5d3-07b5-4f9e-8304-e633aa560a0a](https://github.com/23008859/study-of-basic-gates/assets/139117979/445c510f-c63a-4f66-b850-316e689e8deb)
![319257953-cd6af132-c459-4b8d-ae94-7acece134f68](https://github.com/23008859/study-of-basic-gates/assets/139117979/5fdf2a2d-bc3a-42c9-860d-2c7e1b6ce757)
![319259741-cdfb5e64-a652-4bf0-89d8-1d07528a4a42](https://github.com/23008859/study-of-basic-gates/assets/139117979/554032e9-8d7d-41ae-b718-b0fd5ee0e56d)
![319262447-d473eed3-f79f-48cf-a817-df2ec6c0eec2](https://github.com/23008859/study-of-basic-gates/assets/139117979/b31f7fec-9f5d-482d-ac22-97f3560e5b2f)
![319266755-0a08d115-8fe8-4943-b322-66f16da0ec08](https://github.com/23008859/study-of-basic-gates/assets/139117979/b0b4587b-1b0f-4177-b524-1208fde586a5)


**RTL**
![314435924-ff9b3046-63ed-449d-bba6-e1a0cff0279b](https://github.com/23008859/study-of-basic-gates/assets/139117979/dce08cae-dd75-49b4-a3d6-a7c32390d580)
![319249934-e4c2528d-b615-49a1-8c0d-eae421b8adcc](https://github.com/23008859/study-of-basic-gates/assets/139117979/e6913000-7744-45dd-a14f-b470ed8c7c95)
![319255215-91e6f5d3-07b5-4f9e-8304-e633aa560a0a](https://github.com/23008859/study-of-basic-gates/assets/139117979/4e559baa-075e-4d36-96ab-22c6b0f36949)
![319257953-cd6af132-c459-4b8d-ae94-7acece134f68](https://github.com/23008859/study-of-basic-gates/assets/139117979/b6a8c799-9f2a-4d5d-9332-751c2d09be09)
![319259741-cdfb5e64-a652-4bf0-89d8-1d07528a4a42](https://github.com/23008859/study-of-basic-gates/assets/139117979/35447620-c669-4758-97f9-bd03add09969)
![319262492-dbf2c102-470c-4de1-93f4-68449fe7390e](https://github.com/23008859/study-of-basic-gates/assets/139117979/c7384c38-2adb-4037-9e31-8183768fc0d2)
![319457505-b87a09f9-a913-4428-bcb4-8a1d92176656](https://github.com/23008859/study-of-basic-gates/assets/139117979/262c2102-ebe2-4c87-9304-81a1b6180988)


**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


