# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: SHIVAA PALANIYAPPAN V

# REGISTER NUMBER: 212223110050

# DEPARTMENT: CSE-IoT

# YEAR: II

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
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots:

Addition
![Screenshot 2025-03-14 154855](https://github.com/user-attachments/assets/9ac7ddb9-64e0-471a-a2e9-b325989de8e7)

![Screenshot 2025-03-14 155012](https://github.com/user-attachments/assets/b3b04e1d-cd09-4c7e-9da1-454c25278e36)

![Screenshot 2025-03-14 155110](https://github.com/user-attachments/assets/1dc69590-1fb6-44b6-bae3-d5fe11efbeef)

![Screenshot 2025-03-14 155140](https://github.com/user-attachments/assets/8d35306e-1a44-4b84-93ec-2e3103922d60)

Subtraction
![Screenshot 2025-03-14 155518](https://github.com/user-attachments/assets/aced54cf-c212-4944-9857-0babeec83232)

![Screenshot 2025-03-14 155555](https://github.com/user-attachments/assets/9710e000-6fb4-4d53-95a2-301e673e6eac)

![Screenshot 2025-03-14 155637](https://github.com/user-attachments/assets/46289df8-2cec-4565-b99e-d8b0680b016d)

![Screenshot 2025-03-14 155708](https://github.com/user-attachments/assets/b662850b-fab0-4eb8-b4f5-ff548b702e25)

Multiplication
![Screenshot 2025-03-21 091734](https://github.com/user-attachments/assets/52dee910-8f1e-4e8f-985e-406c58cc81dd)

![Screenshot 2025-03-21 091759](https://github.com/user-attachments/assets/5a9482e2-16f4-445d-a0c2-c64854af42be)

![Screenshot 2025-03-21 091816](https://github.com/user-attachments/assets/1e9ecf7d-746c-4172-a0ce-b96b2fe855b9)

![Screenshot 2025-03-21 091833](https://github.com/user-attachments/assets/c6ac6f59-1209-4ec2-b48b-0013327d1bc3)

Division
![Screenshot 2025-03-21 092131](https://github.com/user-attachments/assets/3cf41380-9f9e-43b1-914a-2118e1241b99)

![Screenshot 2025-03-21 092150](https://github.com/user-attachments/assets/f31e13c0-2cc1-492e-8e9e-e1f3d7f63547)

![Screenshot 2025-03-21 092215](https://github.com/user-attachments/assets/5af368c3-27bb-41a3-ae03-3fd9e60abbb3)

![Screenshot 2025-03-21 092656](https://github.com/user-attachments/assets/cc2f5476-2c5d-4698-8a4b-2ba42df49181)

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
