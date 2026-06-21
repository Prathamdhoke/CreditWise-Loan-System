# CreditWise Loan System

A Machine Learning based loan approval prediction system that helps financial institutions evaluate loan applications using applicant financial and demographic information.

## Project Overview

Financial institutions process hundreds of loan applications every day. Manual verification is often slow, inconsistent, and prone to human bias.

CreditWise Loan System uses historical loan application data to predict whether a loan application should be approved or rejected before final human verification.

The objective is to:

- Reduce approval time
- Improve consistency in decision making
- Minimize risky loan approvals
- Reduce rejection of eligible applicants

---

## Dataset Features

The model uses applicant information including:

- Applicant Income
- Co-applicant Income
- Employment Status
- Age
- Marital Status
- Dependents
- Credit Score
- Existing Loans
- Debt-to-Income Ratio
- Savings
- Collateral Value
- Loan Amount
- Loan Term
- Loan Purpose
- Property Area
- Education Level
- Gender
- Employer Category

Target Variable:

- Loan Approved (1 = Approved)
- Loan Rejected (0 = Rejected)

---

## Project Workflow

### 1. Data Preprocessing

- Missing Value Handling
- Numerical Imputation (Mean)
- Categorical Imputation (Most Frequent Value)

### 2. Exploratory Data Analysis

Performed analysis using:

- Class Distribution
- Histograms
- Box Plots
- Feature Relationships
- Correlation Heatmap

### 3. Feature Engineering

Created additional features:

- DTI_Ratio²
- Credit_Score²

### 4. Feature Encoding

- Label Encoding
- One-Hot Encoding

### 5. Feature Scaling

- StandardScaler

### 6. Model Training

The following machine learning algorithms were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

### 7. Model Evaluation

Models were compared using classification metrics to identify the most suitable loan approval predictor.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Repository Structure

```text
CreditWise Loan System/
│
├── CreditWise.ipynb
├── README.md
└── .gitignore
```

---

## Future Improvements

- Hyperparameter Tuning
- Ensemble Models (Random Forest, XGBoost)
- Model Deployment using Flask/FastAPI
- Interactive Dashboard for Loan Officers

---

## Note

The dataset has been excluded from this repository using `.gitignore`.
To run the notebook locally, place the dataset file in the project directory before execution.
