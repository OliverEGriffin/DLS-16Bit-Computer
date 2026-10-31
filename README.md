# DLS-16Bit-Computer
16Bit computer made in Digital logic Simulator

This was a fun project I took on over the summer of 2026.

-------------------------------------------------- Contents --------------------------------------------------
- Features
- Project Parts
- Install Instructions
- CPU Overview
- Program Codes/Instructions
- Programming Language


-------------------------------------------------- Features --------------------------------------------------

CPU Features include:
- 16 Address Bits
- 16 Data Bits
- 21 simulation steps per clock cycle 
  - This assumes a stable output, fee free to try and overclock it
  - Simulation runs at ~400 steps per second meaning an effective clock frequency of ~ 20Hz

-------------------------------------------------- Project Parts --------------------------------------------------
The project consists of Several Parts: 
 - A DLS simulation
 - A compiler (Written in Python)
 - A Notepad++ Extension for program formatting
 - A Spreadsheet for each Operation Code



It is possible (and encouraged!) you write programs with

-------------------------------------------------- Install Instructions --------------------------------------------------


--------------------------------------------------  CPU Overview --------------------------------------------------

Clock
The clock has 4 states:
High, High Buffer, Low and Low Buffer. These are used for timing read and writes throughout the CPU. Generally the buffers are used to stop unpredictable behaviour when an output of a chip enters the input of the same chip.


<img width="661" height="495" alt="image" src="https://github.com/user-attachments/assets/a2ca81cd-7ecd-4d15-b30c-0a56b2674ccd" />
This shows the last transition state of the clock.
