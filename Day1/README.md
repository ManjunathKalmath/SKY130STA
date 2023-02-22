# Day 1 - Basics of STA, SDC Overview, Clocks, Generated Clocks, Boundary Constraints

## Introduction to OpenSTA

OpenSTA is a gate level static timing verifier. As a stand-alone executable it can be used to verify the timing of a design using standard file formats. <br />
- Verilog netlist
- Liberty library
- SDC timing constraints
- SDF delay annotation
- SPEF parasitics

Inputs to OpenSTA : <br />
- Design (Netlist format, Usually provided in Verilog using read_verilog command)
- Standard Cells (Provided in .lib format using read_liberty command)
- Timing constraints (Provided in sdc format using read_sdc command)

## Lab1

![pic1](https://user-images.githubusercontent.com/48850794/220630845-cbdedbef-413a-42e2-8ec4-b193da040a1a.png)

![pic2](https://user-images.githubusercontent.com/48850794/220631132-ca1d613a-1fd7-4c94-8bb5-2dff0f1ad741.png)

![pic3](https://user-images.githubusercontent.com/48850794/220631262-d6c7e377-73f1-483c-917b-46c33c2ab134.png)

![pic4](https://user-images.githubusercontent.com/48850794/220631382-dac02627-2daa-4ec9-b3a3-0a4948c97d2a.png)

![pic5](https://user-images.githubusercontent.com/48850794/220631685-6aabf2d3-f1e8-4a19-be5b-55006bb82171.png)
