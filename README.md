# 📊 Credit Risk & Loan Approval Analysis

## 📌 Project Overview
This project analyzes loan approval patterns using a real-world dataset to identify key factors influencing loan decisions. The goal is to uncover insights into how financial and demographic variables impact loan approvals.

---

## 🎯 Objectives
- Understand factors affecting loan approval
- Identify high-risk vs low-risk applicants
- Analyze impact of credit score, income, employment, and loan amount
- Build data-driven insights for financial decision-making

---

## 🛠️ Tools & Technologies
- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 📂 Dataset Features
- Age
- Income
- Loan Amount
- Credit Score
- Years of Experience
- Gender
- Education
- City
- Employment Type
- Loan Approved (Target)

---

## 📊 Key Analysis Performed

### 🔹 Data Cleaning
- Handled missing values using mean and mode
- Created meaningful categorical bins (Income, Credit Score, etc.)

### 🔹 Feature Engineering
- Created:
  - Loan Status (Approved / Rejected)
  - Income Bins
  - Credit Score Bins
  - Experience Bins

---

## 📈 Key Insights

### 🔥 1. Credit Score is the strongest predictor
- Approval sharply increases above **650–700**
- Correlation with approval: **0.46**

---

### 💼 2. Employment Status is critical
- Salaried & Self-employed → ~33% approval
- Unemployed → ~3% approval

---

### 💰 3. Income has moderate impact
- Higher income improves chances
- But strong overlap → not a decisive factor

---

### 💸 4. Loan Amount has minimal impact
- Similar distribution across approved & rejected
- Not a key decision driver

---

### 🎓 5. Education has limited influence
- No strong variation across categories

---

### 📊 6. Threshold-based decision system
- Loan approval follows risk thresholds:
  - Credit Score (Primary)
  - Employment (Secondary)

---

## 📉 Visualizations Included
- Count Plots (Approval distribution)
- Box Plots (Credit Score, Income, Loan Amount)
- Histograms (Income & Credit Score distribution)
- Bar Charts (Approval Rate by categories)
- Heatmap (Correlation matrix)
- Scatter Plot (Income vs Credit Score)
- Bubble Chart (Income vs Loan Amount with Credit Score)

---

## 🧠 Advanced Analysis
- Approval rate by Income & Credit Score bins
- Multi-factor analysis (Employment Type + Gender)
- Correlation analysis

---

## 🚀 Conclusion

Loan approval decisions are primarily driven by:
- Creditworthiness (Credit Score)
- Employment Stability

Secondary factors include income, while loan amount and education have minimal impact.

---

## 📁 Project Structure

Credit-Risk-Analysis/
│
├── data/
│   └── Credit_risk_prediction_dataset.csv
│
├── notebook/
│   └── loan_analysis.ipynb
│
├── outputs/
│   └── charts/
│
├── requirements.txt
└── README.md


## 📌 Future Improvements
- Build ML model for prediction on this will add preditive analysis around that

- ## 👤 Created By
**Rahul Pandey**
