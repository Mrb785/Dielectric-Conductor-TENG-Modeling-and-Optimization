Modeling and Optimization of a Dielectric–Conductor Triboelectric Nanogenerator for Self-Powered Footstep Detection
Overview
This project focuses on the theoretical modeling, simulation, validation, and optimization of a dielectric–conductor triboelectric nanogenerator (TENG) using MATLAB/Simulink.
The work investigates the electrical response of a dielectric–conductor TENG under contact–separation excitation and studies the influence of dielectric material properties and external load resistance on the generated electrical output.
The project also explores the potential use of the TENG as a self-powered sensing element for footstep detection.
Objectives
1. Develop a theoretical and Simulink-based model of a dielectric–conductor TENG.
2. Validate the developed models against established theoretical and published results.
3. Compare the performance of different dielectric materials.
4. Investigate the effect of load resistance on the generated power.
5. Study the output of the TENG with a full-wave rectifier (FWR).
6. Explore a self-powered application based on footstep detection.
Methodology
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
        ↓
Self-Powered Footstep Detection
Model Validation
Infinite Parallel-Plate Benchmark
The initial model was developed using the theoretical framework reported by Niu et al. and used as a benchmark for validating the Simulink implementation.
The model was evaluated for:
- Open-circuit voltage
- Transferred charge
Dielectric–Conductor Model
The dielectric–conductor model was validated using the theoretical framework reported by Dharmasena et al.
The validation includes:
- Transferred charge
- Short-circuit current
Validation results are available in:
Results/Validation/
Material Comparison
Five dielectric materials were investigated:
- PDMS
- PTFE
- Nylon
- Kapton
- PVC
Material Parameters
Material	Triboelectric Surface Charge Density, σT (μC/m²)	Relative Permittivity, εr
PDMS	30	3.24
PTFE	100	2.0
Nylon	120	3.5
Kapton	80	3.4
PVC	60	3.5


Simulation Conditions
Parameter	Value
Length, L	5 cm
Width, W	5 cm
Dielectric thickness, d	220 μm
Load resistance, R	1 GΩ
Maximum separation, H	2.5 mm
Frequency, n	1 Hz
Temperature	298 K


The mechanical input was defined as:
z(t) = H[sin(2πnt + 3π/2) + 1]
Material Comparison Results
Material	Peak Power	Peak Open-Circuit Voltage
PDMS	123.56 μW	10.075 kV
PTFE	1.621 mW	38.46 kV
Nylon	1.93 mW	39.59 kV
Kapton	0.866 mW	26.56 kV
PVC	0.483 mW	19.79 kV


The individual and combined comparison plots are available in:
Results/Material Comparison/
Load Resistance Optimization
A load-resistance sweep was performed to investigate the relationship between external resistance and average output power.
For the Nylon full-wave-rectifier model:
- Optimal Load Resistance: 1 GΩ
- Maximum Average Power: 2.719894 × 10⁻⁴ W
- Maximum Average Power: ≈ 0.271989 mW
The load optimization result is available in:
Results/Load_Optimization/
Full-Wave Rectifier
A full-wave rectifier (FWR) configuration was incorporated to investigate the rectified electrical output of the TENG.
The FWR model was used for the load-resistance optimization study.
Simulation Models
The Simulink models used in this project are provided in:
Simulink/
The repository includes models for:
- Infinite parallel-plate TENG validation
- Dielectric–conductor TENG modeling
- Full-wave-rectified dielectric–conductor TENG
The dielectric material simulations use the same underlying model structure with different material parameters.
Results
Results/
│
├── Validation/
│   ├── Niu_Validation_Charge.png
│   ├── Niu_Validation_Voltage.png
│   ├── DDEF_Validation_Charge.png
│   └── DDEF_Validation_Isc.png
│
├── Material Comparison/
│   ├── PDMS/
│   ├── PTFE/
│   ├── Nylon/
│   ├── Kapton/
│   ├── PVC/
│   ├── Power comparison.png
│   └── V_OC comparison.png
│
└── Load_Optimization/
    └── Load_optimization.png
Software and Tools
- MATLAB
- Simulink
- MATLAB plotting and analysis tools
Repository Structure
Dielectric-Conductor-TENG-Modeling-and-Optimization/
│
├── README.md
├── MATLAB/
├── References/
│   └── references.md
├── Results/
│   ├── Validation/
│   ├── Material Comparison/
│   └── Load_Optimization/
└── Simulink/
    ├── DDEF_KAPTON.slx
    ├── DDEF_Nylon_fwr.slx
    └── TENG_niu_validation.slx
References
The theoretical models, material parameters, and supporting literature used in this project are documented in:
[references.md](References/references.md)
Application
The proposed TENG model is intended to investigate the feasibility of using triboelectric energy generation for self-powered footstep detection.
The generated electrical response can potentially be used as a sensing signal for low-power sensing applications.
Authors
Maitreya Birhade
Kanishq Sakhare
B.Tech Mechanical Engineering
Indian Institute of Technology Indore
Project Status
Completed
- Theoretical TENG modeling
- Simulink implementation
- Infinite parallel-plate benchmark validation
- Dielectric–conductor model validation
- Comparison of five dielectric materials
- Full-wave rectifier implementation
- Load resistance optimization
Future Work
- Further investigation of TENG-based footstep detection
- Application-specific sensing analysis
- Further optimization of TENG electrical output
