 ***This repository contains a collection of digital design projects developed for a university-level Computer Architecture Laboratory, implemented entirely in VHDL.
Each project focuses on one or more core components of a typical CPU datapath or digital system, ranging from low-level logic circuits to complete computing subsystems.***

The modules are designed with clarity and modularity in mind, allowing for easy integration into simulation environments or deployment on FPGAs.
The collection serves both as a learning resource for students and a practical foundation for more advanced architecture design.

🔍 Included Modules
**Arithmetic Logic Unit (ALU)

 A fully functional 8-bit ALU capable of performing 5 basic operations: ADD, SUB, AND, OR, and NOT.

 Includes carry-in/carry-out, zero, and parity status flags for result tracking and control logic.

**Harvard Mini-Computer Architecture

A simplified CPU core based on the Harvard architecture with separate instruction and data memories.

Includes a basic control unit, register set, and system bus for executing simple programs and instructions.

**1 KB RAM Module

A synchronous single-port memory block with 1024 × 8-bit capacity.

Supports read/write operations and address decoding, suitable for storing instructions or data.

**Parity Detector

A combinational circuit that checks the parity (even or odd) of an 8-bit input word.

Useful in error detection subsystems or digital communication interfaces.

**8-bit Up/Down Counter

A synchronous counter that can count upwards or downwards based on a control signal.

Supports reset and direction control, and can be used in timing or control circuits.

**Configurable Timer using IP Cores

A programmable timer module built using vendor-specific IP blocks (e.g., Xilinx Vivado or Intel Quartus).

Designed to generate precise time intervals or delays with interrupt output.

**Square-Wave Signal Generator

Generates square-wave signals with customizable period and duty cycle.

Ideal for waveform generation, pulse-width modulation (PWM), or clock simulation.

**Seven-Segment Display Up Counter

A module that drives a 7-segment display (common anode/cathode) to show incrementing numerical values.

Includes multiplexing logic to manage multiple digits with minimal hardware lines.

