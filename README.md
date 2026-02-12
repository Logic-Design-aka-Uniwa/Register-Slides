<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Logic Design</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Registers Sliders
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, May 2021
</p>

---

# Project Overview

This project explores the **design, simulation, and theoretical analysis** of various **shift registers and sliders** using the **Multisim simulator**. It was developed as part of a **Digital Design workshop** at the **University of West Attica**.

The core focus is on understanding **information transfer and storage** through logic circuits, specifically using **D flip-flops** and integrated circuits such as the **74LS194**.

---

## Table of Contents

| Section | Folder/File | Description |
|------:|-------------|-------------|
| 1 | `assign/` | Assignment material for the Registers and Sliders workshop |
| 1.1 | `assign/ASSIGNMENT 4.pdf` | Assignment description in English |
| 1.2 | `assign/ΕΡΓΑΣΙΑ 4.pdf` | Assignment description in Greek |
| 2 | `docs/` | Documentation covering registers and sliders theory |
| 2.1 | `docs/Registers-Sliders.pdf` | English documentation for registers and sliders |
| 2.2 | `docs/Καταχωρητές-Ολισθητές.pdf` | Greek documentation for registers and sliders |
| 3 | `multisim/` | Multisim register and slider simulation files |
| 3.1 | `multisim/8-bit-Register.ms14` | 8-bit register simulation |
| 3.2 | `multisim/generalSlider.ms14` | General slider simulation |
| 4 | `README.md` | Repository overview and usage instructions |

---

## Core Components and Tools

- **Software:** NI Multisim (for circuit design and simulation)  
- **Key Hardware (Simulated):**
  - **74LS194N:** 4-bit bidirectional universal shift register  
  - Logic Gates: AND, OR, NOR, NAND, XOR, XNOR, NOT  
  - Input/Output: VCC sources (5V), Ground, lamps as indicators, interactive switches (Spacebar for CLOCK, 'C' for CLEAR)  
- **Measurement Tools:** Oscilloscope for signal analysis  

---

## Key Exercises Implemented

### 1. General Purpose Shift Register (74LS194)

Analysis of the **74LS194** integrated circuit across multiple states:

- **Initial State:** Set via parallel inputs  
- **Clock Pulse Behavior:** Step-by-step observation of data movement after each clock pulse  
- **Operational Modes:**
  - **SIPO:** Serial Input, Parallel Output  
  - **PISO:** Parallel Input, Serial Output  
- **Shift Directions:** Both right and left shift operations implemented  

---

### 2. Eight-Bit Register and Information Transfer

This exercise demonstrates **data transfer between two 4-bit registers** to form an **8-bit storage system**, illustrating how smaller register units can be cascaded to handle larger bit-widths in digital computing.

---

## Document Structure

| Chapter | Title | Description |
|---------|-------|-------------|
| 1 | A Few Words About Work | Introduction to registers and shift operations |
| 2 | Bibliography | Reference to *Design and Implementation of Logic Circuits* |
| 3 | Work Implementation | Detailed list of Multisim components used |
| 4 | Exercises | Theoretical results and circuit screenshots for the 74LS194 and 8-bit transfer |

---

## How to Use This Analysis

To replicate the results:

1. Set up the **74LS194N** in **Multisim** as shown in the schematics (Pages 6–10).  
2. Use the designated **Key assignments**:
   - **Spacebar:** Clock pulse  
   - **C key:** Clear input  
3. Observe the **shift patterns** on the output lamps (**QA through QD**) to visualize data movement.

> This approach allows interactive simulation of **serial-parallel and parallel-serial transfers**, reinforcing understanding of **shift registers** and **bitwise data manipulation** in digital systems.

---

# Installation & Setup Guide

This repository contains **Workshop 4 – Registers and Sliders** simulations and documentation for the **Digital Design** course at the **University of West Attica**. The focus is on **shift registers, sliders, and information transfer using D flip-flops and integrated circuits**.

All simulations are implemented using **NI Multisim**.

---

## Prerequisites

### Required Software
- **NI Multisim 14** or later  
  Required to open and run `.ms14` simulation files.

Download:  
https://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/what-is-multisim.html

---

### Optional Software
- **PDF Viewer** to read documentation files (`Registers-Sliders.pdf`, `Καταχωρητές-Ολισθητές.pdf`)  
- **Git** for cloning the repository

---

## Installation Steps

### 1. Clone the Repository

Clone using Git:

```bash
git clone https://github.com/Logic-Design-aka-Uniwa/Register-Slides.git
```

Or download the project as a ZIP file and extract it manually.

### 2. Navigate to Project Directory
```bash
cd Register-Slides
```
Ensure the following folder structure exists:
```bash
assign/
docs/
multisim/
README.md
```

--- 

## Multisim Simulation Files
The repository includes simulation files for the main arithmetic circuits:

| File | Description |
|------|-------------|
| `multisim/8-bit-Register.ms14` |	8-bit register simulation |
| `multisim/generalSlider.ms14` |	General slider/shift register simulation |

These circuits cover sequential behavior, memory storage, and clocked operation.

### 3. Open a Simulation in Multisim
1. Launch **NI Multisim**.
2. Select **File** → **Open**.
3. Navigate to the repository folder.
4. Open the `multisim/` directory.
5. Select a `.ms14` file.
6. Wait for the circuit to load.
7. Run the simulation using the Run button.

---

## Open the Documentation
1. Navigate to the `docs/` folder.
2. Open the preferred documentation:

| Language | File |
|----------|------|
| English | `docs/Register-Sliders.pdf` |
| Greek | `docs/Καταχωρητές-Ολισθητές.pdf` |

The documentation includes:
- Shift register theory and operation modes (SIPO, PISO)
- Cascading of registers for 8-bit transfer
- D Flip-Flop and 74LS194 IC usage
- Circuit screenshots and simulation results