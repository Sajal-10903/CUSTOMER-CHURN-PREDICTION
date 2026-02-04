# Customer Churn Prediction using Machine Learning

## 📌 Overview
Customer churn is a major challenge for subscription-based and service-driven businesses.
This project focuses on predicting whether a customer is likely to churn using historical
customer data and supervised machine learning classification models.

---

## 🎯 Objective
To build and evaluate machine learning models that can accurately predict customer churn
based on customer demographics, service usage, and account-related features.

---

## 📂 Dataset
The dataset contains customer-level information with the following key attributes:

- Customer Demographics (Age, Gender, etc.)
- Account Information (Tenure, Contract Type, Payment Method)
- Service Usage Details
- Monthly Charges
- Total Charges
- **Churn (Target Variable)**

Target Variable: **Churn**  
- Yes → Customer left  
- No → Customer retained  

Dataset Source: Telco Customer Churn Dataset (Kaggle)

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Handled missing and inconsistent values  
- Encoded categorical variables  
- Scaled numerical features  

### 2. Exploratory Data Analysis (EDA)
- Churn distribution analysis  
- Customer tenure and churn relationship  
- Impact of charges and contract type on churn  

### 3. Model Building
- Logistic Regression as baseline model  
- Random Forest Classifier for non-linear patterns  

### 4. Model Evaluation
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  

### 5. Model Interpretability
- Feature importance analysis  
- Identification of key churn drivers  

---

## 📊 Results & Key Insights
- Customers with short tenure have a higher churn rate  
- Month-to-month contracts show significantly higher churn  
- Higher monthly charges increase churn probability  
- Random Forest outperformed Logistic Regression in overall performance  

---

## 💼 Business Impact
This model can help organizations:
- Identify high-risk customers early  
- Design targeted retention strategies  
- Reduce customer acquisition and retention costs  

---

## ✅ Conclusion
The project demonstrates how classification-based machine learning models can be applied
to predict customer churn effectively. By combining EDA, feature engineering, and model
evaluation, the project delivers actionable business insights.

---

## 🔮 Future Enhancements
- Hyperparameter tuning using GridSearchCV  
- Handling class imbalance using SMOTE  
- Deployment as a web application  

---

## 👤 Author
**Sajal Raj**  
MCA (AI & Data Science)
