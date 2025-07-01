* Insurance Expense Prediction - Linear Regression

  This project applies Linear Regression to analyze and predict individual medical insurance expenses based on demographic and lifestyle features. The goal is to model the relationship between personal characteristics (such as age, BMI, smoking status, etc.) and insurance charges, and accurately predict future expenses.

* Problem Statement

The business objective is to:

Understand which factors most significantly affect insurance charges.

Build a predictive model to estimate medical expenses for new customers.

* Dataset Overview

  The dataset contains:

* Independent Variables:
  
age: Age of the individual.

sex: Gender of the individual.

bmi: Body Mass Index.

children: Number of dependent children covered by insurance.

smoker: Smoking status (yes/no).

region: Residential region in the US.

* Dependent Variable:

charges: Medical insurance cost billed to the customer.

* Steps Followed:
  
1. Business Problem Understanding:

  Defined a regression problem to estimate medical charges using client demographics.

2. Data Understanding

  Loaded and explored the dataset.
  Visualized relationships using scatter plots and correlation matrix.

3. Data Preprocessing

  Handled categorical variables using Feature-Mapping encoding.

  Split the data into training and testing sets.

4. Modeling

  Used Linear Regression from sklearn.linear_model.

  Fitted the model using the training dataset.
  
  Interpreted model coefficients to identify impactful features.

5. Evaluation

  Assessed model performance using:

  R² Score (Train & Test)

  Cross-Validation Score

  Visualized:

  Distribution of residuals
  
6. Final Model Summary

  The final model captures trends effectively and shows good generalization across train/test splits.

  Can be used to estimate charges for new customers based on their personal details.
