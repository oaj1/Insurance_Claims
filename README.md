# Insurance_Claims

This project explores an insurance claims dataset to identify patterns of fraud through  
data cleaning, exploratory analysis (Python + Tableau), and machine learning models.  

**Dataset:** [Mendeley Insurance Fraud Data](https://data.mendeley.com/datasets/992mh7dk9y/2)

---

## 1. Insurance_Claims_Load_Cleaning
**Scope:**
- Load the initial CSV dataset.
- Inspect data types, missing values, and distributions.
- Apply data cleaning techniques:
  - Handle missing values
  - Remove/adjust outliers
  - Encode categorical fields (as needed)
  - Save a clean dataset (`clean_fraud.csv`).

---

## 2. Insurance_Claims_EDA
**Scope:**
- Conduct exploratory analysis in **Python** and **Tableau**.

### 🔹 Python
- Summary statistics and fraud distribution.
- Visualizations:
  - Fraud vs. non-fraud distributions (boxplots, histograms).
  - Claim comparisons (`vehicle_claim`, `injury_claim`, `property_claim`, `total_claim_amount`).
  - Demographic and financial factors (`age`, `months_as_customer`, `capital-gains/loss`).
  - Categorical features (`incident_type`, `collision_type`, `incident_severity`).
- Multivariate analysis (correlation heatmaps, feature interactions).

### 🔹 Tableau
- Highlight **4–5 of the most interesting relationships** discovered in Python.
- Build interactive dashboards to visually explain fraud risk factors.
- Use Tableau for communicating findings to non-technical stakeholders.

**Note:** This is the stage where you may lean more on **Tableau for storytelling**,  
while Python remains your deeper statistical/technical exploration tool.  

---

## 3. Insurance_Claims_MachineLearning
**Scope:**
- Use cleaned dataset from EDA.
- Feature engineering:
  - Ratios (e.g., claim amount ÷ premium).
  - Encodings (categorical → numeric).
  - Scaling if required.
- Model development:
  - Baseline: Logistic Regression.
  - Advanced: Decision Tree, Random Forest, XGBoost.
- Model evaluation:
  - Confusion matrix, ROC, Precision/Recall, F1-score.
- Goal: Predict likelihood of fraud with interpretable and accurate models.

---

## ✅ Next Steps
- Keep EDA modular (separate notebooks for demographics, claims, financials, etc.).
- Maintain a central README (this file) as a project roadmap and log of key findings.
- Iteratively update Tableau dashboards as new patterns emerge.