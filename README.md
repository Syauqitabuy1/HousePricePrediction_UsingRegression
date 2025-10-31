# HousePricePrediction_UsingRegression

## Business Question:
How to predict the selling price of a house?

## Tools: 
Python, Pandas, Matplotlib, Statsmodels

## Dataset: 
Downloaded from Kaggle (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data), accessed October 2025

## Method:
I am trying to predict house selling prices using regression because I want to see the relationships between variables in a sample of data and then use the regression model to predict the prices for other sample houses. Therefore, the technique I used in this project  was not machine learning. However, I will use econometrics to make the results more meaningful.

  Model: Ordinary Least Squares (OLS)

  Transformation: Logarithm

  Classical Assumption Test:
- Heteroscedasticity → Passed
- Multicollinearity → Passed
- Normality → Slight deviation
- R² = 0.78
- F-stat = 0.00 (significant)

## Prediction Result
The model can predict prices with fairly good accuracy, with the predicted distribution close to the actual data.




