### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

1.Understanding the 8-3 encoder

2.Write the Verlog Code using Dataflow Modeling

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming.*/

**Developed by:Sugeshan S
**RegisterNumber:24007573


![encoder prog](https://github.com/user-attachments/assets/6d2ab387-b4f6-40aa-9acd-dba2bc141b48)

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**


![encoder rtl](https://github.com/user-attachments/assets/717ef649-1c91-45b3-b163-f495da8bed00)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**


![encoder waveform](https://github.com/user-attachments/assets/a5be868d-02eb-4edf-8899-601bae349c5d)

**RESULTS**
 
 Thus Encoder 8 to 3 in Dataflow Modelling is implemented using verilog and their functionality is validated using their functional tables.




