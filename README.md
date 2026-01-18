#  Loan Default Risk & Demographic Analysis
**An End-to-End Data Project: Excel | Python | Power BI**

## Project Overview
This project identifies the key factors that lead to loan defaults (Status 0 vs Status 1). Using a large-scale financial dataset, I performed data cleaning, exploratory analysis, and built interactive dashboards to visualize risk across different regions and demographics.

> **Note:** Due to the large size of the original dataset (>25MB), I have provided high-resolution screenshots of the dashboards and the Python analysis notebook below.

##  Interactive Dashboards

### 1. Power BI Deep-Dive
Focuses on dynamic filtering, regional default rates, and LTV/DTI correlations.
![Power BI Dashboard].

### 2. Excel Executive Summary
Focuses on quick pivot-based insights and status distribution by Gender and Age.
![Excel Dashboard].

---

##  Technical Workflow

### 1. Data Cleaning & Preparation (Excel)
- Handled missing values in `dti` and `LTV` columns.
- Standardized `Region` names and formatted `Status` as binary (0/1).
- Used Power Query for initial data transformation.

### 2. Exploratory Data Analysis (Python)
- **Library Used:** Pandas, Matplotlib, Seaborn.
- **Key Task:** Performed Bivariate analysis to see how `Credit_Score` impacts `Status`.
- **Finding:** Applicants in specific `Regions` with low `Credit_Worthiness` scores had a 20% higher default rate.

### 3. Visual Storytelling (Power BI & Excel)
- Created DAX measures for 'Default Rate %'.
- Segmented data by **Gender**, **Age**, and **Loan Purpose** to identify the safest borrower profiles.

## Top Insights
- **High Risk:** Debt-to-Income (DTI) ratio > 45% is the strongest predictor of `Status 1`.
- **Geography:** The [Mention a Region, e.g., North] region showed the highest volatility in repayments.
- **Demographics:** Gender-wise analysis showed stable repayment trends, while Age groups between 25-35 had higher loan application volumes but moderate risk.

##  Repository Contents
- `Loan_Analysis.ipynb`: Full Python source code for EDA.
- `Screenshots/`: High-res images of the analysis and dashboards.
- `README.md`: Project documentation.

---
**Connect with me on [LinkedIn](www.linkedin.com/in/vaishnavi-sharma-741778265) to discuss this project!**
