# 💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions.  
Handles imbalanced data using preprocessing, feature scaling, and classification models like **Logistic Regression** and **Random Forest**.  

## 🔍 Problem Statement
Credit card fraud is rare but critical. This project focuses on identifying fraud in a highly imbalanced dataset.

## 📊 Dataset
- Anonymized credit card transaction data  
- Numerical features (PCA transformed)  
- Target variable:  
  - `0` → Legitimate  
  - `1` → Fraudulent  

## ⚙️ Approach
- **Data Preprocessing:** Handling imbalance, feature scaling, train-test split  
- **Model Building:** Logistic Regression, Decision Tree, Random Forest, (Optional) SVM / XGBoost  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC–AUC  

## 🚀 Results
Models are evaluated mainly on **recall and precision**, as detecting fraud correctly is more important than overall accuracy.

## 🛠️ Technologies
Python, NumPy, Pandas, Scikit-learn, Matplotlib / Seaborn

## 📌 Conclusion
Demonstrates how ML classification models can effectively detect fraudulent transactions while managing imbalanced datasets.

