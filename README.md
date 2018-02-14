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


$ crim   : num  0.00632 0.02731 0.02729 0.03237 0.06905 ...

$ zn     : num  18 0 0 0 0 0 12.5 12.5 12.5 12.5 ...

$ indus  : num  2.31 7.07 7.07 2.18 2.18 2.18 7.87 7.87 7.87 7.87 ...

$ chas   : int  0 0 0 0 0 0 0 0 0 0 ...

$ nox    : num  0.538 0.469 0.469 0.458 0.458 0.458 0.524 0.524 0.524 0.524 ...

$ rm     : num  6.58 6.42 7.18 7 7.15 ...

$ age    : num  65.2 78.9 61.1 45.8 54.2 58.7 66.6 96.1 100 85.9 ...

$ dis    : num  4.09 4.97 4.97 6.06 6.06 ...

$ rad    : int  1 2 2 3 3 3 5 5 5 5 ...

$ tax    : num  296 242 242 222 222 222 311 311 311 311 ...

$ ptratio: num  15.3 17.8 17.8 18.7 18.7 18.7 15.2 15.2 15.2 15.2 ...

$ black  : num  397 397 393 395 397 ...

$ lstat  : num  4.98 9.14 4.03 2.94 5.33 ...

$ medv   : num  24 21.6 34.7 33.4 36.2 28.7 22.9 27.1 16.5 18.9 ...



Source
Harrison, D. and Rubinfeld, D.L. (1978) Hedonic prices and the demand for clean air. J. Environ. Economics and Management 5, 81–102.
Belsley D.A., Kuh, E. and Welsch, R.E. (1980) Regression Diagnostics. Identifying Influential Data and Sources of Collinearity. New York: Wiley.

## Solution ##

A solution to this problem will be a regression model such as a linear regression, a decision tree regressor, or a support vector regressor.

## Benchmark Model ##

A good naive benchmark would be to use either the mean or the median of the value of owner-occupied home for the dataset.

## Performance Metric ##

We can measure the success of our model using the R2 metric, the Mean Absolute Error, or the Mean Squared Error.