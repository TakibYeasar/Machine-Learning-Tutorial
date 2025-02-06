## 
===>> 

## What is Linear Regression in Machine Learning...?
===>> Linear Regression is a supervised machine learning algorithm that learns a linear relationship between one or more
input features (X) and the single output variabel (Y). As a standard paradigm of machine learning, the output variable is
dependent on the input features.


## Aim of a Linear Regression...?
===>> The main aim of a linear regression, find out best fit line in such a way that the distance between these data points and the predicted
points should be very very less or minimal.


## Mathematical Unerstanding of Linear Regression
===>> In a machine learning problem, linearity is defined as the linearly dependent nature of a set of independent features X and 
the dependent quantity y. Mathematically, if **X = [x1, x2, …, xn]** is a set of independent features, and y is a dependent quantity, 
we try to find a function that maps **y → X** as,
**y = β0 + β1*x1 + β2*x2 + ..... + βn*xn + ξ**
The βi’s are the parameters (also called weights) that our Linear Regression algorithm learns while mapping X to Y using supervised
historical data. ξ is the error due to fitting imperfection, as we can not assume that all the data samples will perfectly 
follow the expected function.


## Types of Linear Regression
===>> There are mainly two types of Linear Regression:
**Simple Linear Regression**
Suppose the number of independent features in X is just one. In that case, it becomes a category of simple linear regression 
where we try to fit a conventional linear line Y = m*X + c, where “m” is the slope, and “c” is the intercept. 
For example, suppose we want to predict the house price by knowing the house size.
**Multiple Linear Regression**
If the number of independent features in X is more than 1, it becomes a category of multiple linear regression.
y = β0 + β1*x1 + β2*x2 + ..... + βn*xn + ξ
For example, considering all essential features for predicting house price becomes a multiple linear regression. 
Most of the industry problems are based on this.


## What is it useful for...?
===>> 
**Predictive Analysis:** It helps in predicting the value of the dependent variable based on the independent variables.
**Understanding Relationships:** It provides insights into the strength of relationships between variables.
**Trend Analysis:** It is commonly employed in the time series analysis to understand and predict trends.
**Feature Importance:** The coefficients obtained from a linear regression model can indicate the features' importance.


## Key parameters of Linear Regression
===>> 
**R-squared (Coefficient of Determination):**
Measures the proportion of the variance in the dependent variable that is predictable from the independent variables. 
It ranges from 0 to 1, where higher values indicate a better fit.
**P-values:**
Indicate the statistical significance of each coefficient, where low p-value (< 0.05) suggests that the independent 
variable is significantly related to the dependent variable.
**Standard Error:**
Provides an estimate of the uncertainty of the coefficient estimates.
**Residuals:**
The differences between observed and predicted values.
**F-statistic:**
Employed to test the overall model's significance. It compares the model with no predictors (intercept only) to determine 
if the model with predictors is significantly better.
**Assumptions:**
Linear regression assumes linearity, independence, homoscedasticity (constant variance of errors), 
and normality of residuals. Violation of these assumptions could affect the validity of the model.


## 
===>> 















