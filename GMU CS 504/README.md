US Inflation Analysis and Prediction

Description:
This project analyzes US inflation data using various machine learning models. The analysis includes data preprocessing, feature selection, and the application of several regression algorithms. The models implemented are ElasticNet, Random Forest, Gradient Boosting, XGBoost, and Support Vector Regression (SVR). A Stacking Ensemble model is also used to combine the predictions of these base models. The project aims to identify the most influential features for predicting inflation rates and compare the performance of different models. Key findings include the identification of CPI_core, import commodity prices, and employment data as major contributors to inflation rates. The SVR model showed the best performance in terms of MSE and R2 score among the individual models tested.

Installation:
To run this project, you'll need Python 3.x and the following libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, xgboost, and neuralprophet. You can install these dependencies using pip with the command: pip install pandas numpy matplotlib seaborn scikit-learn statsmodels xgboost neuralprophet.

Usage:
The project consists of two main Jupyter notebooks: EDA (Exploratory Data Analysis) Notebook and Modeling Notebook. To use the project, clone the repository, install the required dependencies, then open and run the Jupyter notebooks in order. The EDA notebook focuses on data cleaning, preprocessing, and initial analysis. The Modeling notebook implements various machine learning models for inflation prediction.

Contributing:
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

License:
This project is for educational purposes only. The dataset used may have its own licensing terms.
