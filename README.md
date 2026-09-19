# Modeling and Optimization of a Dielectric–Conductor Triboelectric Nanogenerator for Self-Powered Footstep Detection

## Overview

This project focuses on the theoretical modeling, simulation, validation, and optimization of a **dielectric–conductor triboelectric nanogenerator (TENG)** using MATLAB/Simulink.

The work investigates the electrical response of a dielectric–conductor TENG under contact–separation excitation and studies the influence of dielectric material properties and external load resistance on the generated electrical output.

The project also explores the potential use of the TENG as a **self-powered sensing element for footstep detection**.

---

## Objectives

1. Develop a theoretical and Simulink-based model of a dielectric–conductor TENG.
2. Validate the developed models against established theoretical and published results.
3. Compare the performance of different dielectric materials.
4. Investigate the effect of load resistance on the generated power.
5. Study the output of the TENG with a full-wave rectifier (FWR).
6. Explore a self-powered application based on footstep detection.

---

## Methodology

```text
Theoretical TENG Model
        ↓
MATLAB/Simulink Implementation
        ↓
Model Validation
        ↓
Dielectric Material Comparison
        ↓
Full-Wave Rectifier (FWR)
        ↓
Load Resistance Optimization
        ↓
Application Study

---

## Model Validation

### Infinite Parallel-Plate Benchmark

The initial TENG model was developed based on the theoretical framework reported by **Niu et al.** and implemented in MATLAB/Simulink to reproduce the reported analytical benchmark.

The model was evaluated for:

- Open-circuit voltage
- Transferred charge

The corresponding validation results are available in:

`Results/Validation/`

### Dielectric–Conductor Model

The dielectric–conductor model was implemented using the theoretical framework reported by **Dharmasena et al.**

The model was validated by comparing the simulated results with the corresponding theoretical results for:

- Transferred charge
- Short-circuit current

The validation results are available in:

`Results/Validation/`

### Validation Results

The repository contains the following validation plots:

- `Niu_Validation_Charge.png`
- `Niu_Validation_Voltage.png`
- `DDEF_Validation_Charge.png`
- `DDEF_Validation_Isc.png`



Self-Powered Footstep Detection
