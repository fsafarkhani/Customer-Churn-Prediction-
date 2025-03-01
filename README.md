# 📉 Customer Churn Prediction in Telecommunications

## 🚀 Project Overview
This project applies **machine learning techniques** to predict **customer churn** in the **telecommunications industry**.  
The goal is to **identify at-risk customers** before they leave and help telecom companies develop **targeted retention strategies**.

✅ **Key Highlights**:
- **Dataset**: Real-world telecom customer churn data  
- **Models Used**: Logistic Regression, Decision Tree, Random Forest, XGBoost  
- **Feature Importance**: Using **SHAP values & Random Forest importance**  
- **Performance Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
- **Explainability**: SHAP-based model interpretation  
- **Business Impact**: Helps companies **minimize churn rates & optimize customer engagement**  

--

## 📊 Dataset Information
The dataset contains **customer behavior data**, including:
- 📞 **Call Failures** – Number of failed call attempts  
- ❗ **Customer Complaints** – Number of formal complaints  
- 🏷️ **Subscription Length** – How long a customer has been with the provider  
- 💰 **Charge Amount** – Monthly billing amount  
- 📡 **Service Engagement** – Frequency of calls and SMS usage  
- ✅ **Churn Status** – Target variable (1 = Churn, 0 = No Churn)  

📌 **Dataset Source**: (https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset)  

---

## 🔬 Machine Learning Models Used
We experimented with multiple models to predict customer churn:  

| **Model**              | **Accuracy** | **Precision** | **Recall** | **F1 Score** | **ROC-AUC** |
|------------------------|------------|------------|--------|----------|---------|
| Logistic Regression   | 86.9%      | 0.73       | 0.40   | 0.52     | 0.68    |
| Decision Tree         | 93.2%      | 0.83       | 0.77   | 0.80     | 0.87    |
| Random Forest        | 94.1%      | 0.86       | 0.79   | 0.82     | 0.88    |
| **XGBoost**          | **94.4%**  | **0.88**   | **0.79** | **0.83** | **0.88** |

📌 **Key Findings**:
- **XGBoost performed best**, with the highest accuracy (94.4%) and precision (0.88).  
- **Customer complaints and short subscription length are the strongest churn predictors.**  
- **SHAP analysis** was used to interpret model decisions and explain feature importance.  

---

## 📊 Feature Importance & Explainability (SHAP)
To understand **which features contribute most to churn**, we used:
1. **Random Forest Feature Importance** → Identifies the most predictive factors.
2. **SHAP Values (SHapley Additive Explanations)** → Provides a transparent way to interpret model decisions.

📌 **Feature Importance (Top 3 Predictors)**:
1. **Customer Complaints** – Strongest churn predictor.  
2. **Subscription Length** – Shorter contracts = higher churn risk.  
3. **Charge Amount** – High bills increase churn likelihood.  

📌 **SHAP Visualization**: Shows the individual impact of each feature on the model’s predictions.  

---


