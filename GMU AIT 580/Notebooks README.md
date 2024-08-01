This project contains one main Jupyter notebook: Austin TX House Predictions ML - May 2022.ipynb. The purpose of this comprehensive notebook is to cover the entire data analysis and machine learning process for the Austin housing dataset. The notebook is structured into several key sections.

The first section, "Data Loading and Initial Exploration," imports the necessary libraries, loads the dataset, and performs initial data checks, including examining the data information, identifying duplicates, and checking for null values.

The next section, "Exploratory Data Analysis and Preprocessing," visualizes data distributions, handles outliers, performs feature engineering (such as calculating the distance from the city center and creating zipcode categories), and scales time series data.

In the "Feature Selection" section, the notebook calculates correlations, computes the Variance Inflation Factor (VIF), and uses SelectKBest for feature selection.

The "Machine Learning Models" section implements Multiple Linear Regression and Random Forest Regression. It also performs K-Nearest Neighbors Classification for home types and zipcode types.

Finally, the "Model Evaluation" section calculates and interprets various performance metrics, including R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE). Additionally, it generates visualizations of the model results.

Overall, this notebook provides a comprehensive end-to-end analysis of the Austin housing dataset, from initial data exploration to the implementation and evaluation of multiple machine learning models.
