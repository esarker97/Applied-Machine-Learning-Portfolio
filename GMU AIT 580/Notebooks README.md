This project contains one main Jupyter notebook:
Austin TX House Predictions ML- May 2022.ipynb:
Purpose: This comprehensive notebook covers the entire data analysis and machine learning process for the Austin housing dataset.
The notebook is structured into several key sections:

Data Loading and Initial Exploration:

Imports necessary libraries
Loads the dataset
Performs initial data checks (info, duplicates, nulls)


Exploratory Data Analysis and Preprocessing:

Visualizes data distributions
Handles outliers
Performs feature engineering (e.g., calculating distance from city center, creating zipcode categories)
Scales time series data


Feature Selection:

Calculates correlations
Computes Variance Inflation Factor (VIF)
Uses SelectKBest for feature selection


Machine Learning Models:

Implements Multiple Linear Regression
Implements Random Forest Regression
Performs K-Nearest Neighbors Classification for home types and zipcode types


Model Evaluation:

Calculates and interprets various performance metrics (R-squared, MAE, RMSE)
Generates visualizations of model results



This notebook provides a comprehensive end-to-end analysis of the Austin housing dataset, from initial data exploration to the implementation and evaluation of multiple machine learning models.
