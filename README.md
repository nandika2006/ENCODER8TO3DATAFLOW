**NAME:NANDIKA S**


**REGISTRATION NUMBER:24010030**

## EXPERIEMENT-5 ENCODER 8TO3 DATAFLOW Modelling

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

    1.Type the program in Quartus software.
    
    2.Compile and run the program.
    
    3.Generate the RTL schematic and save the logic diagram.
    
    4.Create nodes for inputs and outputs to generate the timing diagram.
    
    5.For different input combinations generate the timing diagram.

**PROGRAM**

![image](https://github.com/user-attachments/assets/544e5718-eb6f-4b3c-8f1b-4b845c9a5f4e)


/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: RegisterNumber:24010030
*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![image](https://github.com/user-attachments/assets/a7948dfa-96e4-4595-aff6-37de4f655acd)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![image](https://github.com/user-attachments/assets/1508d533-edc6-4913-a6bf-28631be67a2c)


**RESULTS**
implementing Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables executed succesfully.




