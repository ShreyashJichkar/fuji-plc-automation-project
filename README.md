# ⚡ Fuji PLC Programming Project – Part 1

<p align="center">
  <img src="https://img.shields.io/badge/PLC-Fuji-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Language-Ladder%20Logic-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tool-SX--Programmer-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Level-Beginner--Intermediate-yellow?style=for-the-badge"/>
</p>

---

## 📌 Project Overview
This project demonstrates **industrial PLC programming fundamentals** using Fuji Electric SX-Programmer.  
It includes ladder logic design, timer-based control, data handling, and an interactive HMI simulation panel.

---

## 🎯 Key Features

✅ Timer (TON) – 20 seconds delay  
✅ MOVE Instruction (Data Transfer)  
✅ Compare Instruction (=)  
✅ Data Register Handling (DM2, DM4)  
✅ Output Control (Y2.1)  
✅ HMI / Simulation Panel Design  

---

## 🧠 Working Principle

```text
Start (X1.1) → Timer T0 (20 sec) → Output Y2.1 ON
                ↓
          Value stored in DM2
                ↓
          Processed → DM4
                ↓
        If DM4 == 20 → Condition TRUE
