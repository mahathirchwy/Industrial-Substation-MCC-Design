# Industrial Substation & MCC Design

## Overview

This project presents the design and analysis of a simplified industrial electrical distribution system for a food-processing and packaging facility.

The system was developed using:

- **EPLAN Education** for electrical schematics and MCC diagrams
- **PowerWorld Simulator** for power-flow analysis
- **Google Sheets** for load calculations, equipment sizing, and results comparison

The design includes a **13.8 kV utility supply**, a **750 kVA transformer**, a **480 V main switchboard**, two motor control centers, auxiliary loads, motor protection, and multiple operating scenarios.

The goal of the project was to combine electrical design, motor control, equipment sizing, and power-system analysis into one complete industrial distribution project.

---

## Project Objectives

The main objectives of this project were to:

- Design a simplified industrial substation
- Size the main transformer and feeders
- Create a 480 V distribution system
- Design MCC motor-control circuits
- Compare DOL and VFD motor applications
- Create motor protection and control schematics
- Build a PowerWorld power-flow model
- Evaluate system voltages and equipment loading
- Study different plant operating conditions
- Identify potential expansion limitations

---

## System Architecture

The electrical system follows this structure:

```text
13.8 kV Utility
       |
       |
   Primary Protection
       |
       |
750 kVA Transformer
13.8 kV / 480 V
       |
       |
800 A Main Breaker
       |
       |
480 V Main Switchboard
       |
       |--------------------|--------------------|
       |                    |                    |
     MCC-1                MCC-2                AUX-1
     300 A                300 A                175 A
