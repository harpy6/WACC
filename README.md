# WACC
Weighted Average Cost of Capital (WACC) analysis and valuation framework for evaluating a company’s cost of capital, capital structure, and investment decisions.

# SJ Corp – WACC Valuation Analysis

## 📌 Project Overview

This project estimates the **Weighted Average Cost of Capital (WACC)** for **SJ Corp**, a listed Indian company operating in the **Gems, Jewellery & Watches sector**.

The analysis uses a **Comparable Company / Peer Group approach** because SJ Corp has a relatively small market capitalization and limited trading history, making its company-specific beta less statistically reliable.

The estimated WACC is used as a potential **discount rate for DCF valuation, investment appraisal, and capital budgeting decisions**.

---

## 🎯 Objectives

* Estimate SJ Corp's Weighted Average Cost of Capital.
* Identify an appropriate business-risk beta using comparable companies.
* Unlever peer-company betas to remove capital-structure effects.
* Calculate the median unlevered beta.
* Re-lever the beta using SJ Corp's target capital structure.
* Calculate the Cost of Equity using CAPM.
* Calculate the After-Tax Cost of Debt.
* Determine the final WACC.
* Provide a suitable discount rate for valuation purposes.

---

## 🏢 Company Information

**Company:** SJ Corp
**Sector:** Gems, Jewellery & Watches
**Country:** India
**Market Price:** ₹71.47 per share
**Market Capitalization:** ₹59.71 Crore
**Current Debt:** ₹0 Crore

SJ Corp currently has an **all-equity capital structure**, with no outstanding debt.

---

## 📊 Peer Companies

The following listed Indian companies were selected as comparable companies:

1. Narbada Gems
2. Moksh Ornaments
3. Mishka Exim
4. Bhakti Gems

These companies were selected from the same broad industry to estimate SJ Corp's underlying business-risk beta.

---

## 🔬 Methodology

The analysis follows these major steps:

### 1. Peer Selection

Comparable companies from the Gems, Jewellery & Watches sector were selected.

### 2. Beta Unlevering

The levered beta of each peer was converted into an unlevered beta:

**Unlevered Beta = Levered Beta ÷ [1 + (1 − Tax Rate) × Debt/Equity]**

### 3. Sector Beta

The average and median unlevered betas were calculated.

The **median unlevered beta** was selected because it is less affected by extreme values or outliers.

### 4. Beta Re-levering

The median unlevered beta was re-levered using SJ Corp's target Debt/Equity ratio:

**Levered Beta = Unlevered Beta × [1 + (1 − Tax Rate) × Target Debt/Equity]**

### 5. Cost of Equity

The Capital Asset Pricing Model (CAPM) was used:

**Cost of Equity = Risk-Free Rate + (Beta × Equity Risk Premium)**

### 6. After-Tax Cost of Debt

**After-Tax Cost of Debt = Pre-Tax Cost of Debt × (1 − Tax Rate)**

### 7. WACC

**WACC = (Cost of Equity × Equity Weight) + (After-Tax Cost of Debt × Debt Weight)**

The report uses a **30% corporate tax rate** and 5-year monthly return data for beta inputs.

---

## 📈 Key Results

| Component              |    Result |
| ---------------------- | --------: |
| Risk-Free Rate         |     6.70% |
| Equity Risk Premium    |     7.64% |
| Median Unlevered Beta  |      0.30 |
| Target Debt/Equity     |     2.08% |
| Re-levered Beta        |      0.30 |
| Cost of Equity         |     8.99% |
| Pre-Tax Cost of Debt   |     0.00% |
| After-Tax Cost of Debt |     0.00% |
| Final WACC             | **8.99%** |

The peer median unlevered beta is **0.29** in the detailed peer table, while the CAPM section reports the rounded value as **0.30**.

---

## 💰 Capital Structure

### Current Capital Structure

* Debt: **₹0.00 Crore**
* Equity: **₹59.71 Crore**
* Debt Weight: **0%**
* Equity Weight: **100%**

Because SJ Corp currently has no debt, its WACC is effectively equal to its Cost of Equity.

---

## ⭐ Final WACC

### **SJ Corp WACC = 8.99%**

The report recommends **8.99% as the discount rate** for DCF valuation and capital budgeting decisions, subject to periodic review as market conditions, risk premiums, and the company's capital structure change.

---

## 🧮 Financial Concepts Used

This project demonstrates practical application of:

* Weighted Average Cost of Capital (WACC)
* Capital Asset Pricing Model (CAPM)
* Levered Beta
* Unlevered Beta
* Debt-to-Equity Ratio
* Debt-to-Capital Ratio
* Cost of Equity
* Cost of Debt
* Capital Structure
* Equity Risk Premium
* Risk-Free Rate
* Comparable Company Analysis
* DCF Valuation
* Investment Appraisal

---

## 🛠️ Tools & Skills

**Financial Analysis**

* WACC Calculation
* CAPM
* Beta Analysis
* Comparable Company Analysis
* Capital Structure Analysis

**Tools**

* Microsoft Excel
* Financial Modelling
* Data Analysis

---

## 📁 Project Structure

```text
SJ-Corp-WACC/
│
├── README.md
├── SJ_Corp_WACC_Report.pdf
├── WACC_Analysis.xlsx
└── charts/
    └── WACC_Analysis.png
```

> Update the filenames above according to the actual files uploaded to this repository.

---

## 📌 Conclusion

The comparable-company approach produces an estimated **WACC of 8.99% for SJ Corp**.

The result is primarily driven by:

* Risk-Free Rate: **6.70%**
* Equity Risk Premium: **7.64%**
* Peer Median Unlevered Beta: approximately **0.30**
* Current Debt: **₹0 Crore**
* Cost of Debt: **0%**

Therefore, **8.99%** can be used as the indicative discount rate for SJ Corp's DCF valuation and capital budgeting analysis, with periodic updates recommended as market and company conditions change.

---

## 👨‍💻 Project Type

**Financial Modelling | Valuation | Corporate Finance | WACC Analysis**

**Prepared:** September 2026
