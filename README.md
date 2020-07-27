# House Price Prediction
This is a project assigned to me during [theDevMasters](https://www.thedevmasters.com) bootcamp.<br> 
For more information or to enter the kaggle competition, click [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview).

## Introduction
Whether a client is looking to buy or sell, he/she would want to avoid overpaying for or underselling his/her house. With machine learning, models are developed
to estimate house prices. Models that predict house prices accurately gives a starting point clients need to move forward on their financial decision. As a 
result, companies that utilize these models receive a higher return on revenue by helping these clients connect with real estate agencies and mortgage lenders.

## Objective
The objective of the project is to predict house sale price.

## Metric
The Root Mean Squared Logarithmic Error (RMSLE) was used as the evaluation metric for this project. The metric score indicates how different the predicted 
values are from the actual values.

## Approach
The following steps were taken to complete the project:
1. Import libraries and datasets
2. Analyze data
3. Remove Outliers
4. Impute Missing Values
5. Transform Features
6. Correct Data Type
7. Create New Features
8. Encode Categorical Columns
9. Select Best Model
10. Submit Result

## Model Selection
The model was chosen based on the lowest RMSLE score.<br>
**Note:** Ridge Regression, Gradient Boosting Regression, and Extreme Gradient Boosting Regression models were used for the stacking model.<br>

<img width="388" alt="Screen Shot 2020-07-18 at 11 20 07 PM" src="https://user-images.githubusercontent.com/51253177/87868761-38744f00-c94e-11ea-85e6-25b7bd7762aa.png">

## Technologies
Application: Jupyter Notebook<br>
Programming Language: Python 3.7.4<br>
Libraries: Numpy, Pandas, Scipy, Matplotlib, Seaborn, Scikit-learn, XGBoost<br>

## Project Files
* [README](https://github.com/Ericjung008/House-Price-Prediction/blob/master/README.md)
* [Project](https://github.com/Ericjung008/House-Price-Prediction/blob/master/House%20Price.ipynb)
* [Train Dataset](https://github.com/Ericjung008/House-Price-Prediction/blob/master/train.csv)
* [Test Dataset](https://github.com/Ericjung008/House-Price-Prediction/blob/master/test.csv)
* [Data Dictionary](https://github.com/Ericjung008/House-Price-Prediction/blob/master/data_description.txt)

## Acknowledgments
The datasets used to complete this project were compiled by Dean De Cock.
