# 🏦 Customer Churn Prediction

This project predicts whether a bank customer will exit (churn) or stay, based on demographic and financial features.  
The dataset used is **Churn_Modelling.xls**.

---

## 📂 Dataset
- **Rows**: 10,000 customers  
- **Columns**: 14  
- **Target Variable**: `Exited` (0 = Not Churned, 1 = Churned)  
- **Features** include:
  - Customer demographics (Age, Gender, Geography)
  - Account information (CreditScore, Balance, Tenure, Estimated Salary)
  - Customer activity (Number of Products, HasCrCard, IsActiveMember)

---

## 🛠️ Technologies Used
- **Python 3**
- **Pandas, NumPy** (Data Handling)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-learn** (Machine Learning: Logistic Regression, Random Forest, etc.)
- **XGBoost** (Advanced Classification)

---

## 📊 Workflow
1. **Data Preprocessing**
   - Handling categorical variables (Geography, Gender → One-Hot Encoding)
   - Scaling features using StandardScaler
   - Train-test split

2. **Model Training**
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost Classifier

3. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - ROC-AUC Curve
