# Day 1 - Basics of STA, SDC Overview, Clocks, Generated Clocks, Boundary Constraints

## Introduction to OpenSTA

OpenSTA is a gate level static timing verifier. As a stand-alone executable it can be used to verify the timing of a design using standard file formats. <br />
- Verilog netlist
- Liberty library
- SDC timing constraints
- SDF delay annotation
- SPEF parasitics

Inputs to OpenSTA <br />
- Design (Netlist format, Usually provided in Verilog using read_verilog command)
- Standard Cells (Provided in .lib format using read_liberty command)
- Timing constraints (Provided in sdc format using read_sdc command)
