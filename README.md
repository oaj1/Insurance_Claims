# 🧾 Insurance_Claims (In Progress)

This project analyzes an **insurance claims dataset** to uncover potential fraud patterns through structured **data cleaning**, **exploratory data analysis (EDA)**, and **interactive Tableau dashboards**.

**Dataset:** [Mendeley Insurance Fraud Data](https://data.mendeley.com/datasets/992mh7dk9y/2)

---

## 🧹 1. Insurance_Claims_Load_Cleaning

**Scope**
- Load and inspect the raw dataset (`Insurance_Claims_Load_Clean.ipynb`).
- Assess data types, missing values, and distributions.
- Apply cleaning techniques:
  - Handle missing or inconsistent values.
  - Detect and adjust outliers.
  - Review skewed variables for potential transformation.
  - Drop redundant or irrelevant features.
- Export a refined dataset for analysis (`insurance_claims_cleaned_fixed.csv`).

---

## 📊 2. Insurance_Claims_EDA

**Scope**
Perform exploratory data analysis (EDA) using **Python** and **Tableau** to identify key fraud indicators and claim behavior patterns.

### 🔹 Python
- Compute summary statistics and fraud distribution overview.
- Conduct visual EDA across major categories:
  - **Fraud vs. Non-Fraud:** overall distribution and imbalance checks.
  - **Claim Characteristics:** amount, type, and duration analysis.
  - **Demographics & Financials:** income, occupation, education levels.
  - **Complexity Factors:** number of vehicles, witnesses, and claim context.
- Perform multivariate analysis (correlation heatmaps, cross-feature trends).

### 🔹 Tableau
- Build intuitive dashboards to visualize fraud-related trends.
- Example dashboard themes:
  - *Fraud by the Numbers*
  - *Claim Amounts by Type (Injury, Vehicle, Property)*
  - *Demographics and Fraud Likelihood*
- Maintain dynamic updates as new data insights emerge.

---

## ✅ Notes
- Keep EDA modular with separate notebooks for demographics, claims, and financials.
- Use this README as a central roadmap and evolving documentation of findings.
- Continue iterating on Tableau dashboards alongside Python-based analysis.

---

📦 **Project Status:** Active – EDA and Tableau dashboard development in progress  
🧠 **Focus Areas:** Data cleaning, fraud pattern detection, visualization design  
🛠️ **Tools:** Python (Pandas, Matplotlib, Seaborn), Tableau  
