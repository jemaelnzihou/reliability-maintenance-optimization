# reliability-maintenance-optimization
Reliability Analysis of Industrial Components Using Weibull Modeling &amp; Survival Analysis

reliability-maintenance-optimization/
│
├── data/
│   └── EXA1.csv                       # Real or simulated dataset
│
├── notebooks/
│   ├── eda_reliability.ipynb          # EDA + Kaplan-Meier
│   ├── weibull_modeling.ipynb         # Parametric modeling (stratified)
│   └── cost_optimization.ipynb        # Cost-based maintenance strategy
│
├── reports/
│   └── summary_decision_logic.pdf     # Optional PDF summary for stakeholders
│
├── requirements.txt                   # Python dependencies
└── README.md                          # Project description & usage guide

# 🔧 Reliability Maintenance Optimization with Weibull Modeling

This project applies data science techniques to analyze component reliability and optimize maintenance scheduling using both survival analysis and cost simulations.

---

## 📌 Objectives

- Perform Exploratory Data Analysis (EDA) on time-to-failure data
- Fit Weibull models (including stratified by batch or group)
- Visualize Kaplan-Meier survival curves
- Calculate reliability and hazard functions
- Estimate MTTF (Mean Time To Failure)
- Optimize maintenance scheduling based on cost vs. reliability

---

## 📊 Dataset

A sample dataset (`EXA1.csv`) contains:
- `Time`: Time to failure or censoring
- `Event`: 1 = failure, 0 = censored
- `Group`: Component batch (optional for stratification)

---

## 🧠 Notebooks Overview

| Notebook | Purpose |
|----------|---------|
| `eda_reliability.ipynb` | Exploratory Data Analysis, survival curves |
| `weibull_modeling.ipynb` | Parametric Weibull fitting, stratified models |
| `cost_optimization.ipynb` | Simulate expected costs, recommend preventive time |

---

## 📈 Sample Output

- **Kaplan-Meier Survival Curve**
- **Weibull Reliability & Hazard Functions**
- **Optimal Replacement Time Recommendation**

---

## 💰 Business Impact

- Reduce unplanned failures
- Improve spare part logistics
- Optimize cost per hour of operation
- Bridge engineering & business through data science

---

## 📦 Installation

```bash
pip install -r requirements.txt

---
📤 Author
Jemael Nzihou
Veteran | Data Scientist | Reliability Optimization
📧 Contact
🌐 Portfolio
