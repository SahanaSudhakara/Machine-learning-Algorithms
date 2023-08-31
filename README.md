# Linear Regression 
This README provides an overview of the Linear Regression code that generates scatter plots and showcases the steps involved in performing Linear Regression.

## Scatter Plots for Feature Analysis
The core function of the code is to generate scatter plots that display the relationship between selected features and the target variable ('cnt'). 

# Steps Involved in Linear Regression

## Using Matrix Version:
1)Construct Design matrix 'X' and co-efficient matrix'B' => using normal equation provides a way to find the best-fitting line that
minimizes the sum of squared residuals in a linear regression problem.
2)Predicted y values (predicted_y) are obtained using the calculated coefficients.

How good is this predictions?
1) Sum of Squares Residual (SSR) and Total Sum of Squares (SSt) are computed to assess the model's performance.
2) The Coefficient of Determination (R-squared) is calculated, indicating the proportion of variance in the target variable explained by the model.

## Using LinearRegression Class:

1) The LinearRegression class from scikit-learn is imported to create a linear regression model.
2)In the Linear Regression Class, the model automatically fits the best-fitting line to the data using mathematical techniques,
 allowing you to visualize the learned relationship between variables.

## Usage
Choose the matrix version to understand the math behind linear regression or opt for the LinearRegression class for practical and efficient implementation with real-world data.
