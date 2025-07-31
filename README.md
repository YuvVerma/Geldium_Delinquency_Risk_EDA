# Geldium_Delinquency_Risk_EDA
# Geldium Delinquency Risk EDA

## 📊 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Geldium’s customer credit dataset to assist **Tata iQ's analytics team** in refining their **delinquency risk prediction model**. The analysis aims to uncover missing data issues, detect early risk factors, and ensure data readiness for predictive modeling.

---

## 📁 Files in This Project

| File Name                          | Description |
|-----------------------------------|-------------|
| `Delinquency_prediction_dataset.csv` | Main dataset containing financial and credit behavior features for 500 customers |
| `EDA_SummaryReport_Template.docx`   | Provided template for structuring the EDA summary report |
| `EDA_SummaryReport_Filled.docx`     | Completed version of the EDA report with findings and recommendations (if generated) |
| `README.md`                         | This file — project overview and documentation |

---

## ⚙️ Tools & Technologies

- Python (Pandas, NumPy)
- Jupyter/Colab Notebook
- Excel/CSV handling
- Generative AI (ChatGPT, DeepSeek)
- Word Processor (MS Word for reporting)

---

## 🧠 Key Steps Performed

1. **Dataset Review**  
   - Checked data structure, types, and key variables  
   - Identified missing values and inconsistencies

2. **Missing Data Treatment**  
   - Imputed missing values for `Income`, `Credit_Score`, and `Loan_Balance`  
   - Chose imputation methods (mean/median) based on data type and business relevance

3. **Pattern Detection & Risk Indicators**  
   - Explored correlation between variables and delinquency  
   - Identified high-risk features like `Missed_Payments`, `Credit_Utilization`, and `Debt_to_Income_Ratio`

4. **AI & GenAI Support**  
   - Used AI tools to guide imputation strategy, detect anomalies, and identify predictive variables

---

## 🔍 Insights & Recommendations

- Strong predictors of delinquency include:
  - High number of missed payments
  - High credit utilization rate
  - Low credit score
  - High debt-to-income ratio

- Next Steps:
  - Use cleaned dataset to build classification models (e.g., Logistic Regression, Random Forest)
  - Perform feature engineering on `Month_1` to `Month_6` columns to extract repayment patterns
  - Monitor fairness metrics if synthetic data generation is applied

---

## ✍️ Author

Prepared by: *Yuvraj Verma*  
For: *Geldium x Tata iQ* Analytics Task  
Date: *31-07-2025*

---
