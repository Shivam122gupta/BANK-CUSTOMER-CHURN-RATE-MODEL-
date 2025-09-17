# Bank Customer Churn Prediction

This project predicts **customer churn** (whether a bank’s customer will leave or stay) using machine learning models.  
It is based on the dataset from Kaggle:  
👉 [Predicting Churn for Bank Customers](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers)

---

## 📊 Dataset
- Source: Kaggle (Adammaus – Predicting Churn for Bank Customers)
- Features include: `CustomerId`, `CreditScore`, `Geography`, `Gender`, `Age`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`
- Target variable: `Exited` (1 → churned, 0 → retained)

---

## 🔍 Project Workflow
1. **Data Loading & Exploration**
   - Read dataset
   - Checked missing values
   - Performed feature inspection and visualization

2. **Preprocessing**
   - Handled categorical variables with encoding
   - Handled missing values
   - Feature scaling

3. **Model Building**
   - Implemented multiple ML models including:
     - Logistic Regression
     - Random Forest
     - XGBoost
   - Compared results using:
     - Accuracy
     - Precision
     - Recall
     - F1-score

4. **Evaluation**
   - Created summary table of model performances
   - Selected the best performing model

---

## ⚡ Current Issue (Work in Progress)
While running XGBoost, an error occurs:  
