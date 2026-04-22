# Rice yield prediction in india Using AI
MSc Data Science project: Rice yield prediction in india Using AI

**Project Overview**

Agriculture plays a crucial role in sustaining economies and ensuring food security, particularly in countries like India. Rice is one of the most important staple crops, yet predicting its yield remains a complex challenge due to the influence of environmental and agricultural factors such as rainfall, cultivated area, and seasonal variability.

This project presents a machine learning-driven approach to predict rice yield using historical agricultural and rainfall data. The aim is to develop a reliable and interpretable system that supports farmers, policymakers, and researchers in making informed decisions.

Objectives

Analyse the relationship between rainfall and crop yield
Perform data preprocessing and exploratory analysis
Implement and compare multiple machine learning models
Evaluate model performance using regression metrics
Apply explainable AI techniques for interpretability

Dataset Description

The project integrates two main datasets:

Rainfall Dataset
Annual rainfall
Seasonal rainfall (Jan–Feb, Mar–May, Jun–Sep, Oct–Dec)
Agricultural Dataset
State and district information
Crop year
Cultivated area
Production
Target Variable
Yield = Production / Area
Exploratory Data Analysis (EDA)

EDA was conducted to understand patterns and relationships in the dataset.

Key Insights:
Strong correlation among rainfall variables
Weak linear relationship between rainfall and yield
Evidence of nonlinear interactions

These findings justified the use of advanced machine learning models.

Machine Learning Models Used

Three regression models were implemented and compared:

1️. Linear Regression
Baseline model
Assumes linear relationships
Provides interpretability but limited performance
2️. Random Forest 
Ensemble learning method
Combines multiple decision trees
Handles nonlinear relationships effectively
Reduces overfitting
3️. Gradient Boosting
Sequential ensemble method
Builds trees iteratively to reduce errors
Focuses on improving weak predictions
Often achieves higher accuracy than Random Forest
Model Evaluation Metrics

The models were evaluated using:

MAE (Mean Absolute Error) → measures average prediction error
RMSE (Root Mean Squared Error) → penalises larger errors
R² Score → measures explained variance

Explainable AI

To ensure interpretability:

Feature importance was used to identify key predictors
Permutation importance validated feature influence
Key Insight:

Monsoon rainfall (Jun–Sep) is the most influential factor in rice yield prediction

Scenario Simulation

The model allows simulation of different rainfall conditions:

Drought scenario
Normal rainfall
High rainfall

This project demonstrates how machine learning techniques such as Linear Regression, Random Forest, and Gradient Boosting can be applied to solve real-world agricultural problems. By combining predictive modelling, explainability, and deployment, the project provides a complete and practical solution.

This helps analyse how yield changes under varying environmental conditions.
