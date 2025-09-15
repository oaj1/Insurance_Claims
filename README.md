# Insurance_Claims (in progress)

This project explores an insurance claims dataset to identify patterns of fraud through  
data cleaning, exploratory analysis (Python + Tableau), and machine learning models.  

**Dataset:** [Mendeley Insurance Fraud Data](https://data.mendeley.com/datasets/992mh7dk9y/2)

---

## 1. Insurance_Claims_Load_Cleaning
**Scope:**
- Load the initial CSV dataset. ('Insurance_Claims_Load_Clean.ipynb')
- Inspect data types, missing values, and distributions.
- Apply data cleaning techniques:
  - Handle missing values
  - Remove/adjust outliers
  - Look at skewed data, decide next steps for analysis (look for heavy right or left tails)
  - Drop any unecessary data
  - Save a clean dataset (`insurance_claims_cleaned_fixed.csv`).

---

## 2. Insurance_Claims_EDA
**Scope:**
- Conduct exploratory analysis in **Python** and **Tableau**.

### 🔹 Python
- Summary statistics and fraud distribution.
- EDA and Visualizations (High-Priority Predictors):
  - Fraud vs. non-fraud distributions (boxplots, histograms).
  - Incident Characteristics EDA.
  - Claim Circumstances and Amounts EDA.
  - Complexity factors EDA.
  - Financial Incentives EDA
  - Tempo
- Multivariate analysis (correlation heatmaps, feature interactions).

### 🔹 Tableau
- As data cleaning and visualization occurs, dynamically create intuitative visualizations.
- Build interactive dashboards to visually explain fraud risk factors.
- Use Tableau for communicating findings to non-technical stakeholders.
- See the below link to for Tableau Public (still in progress)
**Note:** I will use Tableau for visualization and story telling, Python for more advanced statistics and analysis.  

---

## 3. Insurance_Claims_MachineLearning
**Scope:**
- Use cleaned dataset from EDA.
- Feature engineering:.
- Model development:
- Model evaluation:
  - i.e., Confusion matrix, ROC, Precision/Recall, F1-score.
- Goal: Predict likelihood of fraud with interpretable and accurate models.

---

## ✅ Note
- Keep EDA modular (separate notebooks for demographics, claims, financials, etc.).
- Maintain a central README (this file) as a project roadmap and log of key findings.
- Iteratively update Tableau dashboards as new patterns emerge.