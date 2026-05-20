<div align="center">

# Sadik Yasir Tauki

### Ph.D. Student · Computer Architecture · Emerging Memory · ML Hardware Systems

*Computer Science & Engineering @ Penn State · Microsystems Design Lab*

[![Email](https://img.shields.io/badge/Email-mpt5708@psu.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mpt5708@psu.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sadik%20Yasir%20Tauki-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sadikyasir/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Site-000000?style=flat&logo=githubpages&logoColor=white)](https://sites.google.com/view/tauki/home)

</div>

---

## About Me

I am a Ph.D. student in **Computer Science and Engineering at Penn State University**, working in the **Microsystems Design Lab** under **Prof. Vijaykrishnan Narayanan**.

My research sits at the intersection of **emerging non-volatile memory**, **VLSI circuit design**, **computer architecture**, and **machine learning systems**. I am especially interested in how new memory technologies such as **FeRAM, FeFET, and selector-assisted memory arrays** can be modeled, designed, and integrated into efficient computing systems.

My work spans multiple abstraction layers:

```text
Device Physics → Compact Modeling → Circuit Design → Architecture → ML Systems
      └────────────────── end-to-end hardware co-design ──────────────────┘
```

I use **TCAD, SPICE, Verilog-A, RTL design, architecture simulators, and ML frameworks** to study how device-level behavior affects circuit reliability, memory-array scalability, and system-level performance.

---

## Research Focus

My current research focuses on:

- **Emerging Non-Volatile Memory**
  - FeRAM, FeFET, RRAM-inspired selector devices, and spintronic memory modeling
  - Compact modeling of switching dynamics, retention, endurance, and variability
  - Device-to-circuit integration for scalable memory arrays

- **Processing-in-Memory and Compute-in-Memory**
  - In-memory MAC architectures for DNN inference
  - Charge-domain and multi-level memory-based computation
  - Memory-centric accelerator design for energy-efficient AI systems

- **Device–Circuit–Architecture Co-Design**
  - TCAD-to-SPICE modeling workflows
  - Circuit-level evaluation of memory cells, selectors, and sense schemes
  - Architecture-level analysis of memory hierarchy and accelerator performance

- **Computer Architecture and ML Systems**
  - Out-of-order processor design-space exploration
  - Cache and memory-system performance modeling
  - Systolic array optimization for CNN and sequence workloads
  - Hardware-aware ML and accelerator evaluation

- **DRAM Reliability and Security**
  - RowHammer disturbance errors
  - DRAM reliability mechanisms
  - Memory-system security and mitigation strategies

---

## Featured Projects

| Project | Description | Tools / Methods |
|---|---|---|
| ⚙️ **[Out-of-Order Processor Design Space Exploration](#)** | Explored CPU microarchitecture trade-offs by sweeping pipeline width, ROB size, and branch-predictor configurations. Identified performance saturation behavior and proposed a balanced OoO core design. | gem5, Python, performance analysis |
| 🧮 **[Systolic Array Optimization for Neural Networks](#)** | Evaluated array size and dataflow choices for YOLO-Tiny, MobileNet, and OCR workloads. Studied utilization, latency, and performance-efficiency trade-offs. | Scale-Sim, Python, CNN workloads |
| 🔥 **[MIND-MAC: In-Memory MAC using 2T-nC FeRAM](#)** | Designed a multi-level non-volatile memory-based in-memory MAC architecture for DNN inference. Demonstrated high energy efficiency and quasi-non-destructive readout behavior. | Cadence Spectre, FeRAM, PIM |
| 🧬 **[FeFET CIM for Bioinformatics](#)** | Designed a charge-domain compute-in-memory architecture for Needleman–Wunsch sequence alignment using multi-state FeFET memory cells. | FeFET, CIM, sequence alignment |
| 🏭 **[Full-Custom ASIC Design Flow](#)** | Implemented a complete ASIC design flow including RTL design, verification, synthesis, layout, DRC/LVS, parasitic extraction, and corner analysis. | Verilog, SystemVerilog, Cadence, Genus |
| 💾 **[DRAM Reliability and RowHammer Review](#)** | Studied RowHammer disturbance errors, attack mechanisms, and defense techniques from device, architecture, and system perspectives. | DRAM, reliability, security |
| 🔬 **[Ferroelectric Capacitor Compact Modeling](#)** | Developed physics-based modeling workflows for ferroelectric capacitor behavior, including large-signal P–V response and small-signal C–V characteristics. | MATLAB, Verilog-A, FeCAP modeling |
| 🧱 **[Selector-Assisted FeRAM Crossbar Arrays](#)** | Analyzed selector-enhanced FeRAM arrays for disturb mitigation, access-voltage scaling, write energy, and array-level reliability. | TCAD, SPICE, Python |

---

## Publications and Research Works

1. **“MIND-MAC: Multi-Level In-Memory Quasi Non-Destructive MAC Operation in Compact 2T-nC FeRAM for Efficient DNN Accelerator”**  
   *Non-Volatile Memory Technology Symposium, NVMTS 2025*

2. **“Understanding Reliability Trade-offs in 1T-nC and 2T-nC FeRAM Designs”**  
   *IEEE Journal on Exploratory Solid-State Computational Devices and Circuits, JxCDC*

3. **“Towards Scalable 3D Integration of 2T-nC FeRAM with Hundreds of Layer Stacking”**  
   *International Electron Devices Meeting, IEDM 2025*

4. **“Vertical 2T-nC FeRAM Demonstration: BEOL Read Transistor for 4F² Memory Strings and Two-Terminal Selector Design for Polarization Disturb Mitigation”**  
   *Symposium on VLSI Technology & Circuits 2025*

5. **“Modeling Second Order Anisotropy of Monodomain Magnetic Body”**  
   *International Conference on Electrical and Computer Engineering, ICECE*

---

## Technical Skills

### Device, Circuit, and Memory Design

![Cadence](https://img.shields.io/badge/Cadence%20Virtuoso-A100FF?style=flat&logoColor=white)
![Spectre](https://img.shields.io/badge/Cadence%20Spectre-6A0DAD?style=flat&logoColor=white)
![TCAD](https://img.shields.io/badge/Sentaurus%20TCAD-0078D4?style=flat&logoColor=white)
![HSPICE](https://img.shields.io/badge/HSPICE-444444?style=flat&logoColor=white)
![Verilog-A](https://img.shields.io/badge/Verilog--A-FF6600?style=flat&logoColor=white)

- Ferroelectric memory modeling: FeRAM, FeFET, FeCAP
- TCAD-based device simulation and structure analysis
- SPICE and Verilog-A compact modeling
- CMOS/FinFET circuit design
- Sense amplifiers and memory peripheral circuits
- Selector-assisted memory arrays
- Retention, endurance, and reliability analysis

### Computer Architecture and Systems

![gem5](https://img.shields.io/badge/gem5-FF6B35?style=flat&logoColor=white)
![ScaleSim](https://img.shields.io/badge/Scale--Sim-2E86C1?style=flat&logoColor=white)
![NeuroSim](https://img.shields.io/badge/NeuroSim-8E44AD?style=flat&logoColor=white)
![CACTI](https://img.shields.io/badge/CACTI-117864?style=flat&logoColor=white)

- Out-of-order processor design-space exploration
- Cache hierarchy and memory-system analysis
- PIM and near-memory computing architectures
- Systolic array accelerator modeling
- Performance, power, and area evaluation
- Workload-driven hardware optimization

### Digital Design and ASIC Flow

![Verilog](https://img.shields.io/badge/Verilog%2FVHDL-FF6600?style=flat&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-00599C?style=flat&logoColor=white)
![Synopsys](https://img.shields.io/badge/Synopsys-DC3545?style=flat&logoColor=white)
![Genus](https://img.shields.io/badge/Cadence%20Genus-8E44AD?style=flat&logoColor=white)

- RTL design and verification
- SystemVerilog testbench development
- Constrained random verification
- Synthesis and static timing analysis
- DRC/LVS and parasitic extraction
- Full-custom layout and standard-cell design

### ML, Programming, and Data Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)

- Python, C/C++, MATLAB, Bash
- PyTorch, TensorFlow, TensorRT, ONNX
- NumPy, Pandas, Matplotlib, Jupyter
- Hardware-aware ML model evaluation
- Data visualization and simulation automation
- Linux, Git, Docker, HPC workflows

---

## Selected Research Themes

### Emerging Memory for Future Computing

Modern computing systems are increasingly limited by data movement between memory and compute units. My research explores how emerging non-volatile memory technologies can enable denser, more energy-efficient, and more computation-capable memory systems.

I study memory technologies not only as storage devices, but also as active components for computation, acceleration, and reliability-aware system design.

### Processing-in-Memory for AI Acceleration

AI workloads require high memory bandwidth and frequent data movement. Processing-in-memory architectures can reduce this overhead by embedding computation closer to stored data.

My work investigates how FeRAM/FeFET-based memory arrays can support efficient multiply-accumulate operations, multi-level storage, and low-energy inference.

### Device-to-System Co-Design

A major challenge in emerging memory research is connecting device-level behavior to system-level impact. I work across this full stack by combining:

```text
TCAD simulation
↓
Compact modeling
↓
SPICE-level circuit evaluation
↓
Memory-array analysis
↓
Architecture-level performance modeling
↓
Application-level workload evaluation
```

This approach helps identify design trade-offs that are not visible when devices, circuits, and systems are studied in isolation.

---

## Current Academic Profile

- **Ph.D. Student**, Computer Science and Engineering, Penn State University
- **M.S. Student**, Computer Science and Engineering, Penn State University
- **Graduate Research Assistant**, Microsystems Design Lab
- **B.Sc.**, Electrical and Electronic Engineering, BUET
- **Research areas:** emerging memory, VLSI, computer architecture, ML acceleration, memory reliability

---

## Recognition

🏆 **Best Poster Presentation Award**  
CERS 2026, Electronics, Photonics & Semiconductor Systems

🎓 **Vice Provost and Dean of the Graduate School Student Persistence Scholarship**  
Penn State, 2025

🤖 **2nd Runner-up**  
National Robotics Festival, 2017

---

## GitHub Stats

<div align="center">

![Sadik's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Tauki01&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Tauki01&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Connect With Me

I am interested in research collaborations and internship opportunities in:

- Emerging memory systems
- VLSI and ASIC design
- Processing-in-memory architectures
- ML hardware acceleration
- Computer architecture and memory systems
- Device–circuit–architecture co-design

<div align="center">

[![Email](https://img.shields.io/badge/Email-mpt5708@psu.edu-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mpt5708@psu.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sadik%20Yasir%20Tauki-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sadikyasir/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Site-000000?style=flat&logo=githubpages&logoColor=white)](https://sites.google.com/view/tauki/home)

</div>

---

<div align="center">

*Building memory-centric computing systems across devices, circuits, architecture, and ML workloads.*

![Profile Views](https://komarev.com/ghpvc/?username=Tauki01&color=blueviolet&style=flat)

</div>
