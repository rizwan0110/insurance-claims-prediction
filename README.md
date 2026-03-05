# insurance-claims-prediction

# Overview

This project focuses on predicting insurance claims for horse insurance policies using historical policy and claims data. The objective was to help an insurance company better understand customer behavior and predict the likelihood of future claims, enabling more accurate pricing strategies and improved risk management.

The project was completed as part of my Data Science Master's program at Jönköping University in collaboration with an external industry partner.

# Business Problem

Veterinary care costs and insurance claims had increased significantly, impacting the profitability of the insurance company.

The goal of this project was to:

- Identify patterns in customer behavior and claims history

- Predict whether a customer is likely to file an insurance claim

- Support the development of behavior-based pricing models

# Data

The analysis used two datasets provided by the company:

1. Premium Data

- Customer information

- Policy details

- Horse characteristics

- Payment terms and policy duration

2. Claims Data

- Claim events

- Diagnosis type

- Claim costs

- Policy information

These datasets were merged to create a unified dataset containing both customers with claims and customers without claims.


# Methodology

The project followed a structured data science workflow:

- Data Understanding
- Data Cleaning and Missing Value Handling
- Data Integration (merging premium and claims datasets)
- Feature Engineering
- Feature Selection
- Model Training and Evaluation

New features were created to capture customer behavior patterns, such as:

- Claims per customer
- Claims per year
- Claims per object
- Models Evaluated

# Classification Models Tested 

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors
- Gradient Boosted Trees
- XGBoost
-  Naive Bayes
-  
# Metrcis Used for evaluation 

- Accuracy
- Cohen’s Kappa
- ROC-AUC

# Results

The Logistic Regression model achieved the best overall performance.

Key result:

Accuracy: ~90.9%

The model was able to classify whether a customer is likely to file an insurance claim and estimate the probability of claim occurrence.

# Tools & Technologies

- KNIME Analytics Platform

- Machine Learning classification models

- Data preprocessing and feature engineering

- Statistical evaluation metrics


  
_The dataset and the code cannot be shared/uploaded due to confidentiality agreements with the collaborating company._

