Create a predictive model that can be used with any Financial instrument. 

In this project we will explore which regression model model makes the best prediction.

Regression models implemented:

- Linear Regression
- SGD Regressor
- Extreme Gradient Boosting Regressor
- Bagging Regressor
- Random Forest Regressor

Libraries Utilized:
sys, pandas, numpy, matplotlib, seaborn, pandas datareader, sklearn, joblib, xgboost

1) Use the Pandas datareader API to allow the user to Enter the asset of their choice.
2) Check of missing (null) data
3) Visualize the closing price in line chart format
4) Remove outliers in the dataset
5) Create a function that generates custom features of the dataset utilizing the Open, High, Low, Close, Volume from the original dataset along with 5, 21, 50, 200 period windows.
6) Visualize the statistics of each feture and ensure the Dtypes are correct
7) Check the correlation of the features by using a heatmap
8) Split the data into training and testing datasets train with approximately 80% of the data
9) Scale the predictive dataset 
10) Create models for each of the listed regression models
11) filter the regressors with the least mean_absolute_error value to assess the top performing model




# Resources
Linear Regression - 

scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html


SGD Regressor - 

scikit-learn.org/stable/modules/generated/sklearn.linear_model.SGDRegressor.html


Extreme Gradient Booster -

scikit-learn.org/stable/auto_examples/ensemble/plot_gradient_boosting_regression.html


Bagging Regressor -
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingRegressor.html


Random Forest Regressor - 

scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html