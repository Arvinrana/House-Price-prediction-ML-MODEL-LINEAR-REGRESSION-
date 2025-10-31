# House-Price-prediction-ML-MODEL-LINEAR-REGRESSION-
House Price Prediction using Machine Learning
Project Overview

This project focuses on predicting house prices based on multiple property features such as total square feet, location, number of bedrooms, and bathrooms.
The dataset was taken from Kaggle and contains around 12,000 records.
The main objective was to build an accurate price prediction model

Tech Stack

Languages & Tools:
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

 Project Workflow

Data Collection

Kaggle housing dataset (12K+ entries)

Data Cleaning

Removed duplicates and handled missing values

Fixed inconsistent entries and formatted numerical columns

Exploratory Data Analysis (EDA)

Studied correlations and patterns

Visualized price distribution and relationships between features

Feature Engineering

Encoded categorical columns

Applied log transformation on target variable

Removed outliers using IQR

Model Building & Evaluation

Trained Linear Regression, Random Forest, and XGBoost

Compared model performance using R² and RMSE

Finalized XGBoost as the best model


 Model Performance
Model	R² Score	RMSE	Remarks
Linear Regression	0.78	0.42	Baseline
Random Forest	0.85	0.35	Improved
XGBoost	0.89	0.28	Best Performing Model

Key insights into top and low-value regions

Key Insights

Location and square footage have the strongest effect on house prices.

Price per sqft varies widely between regions, even for similar property sizes.

The model’s predictions align closely with actual prices, proving strong reliability.
