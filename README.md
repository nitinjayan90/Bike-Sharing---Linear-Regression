# Forecasting Demand for a Bike Sharing Service using Linear Regression
This project aimed to predict and forecast the demand for a bike-sharing service by building a linear regression model based on weather, season, and time data.

## Summary of Approach
### Exploratory Data Analysis
A comprehensive exploratory data analysis (EDA) exercise was performed to identify relationships between demand and the independent variables. The analysis provided insights into which weather conditions (temperature, humidity, etc.), months, and days of the week were most conducive to bike riding. Correlation analysis was used to trim down the list of independent variables.

### Data Treatment
Before fitting a linear regression model, the data was scaled, and outliers and correlated variables were removed or treated as appropriate. The data was then split into training and testing sets for modeling and evaluation purposes.

### Model Fitting
Modeling was an iterative process that involved fitting the model, evaluating the regression report, dropping insignificant variables, and re-fitting on new data.

### Model Evaluation
For the final model, residual plots for the train and test datasets were analyzed to ensure normality, indicating a good fit. R-squared, p-values, and VIF values were also analyzed to ensure a good fit.

## Results
The analysis revealed that temperature and humidity were the most significant drivers of bike sharing demand. Surprisingly, weekday/weekend was not a significant predictor of bike demand. This could indicate that bike sharing is not necessarily catering only to a leisure segment that rides only on weekends.

Overall, the model provides a useful tool for predicting and forecasting demand for a bike-sharing service based on weather, season, and time data.
