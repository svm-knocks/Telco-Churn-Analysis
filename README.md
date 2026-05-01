# 📊 Telecom Customer Churn Prediction System

## 🧠 Objective
To develop a predictive risk modeling system that identifies customers with high probability of churn, enabling data-driven retention strategies in the telecom sector.

---

## 🎯 Problem Statement
Customer churn represents a critical revenue leakage problem in subscription-based businesses.  
The goal is to build a classification model that estimates churn probability using customer behavioral, demographic, and service usage data.

---

## 📁 Dataset Overview
- Source: Telco Customer Churn Dataset  
- Observations: Customer-level historical records  
- Target Variable: Binary classification (Churn: Yes / No)  
- Feature Types: Categorical + Numerical mixed structured data  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Missing value treatment and type correction (`TotalCharges`)  
- Encoding categorical variables  
- Feature scaling for numerical stability  

### 2. Exploratory Data Analysis (EDA)
- Churn distribution analysis  
- Feature correlation study  
- Behavioral segmentation of customers  

### 3. Feature Engineering
- Conversion of categorical variables into numerical space  
- Identification of high-signal churn drivers  
- Removal of redundant features  

### 4. Model Development
Models evaluated:
- Logistic Regression (baseline)  
- Decision Tree Classifier  
- Random Forest Classifier (final model)  

### 5. Evaluation Strategy
- Accuracy  
- Confusion Matrix  
- Precision / Recall trade-off analysis  

---

## 📊 Results
- Final Model: Random Forest Classifier  
- Accuracy: ~79%  
- Output: Probabilistic churn classification with improved generalization over baseline models  

---

## 📌 Key Insights
- Month-to-month contracts exhibit significantly higher churn probability  
- Higher monthly charges correlate positively with churn risk  
- Customer tenure is inversely related to churn likelihood  
- Service bundling reduces churn probability  

---

## 💡 Business Interpretation
This model functions as a **customer risk scoring system**, enabling telecom operators to:
- Identify high-risk customers early  
- Optimize retention campaigns  
- Reduce revenue leakage through proactive interventions  

---

## 🚀 Future Enhancements
- Hyperparameter optimization for model tuning  
- Gradient boosting models (XGBoost / LightGBM)  
- Conversion into real-time prediction API (Flask / FastAPI)  
- Deployment as interactive dashboard (Streamlit)  

---

## 👨‍💻 Author
**Saivamshi Miryalkar**  
Aspiring Data Analyst | Quantitative Thinking | Python | SQL | Machine Learning  

---

## 🔗 Repository
https://github.com/svm-knocks/Telco-Churn-Analysis
