# DevHub-Data-Science-Internship
Repository for Developers Hub Corporation Internship Tasks
# Credit Risk Prediction Model (Fintech Project) 🏦🚀

This repository contains an end-to-end Machine Learning pipeline designed to automate the credit risk assessment process for banking institutions. The model predicts whether a loan application should be **Approved** or **Rejected** based on historical financial parameters.

## 📊 Project Overview
Manual verification of credit profiles is highly inefficient and prone to human error. This project leverages financial and personal data points (such as CIBIL scores, assets, and income) to classify candidates and minimize financial defaults.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Wrangling:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (`sklearn`)

## ⚡ Key Implementations
1. **Data Cleaning:** Handled trailing whitespaces in column values and structured raw features.
2. **Exploratory Data Analysis (EDA):** Uncovered strong correlation boundaries around customer credit scores (CIBIL).
3. **Feature Mapping:** Encoded categorical textual features into binary representations.
4. **Model Training:** Developed a baseline **Logistic Regression** classifier with an 80-20 train-test split ratio.

## 🎯 Final Model Performance
* **Algorithm:** Logistic Regression
* **Testing Accuracy:** **79.86%** 🔥

## ⚙️ How to Test the Model
You can test the trained model directly by running a manual prediction array:
```python
import sklearn
import numpy as np

# Input Format: [dependents, education, self_employed, income, loan_amt, term, cibil, assets...]
customer_data = [[2, 1, 0, 4000000, 2000000, 4, 750, 2500000, 0, 1200000, 500000]]
prediction = model.predict(customer_data)
