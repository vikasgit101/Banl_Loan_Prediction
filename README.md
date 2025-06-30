# 💳 Loan Approval Prediction using Machine Learning

> 🚀 A **supervised machine learning** project to predict whether a loan application should be approved based on applicant demographic and financial data. This model is designed to support **automated loan screening**, reduce default risks, and minimize human bias.

---

## 📚 Table of Contents
- [📌 Overview](#-overview)
- [🎯 STAR-Based Summary](#-star-based-summary)
- [🛠 Tech Stack](#-tech-stack)
- [📂 Dataset Information](#-dataset-information)
- [🔄 Project Workflow](#-project-workflow)
- [📈 Results](#-results)
- [💻 How to Run](#-how-to-run)
- [🖼️ Screenshots](#-screenshots)
- [🎓 Certifications](#-certifications)
- [📣 Keywords & Hashtags](#-keywords--hashtags)
- [📬 Contact](#-contact)

---

## 📌 Overview

In the financial domain, the loan approval process is crucial yet often challenged by manual screening and data inconsistencies. This project leverages **classification models** to automate loan decisions using historical data. With this solution, financial institutions can **predict loan approvals with higher accuracy** and fairness.

---

## 🎯 STAR-Based Summary

**S – Situation:** Loan disbursal is often delayed by subjective decision-making and inconsistent applicant evaluation.

**T – Task:** Develop a machine learning model that can accurately predict the likelihood of a loan being approved.

**A – Action:**  
- Conducted **data cleaning**, handled missing values, and created engineered features like `TotalIncome` and `LoanAmount_log`.  
- Applied **EDA** to uncover trends and impactful variables using `Seaborn` and `Matplotlib`.  
- Trained **Logistic Regression** and **Decision Tree Classifier** models using `scikit-learn`.  
- Evaluated models via **confusion matrix**, **precision**, **recall**, and **F1-score`.

**R – Result:**  
- Achieved up to **81% accuracy** using Logistic Regression.  
- Identified **credit history** and **income** as key predictors of approval.  
- Delivered a scalable ML solution ready for real-time deployment in fintech scenarios.

---

## 🛠 Tech Stack

- **Language:** Python  
- **IDE:** Jupyter Notebook  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Models Used:** Logistic Regression, Decision Tree Classifier  
- **Tools:** Excel (for initial inspection), Git, GitHub

---

## 📂 Dataset Information

- **Source:** [Kaggle – Loan Prediction Dataset](https://www.kaggle.com/)  
- **Total Records:** 614  
- **Features:** 13 (Categorical + Numerical)  
- **Target Variable:** `Loan_Status` (Y/N)  
- **Key Features:**  
  - Gender, Marital Status, Dependents  
  - Education, Employment, Credit History  
  - Applicant & Coapplicant Income  
  - Loan Amount & Term

---

## 🔄 Project Workflow

```plaintext
📥 Data Import
🧹 Data Cleaning & Feature Engineering
📊 Exploratory Data Analysis (EDA)
🔄 Encoding & Normalization
🧠 Model Training (Logistic Regression, Decision Tree)
📈 Performance Evaluation (Confusion Matrix, F1-score)
```

---

## 📈 Results

| Model              | Accuracy | Notes                             |
|-------------------|----------|-----------------------------------|
| Logistic Regression | **81%**  | Best performer, generalizes well |
| Decision Tree       | 77%      | Slightly overfits small datasets  |

- 🔍 **Top Predictors:** Credit History, Applicant Income  
- 📊 **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 💻 How to Run

### 🔧 Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### ▶️ Run Notebook
```bash
jupyter notebook Loan_Approval_Pridiction.ipynb
```

---

## 🖼️ Screenshots

<p align="center">
  <img src="./assets/loan_approval_prediction.png" alt="Loan Prediction Visualization" width="700">
</p>

> Confusion Matrix, Feature Importance, and Target Distribution visualizations for model interpretation

---

## 🎓 Certifications

This project aligns with hands-on components of:

- 🎓 IBM Data Analyst Professional Certificate (Python, Visualization, Data Analysis)  
- 🎓 Microsoft Career Essentials in Machine Learning  
- 🎓 Forage Virtual Internships – JPMorgan Chase, KPMG Data Analytics

---

## 📣 Keywords & Hashtags

### 🔑 Keywords:
Loan Prediction ML, Logistic Regression, Classification Model, Python for ML, Supervised Learning, Scikit-learn, EDA, Data Cleaning, Loan Approval, Credit Risk Modeling, Feature Engineering

### 📢 Hashtags:
#LoanPrediction #MachineLearning #DataAnalytics #PythonProjects #ScikitLearn #EDA #FeatureEngineering #GitHubPortfolio #VikasKumarProjects

---

## 📬 Contact

- 📧 Email: vk328696@gmail.com  
- 🔗 LinkedIn: [linkedin.com/in/vikasku](https://linkedin.com/in/vikasku)  
- 📂 GitHub: [github.com/vikasgit101](https://github.com/vikasgit101)

---

> ⭐ *If you found this project helpful, feel free to star ⭐ the repo and connect with me on LinkedIn!*
