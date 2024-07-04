
# **Boston House Price Prediction using XGBRegressor**

This project demonstrates how to predict house prices in Boston using the XGBoost regression model (XGBRegressor). The dataset used is the Boston Housing dataset from scikit-learn, which contains information about various houses in Boston. The goal is to predict the median value of owner-occupied homes (MEDV) based on different features.  

## Requirements:  
- Ensure you have Python 3.x installed along with the following libraries:
- scikit-learn
- XGBoost
- pandas
- numpy
- matplotlib

## This script will:

- Load the Boston Housing dataset.
- Preprocess the data (handle missing values, scale features if necessary).
- Split the data into training and testing sets.
- Train an XGBRegressor model on the training data.
- Evaluate the model's performance on the testing data.
- Make predictions on new data points (example included).

## View results:  

The script will print evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score to evaluate the model's performance. Additionally, it will visualize predicted vs actual prices for a subset of the data.

## Files:
- house_price.ipynb: Main script for data loading, preprocessing, model training, evaluation, and prediction.
- readme.md: This file, providing an overview of the project and instructions.
- boston.csv: Dataset required for the project.

## References:
- XGBoost Documentation
- Scikit-learn Documentation
- Boston Housing Dataset

