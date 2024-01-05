# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
 Hardware – PCs, Cyclone II , USB flasher
## Software 
Quartus prime


## Theory
A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.
 

## Logic Diagram
![293624609-601bcd5f-abd2-4da4-8679-0e143468d2d3](https://github.com/lekasri12/Experiment--02-Implementation-of-combinational-logic-/assets/149037427/27d70747-6218-49cf-9df9-d6350257f391)
![293624629-1d841768-6398-4f42-bbb3-8498ac2fac76](https://github.com/lekasri12/Experiment--02-Implementation-of-combinational-logic-/assets/149037427/5671a899-cd8e-4ea7-80f2-07fd692b2ebf)

## Procedure
Create a New Project: Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

Create a New Design File: *Once the project is created, right-click on the project name in the Project Navigator and select "Add New File." *Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

Write the Combinational Logic Code: *Open the newly created Verilog or VHDL file and write the code for your combinational logic.

4.Compile the Project:

*To compile the project, click on "Processing" > "Start Compilation" in the menu. *Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5.Analyze and Fix Errors:

*If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.

*Review and fix any issues in your code if necessary. *View the RTL diagram.

6.Verification:

*Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".

*Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.

*Give the Input Combinations according to the Truth Table and then simulate the Output Waveform.
## Program:

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: LEKA SRI G 
RegisterNumber: 212223100025 

## Output:
![286686638-4b8a9bda-055c-49ba-a7b9-399bb2742f50](https://github.com/lekasri12/Experiment--02-Implementation-of-combinational-logic-/assets/149037427/3f30671c-e684-4f12-bf03-d9e81982b7f8)
![286686732-c04ffff1-23da-4249-8898-ddc6a74cb3dd](https://github.com/lekasri12/Experiment--02-Implementation-of-combinational-logic-/assets/149037427/3ba56215-65da-471a-9a7e-eb155055acff)

## RTL
![286687267-6738f1de-353c-4de2-a2ae-7ce092389d4a](https://github.com/lekasri12/Experiment--02-Implementation-of-combinational-logic-/assets/149037427/d3cba99a-f6d8-4856-8d3c-87b333a2ab1b)

## Timing Diagram
![286687447-b2646966-d9c1-419c-bf86-a6bd714716ef](https://github.com/lekasri12/Experiment--02-Implementation-of-combinational-logic-/assets/149037427/25084836-de9c-4aef-9074-dfdc241e6827)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
