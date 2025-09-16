# Diabetic-safety
### Diabetes Prediction Model

## Overview
This project aims to predict whether a person is likely to have diabetes based on medical and demographic features using machine learning techniques. The model is trained and evaluated on a structured dataset of patients' health information.

The goal is to assist in early detection and risk assessment for diabetes.

## Dataset
File: diabetes_prediction_dataset.csv
Features (columns in dataset, e.g.):

Gender

Age

Hypertension

Heart Disease

Smoking History

BMI

HbA1c Level

Blood Glucose Level

Diabetes (Target: 0 = No, 1 = Yes)


## Machine Learning Model
Implemented in Python using scikit-learn.
1.Preprocessing steps include:

Handling categorical variables

Scaling numerical features

Splitting data into training and testing sets

2.Models trained and tested:

Logistic Regression

Random Forest

XGBoost (if included)

3.Evaluation Metrics:

Accuracy

Precision

Recall

F1-score

ROC-AUC

## Results
Best model:  Random Forest with 97% accuracy

Key insight: HbA1c level and blood glucose level were the most important predictors.


