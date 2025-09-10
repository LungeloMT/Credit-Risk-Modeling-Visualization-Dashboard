# 🏦 Credit Risk Modeling: Predicting Loan Defaults

## 📌 Project Overview
This project demonstrates how **statistics, probability, and machine learning** can be applied to predict **loan defaults**.  
We build a **logistic regression model** to estimate default probabilities and create an **interactive dashboard** to visualize borrower risk.  

The goal is to provide **actionable insights for lenders**, helping them make informed credit decisions.

---

## 🎯 Objectives
- Explore borrower data and loan characteristics using **EDA** (histograms, boxplots, correlation).  
- Apply **statistical hypothesis testing** to validate key risk factors.  
- Build a **predictive model** to estimate loan default probability.  
- Develop a **risk scoring system** (Low, Medium, High Risk).  
- Visualize results with **interactive Plotly charts** for dashboard-style insights.

---

## 📂 Dataset
- **Source**: [Kaggle Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)  
- **Size**: ~325,000 loan records  
- **Key Features**:
  - `person_age` – Borrower’s age  
  - `person_income` – Annual income  
  - `loan_amnt` – Loan amount requested  
  - `loan_int_rate` – Loan interest rate  
  - `loan_status` – Target variable (1 = default, 0 = non-default)  

---

## 🔎 Key Insights
- Defaulters generally have **lower incomes** and request **higher loan amounts**.  
- T-tests confirm **income is a significant factor** in loan default (p < 0.01).  
- Loan amounts are **significantly associated with default risk**.  
- Logistic regression achieves **78% accuracy** and **ROC-AUC of 0.83**.  
- Risk scoring classifies borrowers into **Low, Medium, and High Risk** tiers.

---


> Fully interactive and **runs directly in Jupyter Notebook**. No additional packages required beyond Plotly.

---

## ⚙️ Installation & Usage

