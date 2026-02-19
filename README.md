**Customer Churn Prediction System (Production-Level ML Project)**

Developed an end-to-end machine learning system to predict customer churn using the Telco Customer Churn dataset. The project focuses on identifying customers likely to leave a service, enabling businesses to take proactive retention measures.

 **Problem Statement**

Customer churn significantly impacts revenue in subscription-based businesses. This project builds a predictive system to identify high-risk customers based on demographic, service usage, and billing information.

**Key Features**

Data preprocessing and feature engineering

Class imbalance analysis and handling

Hyperparameter tuning using GridSearchCV

5-fold cross-validation for robust model validation

Model comparison and ROC-AUC evaluation

**Confusion matrix visualization**

Feature importance analysis for business insights

Saved production-ready model using Joblib

**Model Performance**

Evaluated using ROC-AUC, precision, recall, and F1-score

Achieved strong predictive performance with optimized XGBoost model

Cross-validated to ensure generalization capability

**Business Insights**

The model identified tenure, contract type, and monthly charges as the most significant churn drivers. Customers with month-to-month contracts and higher monthly charges showed increased churn probability.

This enables businesses to:

Offer targeted retention discounts

Improve contract structures

Design loyalty programs for high-risk customers

**Tech Stack**

Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib, Seaborn

Joblib
