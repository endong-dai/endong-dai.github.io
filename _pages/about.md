---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am **Endong Dai**, a Master's student in **Electrical and Computer Engineering (Hardware Track)** at **Duke University**. I focus on **digital hardware design, RTL architecture, and AI accelerator systems**. My goal is to build efficient hardware architectures that bridge **algorithm, digital logic, and system-level integration**. My experience includes **Verilog RTL design, FPGA systems, embedded development, and circuit simulation**, with projects ranging from **AI chip architecture modules to floating-point ALU design and power electronics systems**. You can find more information through my [CV](docs/CV.pdf).

I am currently interested in:

- ASIC RTL Design  
- Hardware Accelerators for AI  
- FPGA RTL Design  

---

# 🎓 Education

**Duke University** — Durham, NC  
M.S. Electrical and Computer Engineering (Hardware Track)  
Aug 2025 – Present  

**University of Nottingham** (China + UK 2+2 Program)  
B.Eng. Electrical and Electronic Engineering — **First Class Honours**  
Sep 2021 – Jul 2025  

Awards  
- Dean’s Scholarship  

---

# 🔧 Hardware Skills

### RTL / Digital Design
- Verilog
- FPGA Development (Quartus, Vivado)
- Digital IC Architecture
- Finite State Machine Design
- AXI Interface

### Circuit & Hardware Tools
- Cadence Virtuoso
- LTspice
- PLECS
- MATLAB / Simulink
- KiCad PCB Design

### Embedded Systems
- C / C++
- PIC16 Assembly
- STM32
- Arduino
- Raspberry Pi

### Platforms
- Linux (Ubuntu)
- ROS
- Git

---

# 💻 Selected Projects

---

## Diffusion AI Chip – Gather/Scatter Unit (SGU)

**Duke University**  
Sep 2025 – Jan 2026  

Designed a Gather/Scatter Unit for irregular memory access in diffusion AI accelerators.

Key features:

- 4-stage pipelined FSM architecture
- AXI streaming interface with ready/valid handshake
- Supports both gather and scatter dataflow
- Designed in Verilog RTL

### Gather / Scatter Dataflow

<img src="images/sgu_dataflow.png" width="85%">

This diagram illustrates how the SGU performs gather and scatter operations using a spatial index list.

### SGU Hardware Architecture

<img src="images/sgu_pipeline.png" width="80%">

The SGU is implemented as a 4-stage pipeline:

- **S0**: Index fetch
- **S1**: PISO conversion
- **S2**: Source memory read
- **S3**: Destination write

---

## IEEE-754 Half Precision Floating-Point ALU

**Duke University**  
Sep 2025 – Dec 2025  

Designed a **16-bit floating-point ALU** supporting:

- Addition  
- Subtraction  
- Multiplication  
- Division  

Key design features:

- 12×12-bit array multiplier
- Restoring divider architecture
- Exception detection and rounding
- Normalization datapath and control logic

Estimated performance (TSMC 65 nm):

- ~1 GHz frequency  
- <1 ns delay  
- ~0.05–0.08 mm² area  

---

## Omni-Directional Robot Collision Awareness

**University of Nottingham Ningbo China**  
Jun 2024 – Aug 2024  

Implemented robot navigation system using **ROS and LiDAR SLAM**.

- Configured **ROS Noetic + Gazebo + RViz**
- Deployed **Cartographer SLAM**
- Integrated **RoboRTS navigation stack**

---

## Two-Switch Forward DC/DC Converter

**University of Nottingham**  
Feb 2024 – Apr 2024  

Designed a **two-switch forward converter** power supply system.

- Circuit simulation in **PLECS**
- PCB design using **KiCad**
- Control verification with **MATLAB**

---

## Heart Rate & Pulse Oximeter System

**University of Nottingham**  
Oct 2023 – Dec 2023  

Embedded biomedical device using **STM32**.

- Designed analog front-end circuits
- Implemented **FFT-based heart rate detection**
- Developed ADC firmware for signal processing

---

# 📬 Contact

Email  
ed253@duke.edu  
daiendong81@gmail.com  

GitHub  
https://github.com/endong-dai  

LinkedIn  
https://www.linkedin.com/in/endong-dai-607052385
