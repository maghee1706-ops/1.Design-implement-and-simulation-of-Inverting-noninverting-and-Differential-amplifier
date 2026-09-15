# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/7680c60a-a1ab-410d-b0b0-de3c85642f17" />


  **MODEL GRAPH:**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/039f6c97-2bc5-4d2f-aae3-93d441c52a42" />


  **TABULATION:**
 <img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/6dc520b1-06a0-4a9a-be60-bab3d11fb431" />


**MODEL CALCULATION:**

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**

<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/7059dc75-77ca-4a96-9ab0-1344a5e27e5b" />

  **MODEL GRAPH:**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/dbdf00d9-d5ea-4ffd-a337-60ae933b58d6" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/953754f3-55a4-48c3-98f9-0b12f93bfd50" />


  **TABULATION:**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/c0b933fe-b15f-4521-8d94-43797787cce7" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/9c3b9a8f-10d5-4da7-b08d-f166751f4836" />


  **MODEL GRAPH:**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/fa8f6f74-e585-4224-b2cf-f1da8bffbb81" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/69adb2bc-58a8-4c98-a52c-85bcc08a1e32" />


  **TABULATION:**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/72b75baa-47be-4a44-a27c-09677d519d8e" />

**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/659cb31c-4460-4e2c-b938-46b36abc9a2a" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/dc95bb64-0726-4eda-bdfe-c19598cb1afa" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/5364588f-9da9-4c68-8c0d-910a91e2585e" />


  

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






