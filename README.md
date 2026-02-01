# 💳 Financial Fraud Detection using Machine Learning (LightGBM)

## 📖 Project Overview
This project focuses on building an end to end machine learning pipeline to detect fraudulent financial transactions. The dataset contains more than 6.3 million transaction records and is highly imbalanced with approximately 0.13% fraud cases.

The objective is to develop a robust fraud detection model and derive business insights that can help financial institutions proactively prevent fraudulent transactions.

---

## 🧠 Problem Statement
Financial institutions face significant losses due to fraudulent transactions. This project aims to build a predictive fraud detection model while maintaining a balance between fraud detection accuracy and customer experience.

---

## 📊 Dataset Description
- Large-scale financial transaction dataset  
- ~6.3 Million transaction records  
- Highly imbalanced fraud distribution (~0.13% fraud cases)  
- Features include transaction type, amount, sender balance, receiver balance, and transaction step  

⚠ Note: Dataset is not uploaded due to size and licensing constraints.

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- LightGBM  
- Matplotlib, Seaborn  

---

## 🔬 Project Workflow

### 1️⃣ Exploratory Data Analysis (EDA)
- Fraud class distribution analysis  
- Transaction type vs fraud behaviour  
- Transaction amount distribution  
- Sender and receiver balance behaviour analysis  

### 2️⃣ Data Preprocessing
- Missing value removal  
- Feature selection using EDA + domain knowledge  
- One Hot Encoding using ColumnTransformer  

### 3️⃣ Model Development
- Logistic Regression baseline model  
- Class-weighted Logistic Regression experiment  
- LightGBM final production model  

### 4️⃣ Model Optimization
- Threshold tuning experiment  
- Model comparison using precision, recall, and F1 score  

---

## 📈 Final Model Performance (LightGBM)

### Fraud Class Performance
- Precision ≈ 0.44  
- Recall ≈ 0.49  
- F1 Score ≈ 0.47  

The model provides a balanced trade-off between fraud detection capability and false positive control.

---

## 💡 Key Fraud Risk Insights
The model and EDA identified the following key fraud indicators:
- High transaction amount  
- Transfer transaction type  
- Rapid sender account balance depletion  
- Sudden receiver account balance increase  

---

## 🏦 Business Recommendations
- Risk-based authentication for transfer transactions  
- Additional verification for high value transactions  
- Real-time fraud monitoring systems  
- Adaptive fraud risk scoring mechanisms  

---

## 📌 Future Improvements
- Hyperparameter tuning  
- SHAP-based model explainability  
- Real-time streaming fraud detection  
- Ensemble fraud detection models  

---

## 🚀 How to Run This Project

### 1️⃣ Install Dependencies
