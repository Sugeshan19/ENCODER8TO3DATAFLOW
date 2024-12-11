### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![368f73f1-b0a5-4d27-b88f-3812a7a7eb89](https://github.com/user-attachments/assets/d38c2383-ba34-4309-9bbe-3bbc6996a691)


Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![67994288-9a84-4c4d-ac56-6fca01468d47](https://github.com/user-attachments/assets/a713c71b-91bd-44ed-89b0-d397f69506e1)


The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![Screenshot 2024-12-12 000459](https://github.com/user-attachments/assets/369df6b6-e619-4235-8134-83e8e72eb841)


Figure 02  Encoder 8 * 3

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by:Sugeshan.S RegisterNumber:24007573

```
module encoder(a,b,c,y0,y1,y2,y3,y4,y5,y6,y7);
input y0,y1,y2,y3,y4,y5,y6,y7;
output a,b,c;
assign a= ( y4 | y5 | y6 | y7);
assign b= ( y2 | y3 | y6 | y7);
assign c= ( y1 | y3 | y5 | y7);
endmodule
```


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-12-12 000804](https://github.com/user-attachments/assets/55c63eab-9f66-4b52-b2d4-267e408f66a2)

**RESULTS**
Thus the truth table of a logic for Encoder 8 to 3 in dataflow modelling in Quartus|| using verilog programming are studied,verified and executed successfully.





