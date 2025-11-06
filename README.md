# Microstrip Patch Antenna Design using HFSS

This repository contains the design, simulation, and analysis of a **Rectangular Microstrip Patch Antenna (MPA)** using **ANSYS HFSS**. The project demonstrates how to calculate antenna dimensions from theoretical formulas, model the antenna in HFSS, and analyze key antenna performance parameters.

---

## 📡 Project Overview

Microstrip Patch Antennas are widely used in **wireless and satellite communication systems** due to their:
- Low profile and lightweight structure  
- Ease of fabrication  
- Compatibility with microwave integrated circuits  

However, they typically have **narrow bandwidth** and **lower efficiency**, making careful design and simulation essential.

---

## 🧮 Design Inputs

| Parameter | Value / Description |
|---------|---------------------|
| Substrate | Rogers RT/duroid 5880 (example) |
| Dielectric Constant (εr) | 2.2 |
| Substrate Height (h) | 1.6 mm |
| Operating Frequency | 2.4 GHz / 5.9 GHz (examples) |
| Copper Thickness | 0.017–0.035 mm |

---

## 🛠️ Steps Performed

1. **Calculate patch dimensions** (Length & Width) using the Transmission Line Model  
2. Compute **effective dielectric constant** and **length extension**  
3. **Model the antenna geometry** in HFSS  
4. Assign **materials, radiation boundaries, and feed**  
5. Apply **wave port excitation**  
6. **Run EM simulation**  
7. Extract key performance results  

---

## 📈 Output Parameters Analyzed

- **S11 (Return Loss)**
- **VSWR**
- **2D / 3D Radiation Patterns**
- **Gain & Directivity**
- **Axial Ratio**
- **Far-field Coverage**


