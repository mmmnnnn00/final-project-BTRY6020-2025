# final-project-BTRY6020-2025

# BTRY 6020 Final Project 

This repository contains the code, analysis, and final report for my **BTRY 6020 (Statistical Methods II)** final project at Cornell University.

## Project Overview
The goal of this project was to build and evaluate a linear regression model to predict plasma glucose concentration measured 2 hours after an oral glucose tolerance test (OGTT), using accessible clinical predictors. This work demonstrates key skills in regression modeling, assumption checking, variable selection, and interpretation.

## Dataset
The dataset used is the **Healthcare Diabetes Dataset**, which was obtained from Kaggle:
> [https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes/data](https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes/data)

This dataset includes 10 variables for 2768 individuals. 
- Id: Unique identifier for each data entry.
-  Pregnancies: Number of times pregnant.
- Glucose: Plasma glucose concentration over 2 hours in an oral glucose tolerance test.
- BloodPressure: Diastolic blood pressure (mm Hg).
- SkinThickness: Triceps skinfold thickness (mm).
- Insulin: 2-Hour serum insulin (mu U/ml).
- BMI: Body mass index (weight in kg/height in m^2).
- DiabetesPedigreeFunction: Diabetes pedigree function, a genetic score of diabetes.
- Age: Age in years.
- Outcome: Binary classification indicating the presence (1) or absence (0) of diabetes.

## Key Methods and Tools
-  Exploratory Data Analysis: Summary stats, histograms, and missing data handling
- Regression Assumptions Check: Linearity, normality, homoscedasticity, multicollinearity
- Data Cleaning: Imputing/removing implausible values, log-transforming skewed variables
- Variable Selection & Model Validation: Forward selection via AIC and BIC, 10-fold cross-validation using RMSE, R², MAE
