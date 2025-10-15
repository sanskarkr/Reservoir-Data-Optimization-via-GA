# 💧 Optimization of Hirakud Dam Operation using Genetic Algorithm  

**Course:** CE718 – Water Resources Systems Engineering  
**Group 10 | April 2025**  

**Team Members:**  
Madhav Khetan · Ansh Jain · Sanskar Kumar · Dnyaneshwar Pawar · Aadi Singh · Saurabh  

---

## 🧠 Project Overview  
This project optimizes **Hirakud Dam** operations on the **Mahanadi River (Odisha)** using a **Genetic Algorithm (GA)**.  
The model minimizes **flood-prone releases**, **unmet downstream demand**, and **spill losses** over **2022–2024**, ensuring safe and efficient water management.  

---

## ⚙️ Methodology  
- **Tool:** Python (`PyGAD`, `Pandas`, `Matplotlib`)  
- **Objective:**  
  \[
  \text{Minimize } (Flood\ Penalty + Unmet\ Demand + Spill\ Loss)
  \]
- **Constraints:**  
  - Max storage: 4637 MCM  
  - Safe release: 140 MCM/day  
  - Seasonal demand: 35–50–65 MCM/day  
- **Penalty Ratio:** 1:500 (Unmet demand = 4, Flood = 2000)  

---

## 📊 Key Results  
| Metric | Value |
|---------|-------|
| Flood-Prone Days | **51** |
| Total Unmet Demand | **9634.84 MCM** |
| Avg Storage | **247.38 MCM** |
| Spill Loss | **0.00 MCM** |
| Demand Met | **~84%** |

✅ Balanced operation achieved — safe, sustainable, and demand-efficient.  

---
