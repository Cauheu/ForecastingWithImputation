# ForecastingWithImputation
Building Models for Data Forecasting with Imputation

# Imputation methods
Imputation for completing missing values using k-Nearest Neighbors.

Each sample’s missing values are imputed using the mean value from n_neighbors nearest neighbors found in the training set. 
Two samples are close if the features that neither is missing are close.

# Forecastiing model
Logistic regression is a kind of multiple regression, general
whose purpose is to analyze the relationship between several independents
variables (regressors or predictors) and the dependent variable. Binary
logistic regression, as the name implies, is used when dependent
the variable is binary (ie can take only two values). Others
in other words, logistic regression can be used to estimate probability
that the event will occur for a particular subject (sick / healthy,
loan repayment / default, etc.). This is achieved by applying the following
regression equation (logit transformation):
![image](https://user-images.githubusercontent.com/17165539/167123057-39aaf9c5-61fc-4b10-8b08-2738d871a0b0.png)
where P is the probability that the event of interest will occur; is the basis
natural logarithms 2.71; y is a variable determined by the linear equation
regression.
