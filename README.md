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
![321155193-ea8256d6-9793-43aa-9599-8edb471afa27](https://github.com/23008859/study-of-basic-gates/assets/139117979/2808da0b-c959-4d38-aa86-15c23d1cb4ca)
![319458613-e333ab21-f7bf-4aa0-8a6b-f69c57451122](https://github.com/23008859/study-of-basic-gates/assets/139117979/d180f3ab-4377-4636-9fa1-28fa23db7f89)
![321155726-ddeb460c-e5f3-45b6-a115-169e4397563c](https://github.com/23008859/study-of-basic-gates/assets/139117979/a184c108-39fd-40c5-bcb0-b3988d68efc7)
![319458650-7c6f142b-46a3-4e36-a4c7-76008d1b9832](https://github.com/23008859/study-of-basic-gates/assets/139117979/d118f02f-9570-43a9-b044-9dcb9cb9d076)
![321155801-1cad371c-4463-4d9d-a033-bdad05e1b6d1](https://github.com/23008859/study-of-basic-gates/assets/139117979/d4594b83-2d55-4bf2-b5b6-0f318fc26831)
![321155891-d24d2a06-0780-4e5d-8f4f-5cd5825b96a0](https://github.com/23008859/study-of-basic-gates/assets/139117979/79022b33-9a97-4d25-803d-6b55d1abdf7b)
![319459057-19d8cb59-7eab-4f7b-a45d-296947b83146](https://github.com/23008859/study-of-basic-gates/assets/139117979/cdc9eded-5a69-4fe9-b43d-b316aeb75a31)
![321157180-bbc077de-ee0e-446b-a62e-7117b5221b51](https://github.com/23008859/study-of-basic-gates/assets/139117979/f14a8365-01db-4b3b-99f6-e7f90eaff333)
![319458802-eb93295d-0d69-4b8f-bedd-99ec4f99c4aa](https://github.com/23008859/study-of-basic-gates/assets/139117979/28f65fa4-c363-4d98-bf75-fee0341412fe)
![321156830-d286b753-55ac-4244-a3bd-9b43f11fab22](https://github.com/23008859/study-of-basic-gates/assets/139117979/a2252430-b3a6-4898-906f-3ca728bbc552)
![319458857-dfcd8129-dc9c-47bf-9dc1-8d34142f0f81](https://github.com/23008859/study-of-basic-gates/assets/139117979/bb75d91d-662a-4118-96a5-516f3c130153)
![321156597-395f90c6-e3da-451d-baa9-93e89af26ad9](https://github.com/23008859/study-of-basic-gates/assets/139117979/00f23800-abe3-40b8-ac99-1baed4adbb88)
![319458896-ed25b34e-8a78-4fd1-9b9b-86894a498f7d](https://github.com/23008859/study-of-basic-gates/assets/139117979/2d4226fe-fee5-4589-966e-9ba59f45b2a9)



**RTL realization Output:** 
![314435924-ff9b3046-63ed-449d-bba6-e1a0cff0279b](https://github.com/23008859/study-of-basic-gates/assets/139117979/9d19c7d1-28bd-4006-8259-bd4b80964fdb)
![319249934-e4c2528d-b615-49a1-8c0d-eae421b8adcc](https://github.com/23008859/study-of-basic-gates/assets/139117979/6b5b64e3-0066-4c2c-b18f-8253b1315fcb)
![319459057-19d8cb59-7eab-4f7b-a45d-296947b83146](https://github.com/23008859/study-of-basic-gates/assets/139117979/087ec43e-1197-4654-9a3e-ef5032e92545)
![319257953-cd6af132-c459-4b8d-ae94-7acece134f68](https://github.com/23008859/study-of-basic-gates/assets/139117979/e993f6ac-c1ee-431e-8787-a8e5c77739c1)
![319259741-cdfb5e64-a652-4bf0-89d8-1d07528a4a42](https://github.com/23008859/study-of-basic-gates/assets/139117979/ec5fd67f-7888-4d8c-a7b2-bcb5cdd9d9db)
![319262447-d473eed3-f79f-48cf-a817-df2ec6c0eec2](https://github.com/23008859/study-of-basic-gates/assets/139117979/06c94e4c-7e81-44a4-9cac-327b4e3d4c9b)
![319457505-b87a09f9-a913-4428-bcb4-8a1d92176656](https://github.com/23008859/study-of-basic-gates/assets/139117979/e567ad84-edc8-46ed-8b52-bf5c5c448cdf)


**RTL**
![314435835-e6d8cd84-a6f9-494a-8dbe-14f5232a24b1](https://github.com/23008859/study-of-basic-gates/assets/139117979/466aa3c3-fe27-4c66-8a82-1c82e74f2279)
![319253722-18e815c2-415d-48a5-881e-a4073c55509d](https://github.com/23008859/study-of-basic-gates/assets/139117979/76045087-af15-4100-acae-f53548b82d9d)
![319255215-91e6f5d3-07b5-4f9e-8304-e633aa560a0a](https://github.com/23008859/study-of-basic-gates/assets/139117979/a12bf236-9136-42df-b55c-18a32f228b24)
![319257880-4af553bd-b913-4db8-a3ec-089a9482ad06](https://github.com/23008859/study-of-basic-gates/assets/139117979/a23ea558-24fa-4a21-8870-31b5b6a6abe8)
![319259667-7cfffafe-e298-41f7-9563-46a1f94f5972](https://github.com/23008859/study-of-basic-gates/assets/139117979/1edcae9d-5a6a-4930-8f75-c01653f27037)
![319262492-dbf2c102-470c-4de1-93f4-68449fe7390e](https://github.com/23008859/study-of-basic-gates/assets/139117979/8206c387-9295-4723-96cc-acbb1b8b9121)
![319266755-0a08d115-8fe8-4943-b322-66f16da0ec08](https://github.com/23008859/study-of-basic-gates/assets/139117979/b0db43f5-8fdd-4df5-ac33-f8381f37827c)


**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


