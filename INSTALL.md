<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
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

<hr>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Konstantinos Efstathiou, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/konstantinos-efstathiou/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Academic Scholar
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/academic_sc_ho/" target="_blank">UNIWA Profile</a> ·
  <a href="https://scholar.google.com/citations?user=-LnaZGgAAAAJ&hl=en" target="_blank">Scholar</a>
</p>

<p align="center">
  Co-supervisor: Anastasios Tsilikounas, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/anastasios-tsilikounas/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/anastasios-tsilikounas-31111566/" target="_blank">LinkedIn</a>
</p>

</hr>

---

<p align="center">
  Athens, May 2021
</p>

---

<p align="center">
  <img src="https://media.geeksforgeeks.org/wp-content/uploads/FlipFlop1.png" width="250"/>
</p>

---

# INSTALL

## Registers Sliders

This repository contains **Workshop 4 – Registers and Sliders** simulations and documentation for the **Digital Design** course at the **University of West Attica**. The focus is on **shift registers, sliders, and information transfer using D flip-flops and integrated circuits**.

All simulations are implemented using **NI Multisim**.

---

## 1. Prerequisites

### 1.1 Required Software

- **NI Multisim 14** or later  
  Required to open and run `.ms14` simulation files.

Download:  
https://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/what-is-multisim.html

---

## 2. Optional Software

- **PDF Viewer** to read documentation files (`Registers-Sliders.pdf`, `Καταχωρητές-Ολισθητές.pdf`)
- **Git** for cloning the repository

---

## 3. Installation Steps

### 3.1 Clone the Repository

Clone using Git:

```bash
git clone https://github.com/Logic-Design-aka-Uniwa/Register-Slides.git
```

Or download the project as a ZIP file and extract it manually.

### 3.2 Navigate to Project Directory

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

## 4. Multisim Simulation Files

The repository includes simulation files for the main arithmetic circuits:

| File                           | Description                              |
| ------------------------------ | ---------------------------------------- |
| `multisim/8-bit-Register.ms14` | 8-bit register simulation                |
| `multisim/generalSlider.ms14`  | General slider/shift register simulation |

These circuits cover sequential behavior, memory storage, and clocked operation.

### 4.1 Open a Simulation in Multisim

1. Launch **NI Multisim**.
2. Select **File** → **Open**.
3. Navigate to the repository folder.
4. Open the `multisim/` directory.
5. Select a `.ms14` file.
6. Wait for the circuit to load.
7. Run the simulation using the Run button.

---

## 5. Open the Documentation

1. Navigate to the `docs/` folder.
2. Open the preferred documentation:

| Language | File                             |
| -------- | -------------------------------- |
| English  | `docs/Register-Sliders.pdf`      |
| Greek    | `docs/Καταχωρητές-Ολισθητές.pdf` |

The documentation includes:

- Shift register theory and operation modes (SIPO, PISO)
- Cascading of registers for 8-bit transfer
- D Flip-Flop and 74LS194 IC usage
- Circuit screenshots and simulation results
