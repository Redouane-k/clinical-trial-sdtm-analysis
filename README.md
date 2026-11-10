# Clinical Trial SDTM Data Analysis (Python)

## 📌 Project Overview
This repository contains a complete statistical analysis pipeline developed in Python for a randomized clinical trial. The data processing and structuring strictly follow the **CDISC SDTM** (Study Data Tabulation Model) standards, reflecting regulatory and pharmaceutical industry requirements.

## 🎯 Objectives & Key Deliverables
The project implements key components required for regulatory submission and clinical reporting:
1. **Patient Flow Chart:** Calculation and tracking of patient populations through study milestones.
2. **Table 1 (Baseline Characteristics):** Descriptive statistics of the study population stratified by treatment arm (demographics, vital signs, medical history, and clinical parameters).
3. **Statistical Analysis & Endpoints:** Evaluation of the primary endpoint and safety/efficacy analysis.
4. **Data Visualization:** Publication-ready figures illustrating temporal trends and key clinical outcomes.

## 🗂️ SDTM Domains Used
* **DM:** Demographics
* **VS:** Vital Signs
* **LB:** Laboratory Test Results
* **AE:** Adverse Events
* **EX:** Exposure

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `scipy`, `statsmodels`, `matplotlib`, `seaborn`

## 📁 Repository Structure
```text
├── Tableau1_Kenniche_Redouane.ipynb      # Baseline characteristics generation
├── Tableau2_Kenniche_Redouane.ipynb      # Efficacy & safety analysis
├── FlowCharts_Kenniche_Redouane.ipynb    # Patient flow chart computation
└── Figure1.ipynb                         # Primary endpoint visualization
