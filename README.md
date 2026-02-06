# Customer-Churn-Prediction-for-Subscription-Services
End-to-end customer churn prediction using machine learning
# Customer Churn Prediction for Subscription Services

## 📌 Project Overview
Customer churn is a critical problem for subscription-based businesses, as acquiring new customers is often more expensive than retaining existing ones.  
This project builds an **end-to-end machine learning pipeline** to predict whether a customer is likely to churn based on their demographic, service usage, and billing information.

The model helps businesses proactively identify high-risk customers and design targeted retention strategies.

---

## 🎯 Problem Statement
Predict whether a customer will churn (Yes/No) using historical customer data from a subscription service.

**Objective:**
- Build a reliable churn prediction model
- Identify key factors contributing to customer churn
- Provide actionable business insights

---

## 📊 Dataset
**Dataset:** Telco Customer Churn  
**Source:** Kaggle  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

> The dataset is loaded directly via a public URL in the notebook to ensure full reproducibility.  
> No local file uploads are required.

---

## 🧪 Approach & Methodology
1. Data loading from a public source
2. Exploratory Data Analysis (EDA)
3. Data cleaning and preprocessing
4. Categorical feature encoding
5. Feature scaling
6. Train-test split
7. Model training:
   - Logistic Regression (baseline)
   - Random Forest (advanced)
8. Model evaluation using:
   - Accuracy
   - Precision, Recall, F1-score
   - ROC-AUC score
   - Confusion Matrix
9. Feature importance analysis for business insights

---

## 📈 Results
- **Random Forest** outperformed Logistic Regression
- Achieved strong ROC-AUC score
- Key churn drivers identified:
  - Customer tenure
  - Contract type
  - Monthly charges
  - Payment method

---

## 🧠 Business Insights
- Customers with month-to-month contracts are more likely to churn
- Long-tenure customers show lower churn probability
- High monthly charges increase churn risk
- Targeted offers and loyalty programs can reduce churn

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## ▶️ How to Run the Project
1. Open the notebook located in the `notebooks/` folder
2. Run all cells sequentially in Google Colab
3. The dataset loads automatically from an online source

---

## 📂 Repository Structure
