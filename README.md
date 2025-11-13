# 📊 Three-Statement Financial Model (Excel)

### 🏢 Project: Aurora Electronics Inc.

A dynamic **three-statement financial model** built in Microsoft Excel that projects **Income Statement, Balance Sheet, and Cash Flow Statement** for a hypothetical mid-size electronics firm over a 5-year horizon (2024–2028).  
The model links all statements automatically and allows scenario toggling between **Base**, **Best**, and **Worst** cases.

---

## 🚀 Project Overview
This project demonstrates the construction of a **fully integrated financial model** commonly used in FP&A, investment analysis, and corporate forecasting.

### Key Objectives
- Build a transparent, auditable Excel model with linked financial statements  
- Implement a **Scenario Selector** to test assumptions dynamically  
- Automate key financial ratios and KPI dashboards  
- Visualize trends in revenue, profit, and cash flow  

---

## 🧾 Model Structure

| Sheet Name | Description |
|-------------|--------------|
| **Assumptions** | Centralized input tab controlling revenue growth, margins, CapEx, and working capital assumptions with Base/Best/Worst case switch |
| **Income Statement** | Calculates revenue, costs, EBITDA, and net income for 2024–2028 |
| **Balance Sheet** | Tracks assets, liabilities, and equity, all linked to the Income Statement and Cash Flow |
| **Cash Flow Statement** | Indirect cash flow derived from net income, working capital, CapEx, and financing activities |
| **Ratios & Dashboard** | Displays KPIs (EBITDA margin, ROE, FCF) and visual charts across scenarios |

---

## ⚙️ Key Features

✅ **Dynamic Scenario Selector**  
Use a dropdown to toggle between Base, Best, and Worst cases.  
```excel
=CHOOSE(MATCH($B$6,{"Base","Best","Worst"},0),C10,D10,E10)
