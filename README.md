# 6T_SRAM_Layout_Design_and_Verification
6T SRAM Layout Design and Verification Project
Overview
This project involves the design, simulation, and analysis of a CMOS 6-Transistor (6T) Static Random-Access Memory (SRAM) cell using Cadence Virtuoso. The SRAM cell is designed to store a single bit of data efficiently, ensuring high stability and low power consumption.

Software & Tools Used
Cadence Virtuoso (for schematic capture, layout, and simulation)
Assura (for DRC and LVS verification)
Analog Design Environment (ADE) (for waveform analysis)
Project Workflow
Schematic Design

Designed using Virtuoso Schematic Editor.
Includes six MOSFETs (4 NMOS & 2 PMOS) forming a cross-coupled inverter pair and access transistors.
Verified through Transient analysis.
Layout Design

Created using Virtuoso Layout Editor.
Optimized for area efficiency and minimal parasitics.
Design Rule Check (DRC) performed for layout validation.
Layout Versus Schematic (LVS) Check

Ensured the layout matches the schematic using LVS.
Parasitic Extraction & Post-Layout Simulation

Extracted layout using Assura.
Post-layout simulation performed to analyze parasitic effects.
Technical Specifications
Technology Node: 90nm (as per design constraints)
Supply Voltage (VDD): 1v
Word Line (WL) & Bit Line (BL) Operation
Read & Write Stability Analysis (SNM, Read/Write margins)
Results & Observations
Schematic Simulation: Verified correct read/write operations.
Layout Optimization: Ensured minimal area and DRC compliance.
Post-Layout Simulation: Observed deviations due to parasitic capacitance and resistance.
