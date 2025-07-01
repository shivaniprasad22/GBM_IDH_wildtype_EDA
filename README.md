# 🧠 GBM_IDH_Wildtype_EDA – Molecular Insights into Glioblastoma

## 📌 Overview
Glioblastoma (GBM) is an aggressive brain tumor with poor prognosis. This project focuses on exploring the molecular landscape of GBM through an in-depth **Exploratory Data Analysis (EDA)** on:
- **IDH1 mutation status**
- **MGMT promoter methylation**

Understanding these markers is critical for optimizing treatment plans and enhancing patient-specific outcomes.

---

## 🎯 Objectives
- Analyze relationships between **age**, **gender**, and molecular markers (IDH1, MGMT).
- Assess how **MGMT methylation** and **IDH1 mutation** influence **treatment response** and **survival outcomes**.
- Derive clinically meaningful patterns to inform further predictive modeling and personalized medicine approaches.

---

## 🔍 Key Findings

### 1️⃣ **Age and IDH1 Mutation Correlation**
- **Younger patients** show a higher incidence of **IDH1 mutations**.
- **Older patients** are more likely to have **wildtype IDH1**, correlating with poorer outcomes.

### 2️⃣ **MGMT Methylation and Treatment Response**
- **Methylated MGMT** is associated with **better response** to **temozolomide chemotherapy**.
- **Unmethylated MGMT** correlates with **treatment resistance** and lower survival rates.

### 3️⃣ **Gender and Survival Patterns**
- No major gender-based survival differences were observed.
- **Survival outcomes** are more strongly influenced by **IDH1 and MGMT status** than by gender.

---

## 🧠 Clinical Implications
- **Molecular profiling** should be integrated into treatment planning.
- **MGMT methylation** can serve as a biomarker for chemotherapy suitability.
- **IDH1 mutation** status can assist in prognostic modeling and patient stratification.

---

## 🧪 Dataset Description
The dataset includes:
- Demographic information (age, gender)
- Survival data (days, censoring)
- Molecular markers: **MGMT (methylated/unmethylated)**, **IDH1 (mutated/wildtype)**
- Treatment outcomes

---

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- SciPy/Statsmodels for statistical testing

---

## 📊 Visualizations Included
- Distribution plots for age vs IDH1 mutation
- Survival boxplots for MGMT methylation vs outcome
- Heatmaps and grouped bar charts for gender and mutation status comparisons
- Correlation matrices

---

## 🚀 Future Work
- Incorporate findings into **survival prediction models**.
- Extend EDA to include radiomic or genomic features.
- Validate findings on **larger and multi-institutional cohorts**.
- Explore **resistance mechanisms** in MGMT unmethylated GBM.


