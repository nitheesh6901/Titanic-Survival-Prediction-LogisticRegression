# Titanic-Survival-Prediction-LogisticRegression

# Titanic Survival Prediction using Logistic Regression

Project Overview
Predict survival of passengers from the Titanic dataset using Logistic Regression with and without regularization (L1 & L2).

Dataset
Dataset from OpenML: [Titanic](https://www.openml.org/d/40945)

Steps
1. Data Preprocessing
   - Handle missing values
   - Encode categorical variables
   - Feature scaling
2. Train Logistic Regression models
   - No regularization
   - L2 Regularization (Ridge)
   - L1 Regularization (Lasso)
3. Evaluation
   - Accuracy, Precision, Recall, F1-score
   - Classification report

Key Learnings
- How regularization affects model performance
- L1 for feature selection, L2 for penalizing large coefficients
- Train-test split and scaling impact

Usage
```python
# Clone repo and run
python titanic_logreg.py
