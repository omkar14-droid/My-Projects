**Loan Approval & Risk Prediction System**

**Project Overview**

This project focuses on applying Data Mining and Machine Learning (DMML) techniques to solve two key financial problems:
1. Loan Approval Prediction (Classification)
2. Maximum Loan Amount Prediction (Regression)

The goal is to build models that help financial institutions make better lending decisions.

**Part A – Loan Approval Prediction (Classification)**

**Objective:**
To predict whether a loan application will be Approved or Rejected.

Features Used:
1. Age
2. Income
3. Home Ownership
4. Employment Length
5. Loan Intent
6. Loan Amount
7. Loan Interest Rate
8. Loan-to-Income Ratio
9. Payment Default History
10. Credit History Length

Data Preprocessing:
1. Removed irrelevant variables (e.g., ID)
2. Handled missing and invalid values
3. Encoded categorical variables
4. Standardised numerical features
5. Cleaned inconsistent labels

Models Implemented:
1. Naïve Bayes
2. Logistic Regression
3. Random Forest

Evaluation Metrics:
1. Recall
2. Precision
3. F1-Score
4. AUC-ROC

**Best Model -**
Random Forest performed best with:
1. High Precision (0.91)
2. Strong Recall (0.67)
3. Best overall F1-score and AUC

Key Insight:
1. Model shows slight overfitting (train accuracy = 1.0)
2. Still performs well on unseen data

**Part B – Maximum Loan Amount Prediction (Regression)**

**Objective**
Predict the maximum loan amount a customer can receive.

Features Used(Includes both numeric and categorical variables):
1. Income
2. Age
3. Loan Amount
4. Credit History Length
5. Employment Length
6. Loan Intent
7. Payment Default History

Data Preprocessing:
1. Scaled numeric features
2. Kept target variable unscaled
3. Handled inconsistent data

Models Implemented:
1. Decision Tree Regressor (DT1 – numeric only)
2. Decision Tree Regressor (DT2 – all features)

Evaluation Metrics:
1. Mean Squared Error (MSE)
2. Mean Absolute Error (MAE)
3. R-Squared

**Best Model**

DT1 (Numeric Features Only) performed best:
1. Lower prediction errors
2. Higher explanatory power

Key Insight:
1. Simpler model performed better than complex one
2. Pruning improved interpretability but reduced accuracy

Technologies Used:
1. Python
2. Pandas
3. NumPy
4. Scikit-learn
5. Jupyter Notebook

Project Structure:
ML_Project.py – Main notebook with code and analysis
Report.docx – Detailed Project report

**Conclusion**

This project demonstrates how machine learning can:
1. Improve loan approval decisions
2. Predict financial outcomes
3. Support data-driven decision-making
