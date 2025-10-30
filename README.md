# 📟 Vending Machine — Semi-Custom IC Design (Cadence Flow)

## 🎯 Objective  
Design and implement a **chocolate vending machine FSM** using **Verilog RTL** and complete an **industry-standard VLSI flow** using Cadence EDA tools.

---

## ✅ Functional Specification

| Coins Inserted | Output |
|----------------|--------|
| ₹10 (or two ₹5 coins) | ✅ Dispense chocolate |
| ≥ ₹20 | ✅ Dispense chocolate + ✅ return ₹5 change |

---

## 🧠 Features

| Category | Details |
|--------|--------|
| RTL | Verilog FSM-based vending machine logic |
| Verification | SystemVerilog testbench + waveform validation |
| Synthesis | Cadence Genus (timing-driven) |
| Physical Design | Cadence Innovus (floorplan → routing) |
| Sign-off | DRC & LVS clean checks |
| Output | Final GDSII + layout screenshots |

---

##Final

---

## 🧩 RTL Design (FSM Logic)

State machine uses four states:

| State | Description |
|---|---|
IDLE | No coins inserted  
FIVE | ₹5 inserted  
TEN | ₹10 inserted  
DISPENSE | Dispense chocolate + optional change  

---

## 💻 Tools Used

| Stage | Tool |
|---|---|
RTL Simulation | Xcelium / Icarus Verilog  
Synthesis | Cadence Genus  
Floorplan → GDS | Cadence Innovus  
Sign-Off Check | DRC / LVS / Timing Closure  

---

## 🖼️ Layout & GDS Results

### 📌 Power Planning View
> (Screenshot below is from Cadence Innovus)

*(<img width="868" height="1156" alt="image" src="https://github.com/user-attachments/assets/31462827-cdf1-4d71-be5c-5a4b4bb18f14" />

)*


### 📌 Floorplan or Placement View
> (Screenshot below is from Cadence Innovus)

*(<img width="868" height="1156" alt="image" src="https://github.com/user-attachments/assets/9ba42e3c-9bff-4c33-929f-50bc29ff0bb7" />
)*

### 📌 Final Innovus Layout (Routed)
> (Screenshot below is from Cadence Innovus)

*(![WhatsApp Image 2025-10-30 at 10 46 02 AM](https://github.com/user-attachments/assets/b827a474-44b0-42e3-b174-e17576d2f5c9)
)*

### 📌 Generated GDS File
> Successfully exported **GDSII**, verified in viewer

*(![WhatsApp Image 2025-10-30 at 10 46 02 AM (1)](https://github.com/user-attachments/assets/bf9e223e-2f96-4b76-8d4e-cccd5d1fe72d)
)*

---

## ✅ Results Summary

| Metric | Status |
|---|---|
Functional verification | ✅ Passed  
Synthesis | ✅ Timing met  
Placement & Routing | ✅ Completed  
DRC | ✅ Clean  
LVS | ✅ Matched  
Final Output | ✅ `chip.gds` Generated  

---

## 👨‍💻 Author

**Rohan N D**  
Electronics & Communication | VLSI Enthusiast  
Focus: **RTL → Physical Design → ASIC Implementation**

---

## ⭐ Notes

This project demonstrates a **complete Semi-Custom ASIC flow** for a digital FSM-based design.  
Suitable for **VLSI internship & job portfolios** (PD / RTL / Verification).

If you find this project useful, ⭐ the repository 😊



