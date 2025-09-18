Bank Customer Churn Prediction

This project predicts customer churn (whether a bank’s customer will leave or stay) using machine learning models.
It is based on the dataset from Kaggle:
👉 Predicting Churn for Bank Customers

📊 Dataset

Source: Kaggle (Adammaus – Predicting Churn for Bank Customers)

Features include:
CustomerId, CreditScore, Geography, Gender, Age, Balance,
NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary

Target variable:
Exited → (1 → churned, 0 → retained)

🔍 Project Workflow

Data Loading & Exploration

Loaded dataset

Checked missing values

Performed feature inspection and visualization

Preprocessing

Handled categorical variables with encoding

Converted None values to np.nan

Applied feature scaling

Model Building

Implemented multiple ML models including:

Logistic Regression

Random Forest

XGBoost

Compared models using:

Accuracy

Precision

Recall

F1-score

Evaluation

Created summary table of model performances

Best model achieved ~86% accuracy

🛠️ Bug Fix

While running XGBoost, an error occurred:

XGBoostError: Invalid type for: `missing`, expecting one of the: {`Number`, `Integer`}, got: `Null`

Cause:

The dataset had None values instead of np.nan.

XGBoost does not handle Python None directly.

⚡ Result:
✅ The best-performing model gave an accuracy of ~86%, making it suitable for predicting churn in bank customers.