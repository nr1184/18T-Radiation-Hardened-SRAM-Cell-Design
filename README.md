# 18T Radiation-Hardened SRAM Cell Design using Cadence Virtuoso

## Overview

This project focuses on the design and simulation of an 18-Transistor **(18T) Radiation-Hardened Static Random Access Memory (SRAM) Cell using Cadence Virtuoso**. The objective is to improve the reliability of SRAM in radiation-prone environments by enhancing resistance to **Single Event Upsets (SEUs)** while ensuring stable read, write, and hold operations.

The project includes transistor-level schematic design, simulation, power analysis, and custom layout implementation.

---

## Objectives

- Design an 18T radiation-hardened SRAM cell.
- Improve resistance against radiation-induced soft errors.
- Verify the functionality of the SRAM cell through simulations.
- Analyze power consumption and circuit behavior.
- Develop the physical layout following CMOS design rules.

---

## Tools Used

- Cadence Virtuoso
- Cadence Spectre Simulator
- CMOS Technology Library (PDK)

---

# Project Features

- Radiation-hardened 18T SRAM architecture
- Stable Read, Write, and Hold operations
- CMOS transistor-level implementation
- Custom layout design
- Power consumption analysis
- DC and transient simulations

---

# Project Workflow

```
Specification
      │
      ▼
Schematic Design
      │
      ▼
DC Analysis
      │
      ▼
Transient Analysis
      │
      ▼
Power Analysis
      │
      ▼
Layout Design
```

---

# Schematic Design

The SRAM cell was designed at the transistor level using CMOS technology in Cadence Virtuoso. Proper transistor sizing and connectivity were implemented to achieve reliable memory operation.

The schematic was verified for:

- Read operation
- Write operation
- Hold operation
- Correct logic functionality

---

# DC Analysis

DC simulations were performed to verify the operating point and static behavior of the SRAM cell.

The analysis was used to:

- Verify node voltages
- Confirm correct biasing
- Validate stable logic states
- Ensure reliable data retention during hold mode

---

# Transient Analysis

Transient simulations were carried out to study the dynamic behavior of the SRAM cell.

The following operations were verified:

- Write '1'
- Write '0'
- Read operation
- Hold operation

Simulation waveforms confirm the correct switching behavior and successful data storage.

---

# Power Consumption Analysis

Power analysis was performed to evaluate the energy efficiency of the SRAM cell during different modes of operation.

These results help assess the trade-off between improved reliability and power efficiency.

---

# Layout Design

A custom layout of the 18T SRAM cell was created using **Cadence Virtuoso Layout Editor** following standard CMOS layout design practices.

The layout includes:

- PMOS and NMOS transistor placement
- Metal routing
- Poly and diffusion layers
- Power and ground rails
- Well and substrate contacts

The layout was developed with attention to proper device placement, routing, and design-rule compliance.


---

# Applications

- Space Electronics
- Aerospace Systems
- Satellite Memory
- Radiation-Hardened Computing
- Safety-Critical Embedded Systems

---

# Future Work

- DRC and LVS verification
- Static Noise Margin (SNM) analysis
- Delay optimization
- PVT analysis
- SRAM array implementation

---

# Skills Demonstrated

- SRAM Cell Design
- Radiation-Hardened Circuit Design
- CMOS Design
- Cadence Virtuoso
- Cadence Spectre
- DC Analysis
- Transient Analysis
- Power Analysis
- Custom Layout Design

---

# Author

**R. Nishalini**  
Electronics and Communication Engineering

**Areas of Interest**

- VLSI Design
- Memory Design
- Analog IC Design
- Semiconductor Devices
