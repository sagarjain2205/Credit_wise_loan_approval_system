# Credit Wise Loan Approval Prediction System

A Machine Learning based system that predicts whether a loan application will be approved or rejected using applicant financial and personal details.

---

## Project Overview

This project aims to automate the loan approval decision process using historical data and machine learning techniques.

It reduces manual effort and improves decision accuracy by identifying key factors affecting loan approval.

This is a **Binary Classification Problem** where the target variable is:

**Loan_Approved (Yes / No)**

---

## Key Highlights

- Implemented complete ML pipeline from data preprocessing to model evaluation
- Used **three different Machine Learning algorithms**
- Compared model performance
- Achieved **87% prediction accuracy**
- Identified important features affecting loan approval decisions

---

## Machine Learning Algorithms Used

The following models were trained and evaluated:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Gaussian Naive Bayes

### Final Result

- Best Accuracy Achieved: **87%**
- After comparing multiple models, **Naive Bayes performed the best** in terms of overall performance and precision.

---

## Features of the System

- Data Cleaning and Missing Value Handling
- Exploratory Data Analysis (EDA)
- Outlier Detection
- Feature Encoding (Label Encoding & One-Hot Encoding)
- Correlation Analysis using Heatmap
- Feature Scaling using StandardScaler
- Model Training and Evaluation using Accuracy, Precision, Recall, F1 Score

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset Attributes

- Gender
- Marital Status
- Education
- Employment Status
- Applicant Income
- Coapplicant Income
- Credit Score
- Loan Amount
- Property Area

**Target Variable:**

- Loan_Approved

---

## Project Workflow

1. Data Collection & Loading
2. Data Preprocessing
3. Handling Missing Values
4. Exploratory Data Analysis
5. Feature Engineering
6. Encoding Categorical Variables
7. Train-Test Split
8. Feature Scaling
9. Model Training (3 Algorithms)
10. Model Comparison
11. Accuracy Evaluation
12. Best Model Selection

---

## How to Run

```bash
git clone https://github.com/your-username/credit-wise-loan-approval-system.git

- Open in Jupyter Notebook and run all cells.