# Diabetes Prediction Using Logistic Regression

## Overview
This project focuses on predicting diabetes in patients using logistic regression. The dataset contains various features such as glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age, which are used to predict the likelihood of a patient having diabetes.

## Dataset
The dataset used in this project is `diabetes.csv`, which contains 768 instances and 9 features including the target variable 'Outcome'. The features are:
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (0: Non-diabetic, 1: Diabetic)

## Data Cleaning
The dataset is clean and does not contain any missing values, eliminating the need for data cleaning operations.

## Visualization
- The distribution of diabetic and non-diabetic patients is visualized using a count plot.
- Pair plots are used to visualize relationships between different features and the target variable.

## Modeling
- Logistic Regression model is trained using the data to predict diabetes.
- The model is evaluated using accuracy score and classification report.

## Results
- Accuracy Score: 74.41%

## Contents
- `diabetes.csv`: CSV file containing the dataset.
- `diabetes_prediction.ipynb`: Jupyter Notebook containing code for diabetes prediction using logistic regression.

## Dependencies
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Contributors
- [Sai Charan](https://github.com/your_username)
