# Food-Delivery-delay-prediction-
Food delivery delay prediction using Logistic Regression and Random Forest with cross-validation, hyperparameter tuning, and feature importance analysis.

## Project Overview
This project predicts whether a food delivery will be delayed using Machine Learning. The workflow includes data cleaning, handling missing values, exploratory data analysis (EDA), feature engineering, model training, cross-validation, hyperparameter tuning, and model evaluation.

## Problem Statement
Food delivery platforms need to identify orders that are likely to be delayed so that they can take proactive measures and improve customer satisfaction.

## Dataset Features
Some of the important features used:

- City Tier
- Customer Age
- Customer Loyalty Score
- Order Hour
- Delivery Distance
- Preparation Time
- Traffic Level Score
- Weather Severity Score
- Restaurant Rating
- Delivery Partner Rating
- Order Value
- Delivery Fee
- Number of Items
- Premium Customer Flag
- Festival or Weekend Flag

## Data Preprocessing
- Handled missing values using median imputation
- Removed identifier columns
- Removed data leakage features
- Train-test split

## Models Used
### Logistic Regression
Used as a baseline classification model.

### Random Forest Classifier
Used as the final model after model comparison.

## Model Evaluation
Evaluation metrics:

## Hyperparameter Tuning
Used GridSearchCV to optimize Random Forest parameters.

## Key Insights
- Traffic conditions strongly influence delivery delays.
- Weather severity contributes significantly to delays.
- Delivery distance affects delay probability.
- Customer and restaurant-related factors also influence delivery performance.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

