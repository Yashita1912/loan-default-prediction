# loan-default-prediction
Machine Learning project that predicts loan default risk using Logistic Regression, Decision Trees, Random Forest, and XGBoost. Includes data preprocessing, exploratory data analysis, class imbalance handling, stratified cross-validation, hyperparameter tuning, and model comparison.

> 🚧 **Work in Progress:** This project is still under active development. Additional model improvements, hyperparameter tuning, and further experimentation are currently being implemented.

## Project Overview

This project aims to predict whether a borrower is likely to default on a loan using supervised machine learning techniques. Financial institutions rely on accurate default prediction models to assess credit risk and make informed lending decisions. The objective of this project is to compare multiple classification algorithms and identify the model that provides the best balance between identifying potential defaulters while minimizing incorrect predictions.

The project follows a complete machine learning workflow, beginning with data preprocessing and exploratory data analysis, followed by model building, evaluation, and optimisation.

---

## Models Implemented

The following machine learning models have been implemented and compared:

- Logistic Regression (Baseline Model)
- Decision Tree Classifier
- Random Forest (Bagging)
- XGBoost (Boosting)

Each model is evaluated using the same **Stratified 5-Fold Cross-Validation** strategy to ensure a fair and consistent comparison.

---

## Project Workflow

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Handling Class Imbalance
- Model Training
- Stratified K-Fold Cross Validation
- Model Evaluation
- Feature Importance Analysis
- Hyperparameter Tuning *(In Progress)*
- Final Model Comparison *(In Progress)*

---

## Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

Since loan default prediction is an imbalanced classification problem, greater emphasis is placed on **Recall** and **F1-Score** rather than overall accuracy.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Key Concepts Demonstrated

- Binary Classification
- Logistic Regression
- Decision Trees
- Ensemble Learning
- Bagging (Random Forest)
- Boosting (XGBoost)
- Class Imbalance Handling
- Stratified K-Fold Cross Validation
- Hyperparameter Tuning
- Feature Importance Analysis
- Model Performance Comparison

---

## Current Status

✅ Data preprocessing completed

✅ Exploratory Data Analysis completed

✅ Logistic Regression implemented

✅ Decision Tree implemented

✅ Random Forest implemented

✅ XGBoost implemented

✅ Unified evaluation framework using Stratified K-Fold Cross Validation

🚧 Hyperparameter tuning in progress

🚧 Final model optimisation and comparison in progress

---

## Future Improvements

- Hyperparameter optimisation using GridSearchCV / RandomizedSearchCV
- Threshold tuning for improved default detection
- ROC-AUC and Precision-Recall Curve analysis
- SHAP values for model interpretability
- Feature selection and dimensionality reduction
- Model deployment using Streamlit or Flask

---

## Repository Structure

```
loan-default-prediction/
│
├── loan-default-prediction.ipynb
├── README.md
├── requirements.txt
└── data/
```

---

## Learning Objectives

This project was built to strengthen practical machine learning skills by implementing an end-to-end predictive modelling pipeline on a real-world financial dataset. It demonstrates data preprocessing, model development, evaluation, and optimisation while applying best practices such as consistent cross-validation and class imbalance handling.

---

## Disclaimer

This project is intended for educational and portfolio purposes. The models developed are not intended for production use or real-world lending decisions without further validation and testing.
