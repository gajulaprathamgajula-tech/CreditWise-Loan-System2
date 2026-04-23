# CreditWise-Loan-System
Built an end-to-end supervised ML pipeline using KNN, Logistic Regression and Naive Bayes to predict loan approval.  Implemented Binary classification along with EDA, feature engineering &amp; model evaluation (Precision, Recall, F1) 
# 🚀 Loan Approval Prediction using Machine Learning

## 📌 **Project Overview**
This project focuses on predicting whether a loan application will be approved or rejected based on applicant details such as income, credit score, employment status, and financial background.  
It demonstrates a complete end-to-end machine learning pipeline.

---

## 🎯 **Objective**
The goal of this project is to build a reliable classification model that can assist financial institutions in making accurate and efficient loan approval decisions.

---

## 📊 **Dataset Description**
The dataset contains applicant-related features including:
- Applicant Income
- Co-applicant Income
- Credit Score
- Debt-to-Income (DTI) Ratio
- Savings
- Employment Status
- Property Area and more

---

## ⚙️ **Project Workflow**

### 🔹 Data Preprocessing
- Handled missing values using mean (numerical) and mode (categorical)
- Removed irrelevant features like Applicant ID

### 🔹 Exploratory Data Analysis (EDA)
- Analyzed distributions using histograms
- Detected outliers using boxplots
- Studied feature relationships with loan approval

### 🔹 Feature Engineering
- Created new features such as:
  - DTI Ratio Squared
  - Credit Score Squared
- Captured non-linear relationships to improve model performance

### 🔹 Feature Encoding
- Label Encoding for binary variables
- One-Hot Encoding for categorical variables

### 🔹 Feature Scaling
- Applied StandardScaler to normalize numerical features

---

## 🤖 **Machine Learning Models Used**
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes

---

## 📈 **Model Evaluation Metrics**
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🏆 **Results**
Among all the models tested, **Naive Bayes** achieved the best performance based on precision and F1-score, making it the most suitable model for this problem.

---

## ▶️ **How to Run the Project**
```bash
pip install -r requirements.txt
python loan_model.py
