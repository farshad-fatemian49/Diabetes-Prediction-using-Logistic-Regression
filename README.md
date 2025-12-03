# Diabetes-Prediction-using-Logistic-Regression


Binary classification models to predict diabetes from clinical measurements using the Pima Indians Diabetes dataset. The project focuses on logistic regression and compares it with several tree-based and ensemble methods.

## Dataset

- Source: Pima Indians Diabetes dataset (768 samples, 8 clinical features + binary outcome).
- Features: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age.
- Target: `Outcome` (1 = diabetic, 0 = non-diabetic).

## Methodology

1. Exploratory data analysis (summary statistics, feature meaning, correlation heatmap).
2. Data cleaning (treating impossible zeros as missing values, imputation) and feature scaling.
3. Baseline logistic regression with statistical interpretation (Statsmodels).
4. Training and evaluating multiple classifiers (Logistic Regression, Decision Tree, Random Forest, KNN, SVM, AdaBoost, Gradient Boosting, XGBoost).
5. Hyperparameter tuning with cross-validation and comparison of train / test accuracy.


## Results

- Logistic regression provides a strong, interpretable baseline for diabetes prediction.
- Some ensemble methods achieve higher accuracy but at the cost of model complexity.
- The final model achieves competitive test performance while remaining suitable for deployment in clinical decision support scenarios.


