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

Dependencies include:
- pandas
- numpy
- matplotlib
- lifelines
- scipy

## 📤 Author
Jemael Nzihou  
Veteran | Data Scientist | Reliability Optimization  
📧 [Contact](mailto:jemaelnzihou@gmail.com)  
🌐 [Portfolio](https://jemaelnzihou.github.io/Portfolio)
