# DevHub-Data-Science-Internship
Repository for Developers Hub Corporation Internship Tasks

# DevHub Data Science Internship Portfolio 🚀

[cite_start]Welcome to my data science project repository for the DevHub Corporation Internship[cite: 111, 112]. [cite_start]This repository documents my end-to-end machine learning implementations, data preprocessing workflows, and predictive modeling tasks[cite: 117].

---

## 📂 Projects Directory

### 1. Credit Risk Prediction Model (Fintech Project) 💳📋

[cite_start]This repository contains an end-to-end Machine Learning pipeline designed to automate the credit risk assessment process for banking institutions[cite: 139]. [cite_start]The model predicts whether a loan application should be **Approved** or **Rejected** based on historical financial parameters[cite: 139].

#### 📝 Project Overview
Manual verification of credit profiles is highly inefficient and prone to human error. [cite_start]This project leverages financial and personal data points (such as CIBIL scores, assets, and income) to classify candidates and minimize financial defaults[cite: 139, 144].

#### 🛠️ Tech Stack & Libraries
* **Language:** Python
* [cite_start]**Data Wrangling:** Pandas, NumPy 
* [cite_start]**Data Visualization:** Matplotlib, Seaborn 
* [cite_start]**Machine Learning:** Scikit-Learn (`sklearn`) 

#### ⚡ Key Implementations
1. [cite_start]**Data Cleaning:** Handled trailing whitespaces in column values and structured raw features[cite: 143].
2. [cite_start]**Exploratory Data Analysis (EDA):** Uncovered strong correlation boundaries around customer credit scores (CIBIL)[cite: 144, 149].
3. **Feature Mapping:** Encoded categorical textual features into binary representations.
4. [cite_start]**Model Training:** Developed a baseline **Logistic Regression** classifier with an 80-20 train-test split ratio[cite: 145].

---

### 2. Bank Customer Churn Prediction 🏦📊

[cite_start]An end-to-end Machine Learning pipeline developed to predict banking customer turnover using a **Random Forest Classifier**[cite: 154, 160]. [cite_start]This project analyzes customer demographics and financial behavior to identify high-risk churn segments[cite: 154, 159], achieving an accuracy of **86.10%**.

#### 📝 Project Overview
[cite_start]Customer retention is one of the primary challenges for modern banking institutions[cite: 154]. [cite_start]This project utilizes customer profiles to build a predictive model that flags customers likely to leave the bank, enabling targeted marketing and loyalty interventions[cite: 154].

#### 📊 Model Performance & Evaluation
* **Overall Model Accuracy:** 86.10%

```text
              precision    recall  f1-score   support

           0       0.87      0.97      0.92      1593 (Stayed)
           1       0.77      0.45      0.57       407 (Churned)

### 3.Predicting Insurance Claim Amounts (Health-Tech Regression Project) 🏥📉
An end-to-end regression modeling pipeline developed to estimate medical insurance costs based on individual health habits and demographic metrics. The project analyzes personal metrics to predict explicit target charges with high statistical accuracy.

📝 Project Overview
Accurate cost forecasting is vital for modern health-tech and insurance underwriting. This project uncovers hidden non-linear relationships across user physical profiles (such as age, BMI, and smoker status) and isolates key financial risk factors using a supervised Linear Regression model.

🛠️ Tech Stack & Libraries
Language: Python

Data Wrangling: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn (sklearn)

📊 Model Performance & Evaluation
Mean Absolute Error (MAE): $4,181.19

Root Mean Squared Error (RMSE): $5,796.28

⚡ Feature Importance & Insights (Model Coefficients)
The model extracted clear directional weights showing the mathematical impact of each feature on base healthcare charges:

smoker_yes (+23,651.13): Being a smoker has the single most dramatic positive correlation with total billing.

children (+425.28): Each additional dependent moderately scales up base claim expectations.

bmi (+337.09): Body Mass Index provides a steady upward scaling parameter for risk pooling.

age (+256.98): Charges progress reliably in a linear fashion for every year older a user gets.
