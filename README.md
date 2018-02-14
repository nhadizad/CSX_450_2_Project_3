# Housing Values in Suburbs of Boston #

## Domain ##
The problem is drawn from the study of the housing values in suburbs of Boston.

## Problem Statement ##
We will use supervised learning to develop a regression model that can predict the median value of an owner-occupied home, based on a number of features listed in the dataset section below.

## Dataset ##
The Boston data frame has 506 rows and 14 columns.

The medv variable is the target variable.

This data frame contains the following columns:

    crim
    per capita crime rate by town.
    zn
    proportion of residential land zoned for lots over 25,000 sq.ft.
    indus
    proportion of non-retail business acres per town.
    chas
    Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
    nox
    nitrogen oxides concentration (parts per 10 million).
    rm
    average number of rooms per dwelling.
    age
    proportion of owner-occupied units built prior to 1940.
    dis
    weighted mean of distances to five Boston employment centres.
    rad
    index of accessibility to radial highways.
    tax
    full-value property-tax rate per $10,000.
    ptratio
    pupil-teacher ratio by town.
    black
    1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
    lstat
    lower status of the population (percent).
    medv
    median value of owner-occupied homes in $1000s.



Source
Harrison, D. and Rubinfeld, D.L. (1978) Hedonic prices and the demand for clean air. J. Environ. Economics and Management 5, 81–102.
Belsley D.A., Kuh, E. and Welsch, R.E. (1980) Regression Diagnostics. Identifying Influential Data and Sources of Collinearity. New York: Wiley.

## Solution ##

A solution to this problem will be a regression model such as a linear regression, a decision tree regressor, or a support vector regressor.

## Benchmark Model ##

A good naive benchmark would be to use either the mean or the median of the value of owner-occupied home for the dataset.

## Performance Metric ##

We can measure the success of our model using the R2 metric, the Mean Absolute Error, or the Mean Squared Error.