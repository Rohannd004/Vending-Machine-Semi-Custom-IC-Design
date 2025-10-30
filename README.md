# 🍫 Vending Machine – Semi-Custom IC Design (RTL → GDSII)

This repository contains the complete implementation of a **Vending Machine ASIC** designed using a **Semi-Custom VLSI Design flow**.  
The project covers the entire chip design cycle — from **RTL coding** to **GDSII generation**.

---

## 🎯 Objective

Design a **chocolate vending machine controller** that accepts ₹5 and ₹10 coins:  
- ₹10 or two ₹5 coins → ✅ Dispense chocolate  
- ≥ ₹20 inserted → ✅ Dispense + return ₹5 change

Target: Implement using **industry-standard VLSI flow**.

---

## 🧠 Features

| Category | Details |
|---|---|
RTL | Verilog FSM-based vending machine logic  
Verification | SystemVerilog testbench + waveform validation  
Synthesis | Cadence Genus (timing-driven)  
Physical Design | Cadence Innovus (floorplan → routing)  
Sign-off | DRC & LVS clean checks  
Output | Final **GDSII** and layout screenshots  

---

## 📂 Directory Structure

