# Physical-design-Workshop
A Workshop on VLSI SoC / Physical Design using Open-Source EDA tools by The VSD corp. Workshop is conducted on a cloud-based platform known as VSD-IAT, a user-friendly platform to learn and implement the essential skills in physical design using open-source EDA tools.

## Contents
1. Day 1: study various components of RISC-V microprocessor based SoC and review RISC-V picoSoC

## 1. Day 1: Study various components of RISC-V microprocessor based SoC and review RISC-V picoSoC 
Day 1 started with an Introduction to the IC design component terminologies. An overview of the QFN-48 Package, layout of the chip, pads, core, die and IPs.
RISC-V Instruction Set Architecture (ISA) was introduced and the RISC-V flow was explained. The flow starts with the C/C++/Java code being converted to an Instruction Set Architecture (ISA) by the compiler and the assembler converts this ISA into binary. The RTL implementation is done using Hardware Description Language (HDL) to create a netlist which is then laid out on the chip. 

PicoRV32 was introduced. It is a is a CPU core that implements the RISC-V RV32IMC Instruction Set. It's Pin diagram and salient features were discussed before moving to the PicoSoC whose brief layout and features were then discussed. Raven SoC which is a slight modification to PicoSoC was discussed before moving out for the synthesis.
#### Necessary EDA Tools for Physical Design:
- Yosys : RTL Netlist to Logic Synthesis
- Graywolf : Floor Planning, Placement, Clock Tree Synthesis
- Qrouter : Routing
- OpenTimer : Static Timing Analysis
- Magic : Layout
- NGSpice : Pre-layout and Post-layout spice simulations
- eSim : Circuit Design and Simulations
- Qflow : Tool Chain for complete RTS2GDS flow
The required tools were installed and working was checked with a sample design file.
## Lab
