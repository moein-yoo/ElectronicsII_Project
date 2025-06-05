# 🔌 Electronics II – Differential Amplifier Project (Phase 1)

📚 **Course**: Electronics II  
🏫 **University**: Sharif University of Technology  
👨‍🏫 **Instructors**: Dr. Fakharezadeh, Dr. Sarvari, Dr. Medi, Dr. Besharat Rad  
👨‍💻 **Author**: Moein Yousefinia  
📧 **Contact**: moein.yoo84@sharif.edu | moein.yoo@outlook.com  
🕒 **Semester**: Spring 2025  

---

## 📁 Repository Structure

- `Part1/`: Initial design of the differential amplifier with resistive load  
- `Part2/`: Amplifier using active MOSFET load  
- `Part3/`: Differential amplifier biased using current mirror  
- `Part4/`: Fully optimized circuit with improved swing and gain  
- Each folder contains a `Fig/` subdirectory with simulation results and plots

---

## 🧪 Project Overview

This project presents a four-phase design and analysis of a MOSFET-based differential amplifier. Each phase introduces a new level of complexity and improvement to key performance metrics such as differential gain, common-mode rejection, power consumption, and output swing. Both theoretical derivations and SPICE simulations are used to evaluate performance.

---

## 🧩 Phase Descriptions

### 🧱 Part 1: Initial Design (Resistive Load)
- Design of a basic differential pair with passive RD resistors
- Hand calculations for gain, input/output resistance, and power
- Common-mode and differential-mode simulation
- Limitations in output swing due to large RD

### ⚙️ Part 2: Active Load
- Replacing RD with PMOS current sources for improved gain
- Gate bias voltage derivation for active load transistors
- Simulation-based verification of gain, swing, and input/output resistance
- Increased differential gain and improved CMRR

### 🔄 Part 3: Current Mirror Biasing
- Replacing ideal bias sources with NMOS current mirrors
- Accurate W/L selection for current source transistors
- Higher differential gain observed
- Full theoretical analysis and simulation confirmation

### 🔧 Part 4: Circuit Optimization
- Fully transistor-based biasing and loading
- Rx resistance calculated to ensure stable 1mA current
- Final gain analysis for single-ended and differential output
- Insight into why single-ended gain remains limited
- Proposed solution: source degeneration in M7 to boost performance

---

## 🖥️ Simulations

All simulation results are organized within each `PartX/Fig/` directory.  
Each part includes:
- DC sweep results  
- Common-mode vs differential-mode gain figures  
- Output swing verification  
- Input/output resistance simulations  

---

## 📊 Summary Table

| Metric               | Part 1 | Part 2 | Part 3 | Part 4 |
|----------------------|--------|--------|--------|--------|
| Differential Gain    | ~14.8  | ~40    | 100    | 100    |
| Common-Mode Gain     | -0.015 | N/A    | N/A    | -0.995 |
| Power Consumption    | 2 mW   | 2 mW   | 3 mW   | 4 mW   |
| Input Resistance     | ∞      | ∞      | ∞      | ∞      |
| Output Resistance    | ~6kΩ   | ~40kΩ  | ~40kΩ  | ~40kΩ  |

---

## ✅ Key Features

- Precise hand calculations and MOSFET modeling
- SPICE simulation consistency and documentation
- Trade-off analysis between power, complexity, and gain
- Educational step-by-step design improvement

---

## 📂 License

This project is for educational purposes only.

---
