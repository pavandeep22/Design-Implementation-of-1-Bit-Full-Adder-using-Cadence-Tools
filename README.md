# Ex No: 05 - Design & Implementation of 1-Bit Full Adder Using Cadence Virtuoso

## Aim
The aim is to design and implement a 1-bit Full Adder using Cadence Virtuoso and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the 1-bit Full Adder design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **Full Adder circuit** using **CMOS**.
- Connect the inputs (**A, B, Cin**) and outputs (**Sum, Cout**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the output logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

<img width="712" height="433" alt="image" src="https://github.com/user-attachments/assets/ac1969f6-b2b5-4394-9dba-d457dfa5ebe9" />


## Truth Table for 1-Bit Full Adder
![image](https://github.com/user-attachments/assets/328fae3c-b83a-4cd6-b394-54323dc59673)


## Schematic Diagram
### 1. Schematic of 1-Bit Full Adder:
<img width="1920" height="1080" alt="Schematic" src="https://github.com/user-attachments/assets/072885a1-163e-4c1b-8a75-f5862c142e14" />


![image](https://github.com/user-attachments/assets/1a962018-9d6b-4246-ab5f-424602551e87)



## Output
### Transient Analysis Output:
<img width="1920" height="1080" alt="Transient Setup" src="https://github.com/user-attachments/assets/9e07d294-c879-465e-9591-4756fdb67dc4" />
<img width="1920" height="1080" alt="ADE_L" src="https://github.com/user-attachments/assets/40da7a68-5b56-4565-aa7f-5687d342f701" />
<img width="1920" height="1080" alt="Output" src="https://github.com/user-attachments/assets/1ff1c5ab-ec78-4b3f-a6bc-e6de79355cff" />

## Results
1. Successfully designed the **1-bit Full Adder** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Full Adder**.
3. Observed **correct logic switching behavior** in response to input signals.
