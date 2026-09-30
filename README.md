# House Price Prediction

## Project Overview

This project predicts house prices using machine learning regression algorithms. The project includes data cleaning, exploratory data analysis, feature selection, categorical encoding, model training, evaluation, and feature importance analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The dataset contains information about residential properties and uses `SalePrice` as the target variable.

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Selection
5. Categorical Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Feature Importance Analysis

## Machine Learning Models

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

## Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results

Based on the R² scores from the project:

- Linear Regression: 0.644
- Decision Tree Regressor: 0.772
- Random Forest Regressor: 0.889
- Gradient Boosting Regressor: 0.892

Gradient Boosting Regressor achieved the highest R² score among the models tested.

## Feature Importance

Feature importance analysis was performed using the Gradient Boosting Regressor to identify the features that contributed most to the predictions.

## Key Insights

- Overall house quality has a strong relationship with house price.
- Living area influences house prices
