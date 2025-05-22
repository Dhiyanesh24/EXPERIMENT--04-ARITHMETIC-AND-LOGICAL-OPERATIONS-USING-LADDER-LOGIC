# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC


##  NAME: Dhiyaneshwar P
## REGISTER NUMBER:212222110009
## DEPARTMENT: CSE(IoT)
## YEAR: 3
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.

##  Simulation Screenshots:
### Addition 
![image](https://github.com/user-attachments/assets/09da847f-3f30-4779-a9c1-185dff17b768)
![image](https://github.com/user-attachments/assets/86cbdbb0-dbed-43f1-9967-1a9163699796)
![image](https://github.com/user-attachments/assets/a61750bf-ed15-4b74-a4ce-e3f3b5f1e7bd)
![image](https://github.com/user-attachments/assets/0b8e7945-9164-4d45-81ff-5f8e3cdaa41a)



### Subtraction

![image](https://github.com/user-attachments/assets/df17e6fb-3cbf-4f80-be25-873ac5ccf889)
![image](https://github.com/user-attachments/assets/77b7eb22-a1a7-47c1-acf0-06369d0b3b1d)
![image](https://github.com/user-attachments/assets/73c43db9-1baf-4c80-92b5-e5d9cf530228)
![image](https://github.com/user-attachments/assets/9e689520-ef77-41e8-af87-c9c398a3a203)

### multipliation

![image](https://github.com/user-attachments/assets/781f998f-b9bb-4b9f-af45-3b5b17849f05)
![image](https://github.com/user-attachments/assets/da4a328b-eadf-4df5-bdb7-47060652481d)
![image](https://github.com/user-attachments/assets/671a25ba-c893-47e4-9ca7-6ff3dbbb955a)
![image](https://github.com/user-attachments/assets/444c14c6-cf22-4c10-a5f7-5e25bb1fd754)


### Division
![image](https://github.com/user-attachments/assets/448af516-35d5-4379-a93d-743e93835398)
![image](https://github.com/user-attachments/assets/c3687f5c-347c-4a64-a709-bae910d91de2)
![image](https://github.com/user-attachments/assets/df630ae9-03c4-4bec-bfc1-ee7ea89f1e62)

![image](https://github.com/user-attachments/assets/096ccb51-c2e1-43b7-b556-fe98259a8bc7)


## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
