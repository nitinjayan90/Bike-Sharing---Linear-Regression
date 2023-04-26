# Forecast Demand for a Bike Sharing Service using Linear Regression

In this exercise, we try to predict/forecast the demand for a bike-sharing service using a linear regression model built on weather, season, and time data.

## Summary of Approach:

1. Exploratory Data Analysis: A comprehensive EDA exercise was performed to identify any relationships between demand and the independent variables. This way, insights on which weather (temperature, humidity, etc), months, days of week, were most conducive to bike riding was obtained. We also obtained insights on which independent variables were correlated which were used to trim down our list of independent variables later on. 
2. Data Treatment: Before a linear regression model is fit, the data was scaled and outliers and correlated variables were removed/treated as appropriate. The data was then split into train and test sets for modeling and evaluation purposes.
3. Model Fitting: Modeling was an iterative process involving model fitting, evaluation of regression report, dropping of insignificant variables, and re-fitting on new data.
4. Model Evaluation: For the final model, the residual plots for train/test datasets were analysed to ensure normality, indicating a good fit. R-squared, p-values, VIF values were also analyzed to ensure good fit.

## Results:

Temperature and humidity came out to be some of the biggest drivers of bike sharing demand. Surprisingly, weekday/weekend was not a significant predictor of bike demand. This could indicate that bike sharing is not necessarily catering only to a leisure segment that rides only on the weekends.
