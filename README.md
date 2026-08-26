# Customer Churn Prediction

## 📌 Project Overview

Customer churn is a major challenge for businesses, as losing existing customers can directly impact revenue and growth. This project uses machine learning to predict whether a customer is likely to churn based on customer demographics, account information, services, and billing-related features.

The project follows an end-to-end machine learning workflow, including data cleaning, exploratory data analysis, feature engineering, model building, and performance evaluation.

---

## 🎯 Objectives

- Analyze customer data to identify patterns associated with churn
- Perform data cleaning and preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Prepare features for machine learning models
- Build and compare multiple classification models
- Evaluate model performance using Accuracy and ROC-AUC
- Identify insights that could support customer retention strategies

---

## 📊 Exploratory Data Analysis

The dataset was explored to understand how different customer characteristics relate to churn.

Key areas analyzed include:

- Customer tenure
- Monthly charges
- Total charges
- Contract type
- Internet service
- Payment method
- Online security
- Technical support
- Streaming services
- Customer demographics and service usage

The analysis helped identify patterns and trends that may contribute to customer churn.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Google Colab

---

## 🤖 Machine Learning Models

The following classification models were trained and evaluated:

### 1. Logistic Regression

Used as a baseline classification model.

**Accuracy:** 78.32%  
**ROC-AUC:** 82.99%

### 2. Random Forest

An ensemble learning model used to capture more complex relationships within the data.

**Accuracy:** 79.89%  
**ROC-AUC:** 82.16%

### 3. XGBoost

A gradient boosting model used for classification and predictive performance.

**Accuracy:** 78.25%  
**ROC-AUC:** 81.16%

---

## 📈 Model Comparison

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 78.32% | 82.99% |
| Random Forest | **79.89%** | 82.16% |
| XGBoost | 78.25% | 81.16% |

### Key Findings

- **Random Forest achieved the highest accuracy** at approximately **79.9%**.
- **Logistic Regression achieved the highest ROC-AUC score** at approximately **83.0%**.
- The results demonstrate the importance of comparing models using multiple evaluation metrics rather than relying only on accuracy.

---

## 🔍 Machine Learning Workflow

```text
Raw Data
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Performance Comparison & Business Insights

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Machine Learning
- Classification
- Model Comparison
- Model Evaluation
- Accuracy and ROC-AUC Analysis
- Business Insight Generation

---

## 📂 Project Structure

```text
customer-churn-prediction/
│
├── Customer_churn.ipynb
├── README.md
└── .gitignore

##🚀 Conclusion

This project demonstrates an end-to-end machine learning workflow for predicting customer churn.

Multiple machine learning models were trained and compared to understand their performance on the classification task. Random Forest achieved the highest accuracy, while Logistic Regression achieved the highest ROC-AUC score.

The project also highlights how customer data can be transformed into meaningful insights that may help businesses identify customers at risk of churn and support data-driven customer retention strategies.

##👩‍💻 Author

Kavya Sharma

Aspiring Data Scientist | AI & Data Analytics | Machine Learning
