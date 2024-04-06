# Loan Default Prediction Model

## Overview
This repository contains the implementation of a loan default prediction model using XGBoost. The model is trained to predict whether a loan applicant is likely to default based on various features such as income, credit score, loan amount, etc.

## Dataset
The dataset used for training and evaluation contains information on loan applicants, including their financial profiles, employment details, and loan terms. It consists of both numerical and categorical features.

## Workflow
The project follows a systematic workflow, including:
1. Exploratory Data Analysis (EDA): Analyzing the dataset to understand the distributions and relationships of features.
2. Feature Engineering: Creating new features or transforming existing ones to improve model performance.
3. Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.
4. Handling Imbalanced Data: Using techniques such as oversampling or undersampling to address class imbalance.
5. Model Selection and Hyperparameter Tuning: Experimenting with various classifiers and optimizing hyperparameters using techniques like GridSearchCV or RandomizedSearchCV.
6. Model Evaluation: Assessing model performance using metrics such as accuracy, F1-score, precision, recall, and AUC-ROC curve.
7. Selection of Best Model: Identifying the XGBoost classifier as the best-performing model based on evaluation results.

## Model Performance Evaluation
- **Accuracy:** 86.14%
- **F1-score (Class 1):** 83.91%
- **Precision (Class 1):** 98.3%
- **Recall (Class 1):** 73.91%
- **AUC (Class 1):** 91.8%

## Conclusion
The XGBoost model demonstrates superior performance in predicting loan defaulters, achieving an accuracy of 86% and a high recall rate of 74%. This indicates that the model effectively identifies instances of defaulters while maintaining a reasonable precision score.

## Future Work
Potential areas for further improvement include:
- Experimenting with additional feature engineering techniques.
- Exploring advanced algorithms or ensemble methods.
- Conducting more extensive hyperparameter tuning to fine-tune model performance.
- Evaluating model robustness using cross-validation or validation on external datasets.
