# 💧 Liquidity Risk Stress Simulation – LCR & NSFR Analysis

🚨 Stress-testing a bank’s liquidity using Basel III standards – all in Python 🐍

---

## 📘 Overview

This project simulates a **medium-sized bank's liquidity risk exposure** using:
- **Liquidity Coverage Ratio (LCR)** – Short-term shock survival (30 days)
- **Net Stable Funding Ratio (NSFR)** – Long-term funding stability

We apply multiple stress scenarios using a mock balance sheet and visualize the impact using Plotly.

---

## 📊 Key Features

✅ Self-generated **bank balance sheet** dataset  
✅ **6 stress scenarios**: deposit run, bond haircut, loan delay, OBS drawdown, combined shock  
✅ Dynamic calculation of **LCR & NSFR**  
✅ Interactive **Plotly bar chart** for visual comparison  
✅ Risk insights & recommendations included  

---

## 📁 Dataset

> **Note**: This is a **self-generated mock dataset** created for educational and demonstration purposes only.  
> It does not represent real institutions or financial data.

File: `bank_balance_sheet.csv`

---

## 💥 Stress Scenarios Modeled

1. **Base Case**
2. **Deposit Run (30%)**
3. **Bond Haircut (20%)**
4. **Credit Line Drawdown (30%)**
5. **Loan Repayment Delays (20%)**
6. **Combined Stress Scenario**

---

## 🔍 Key Findings

- 📈 **Base LCR**: 300% (Very strong)
- 🧯 **Combined Stress LCR**: Drops to ~195%
- 🚨 **NSFR**: 48.39% (Below Basel III threshold of 100%)
- 💡 Even well-capitalized banks can become fragile under multiple stress conditions

---
