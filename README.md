# Full-Subtractor-CMOS-Design
Design and simulation of a Full Subtractor using CMOS logic with truth table verification

## 📘 Project Description
This project presents the design and simulation of a **Full Subtractor** using CMOS logic.  
The circuit is implemented using basic logic gates and verified through **truth table validation** and waveform simulations.

## 🔢 Inputs and Outputs
- **Inputs:** A, B, Borrow-in (C)
- **Outputs:** Difference, Borrow

## 📋 Truth Table Verification

| A | B | C | Difference | Borrow |
|---|---|---|------------|--------|
| 0 | 0 | 0 |     0      |   0    |
| 0 | 0 | 1 |     1      |   1    |
| 0 | 1 | 0 |     1      |   1    |
| 0 | 1 | 1 |     0      |   1    |
| 1 | 0 | 0 |     1      |   0    |
| 1 | 0 | 1 |     0      |   0    |
| 1 | 1 | 0 |     0      |   0    |
| 1 | 1 | 1 |     1      |   1    |

Simulation results match the expected truth table, confirming the correctness of the design.

## 🛠 Tools Used
- CMOS Logic Gates
- Circuit Simulation Tool (e.g., Cadence )

## 📊 Simulation Results
- Transient analysis performed
- Difference and Borrow outputs verified for all input combinations

## 📁 Files Included
- Full Subtractor Schematic
- Testbench Circuit
- Simulation Waveforms

## 🎯 Learning Outcomes
- Understanding of Full Subtractor logic
- CMOS-level digital design
- Truth table and waveform verification
- Practical VLSI fundamentals


