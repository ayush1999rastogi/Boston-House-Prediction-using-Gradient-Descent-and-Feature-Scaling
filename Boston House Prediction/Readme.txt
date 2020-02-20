Boston dataset predictions using-Gradient Descent Algorithm
In this project I'm attempting to do data analysis on the Boston dataset, the aim is to apply Gradient Descent Algorithm to predict the prices of house in boston dataset.
 I have tried to implement the gradient descent algorithm from scratch without the support of the inbuilt libraries.
Data description
The medv variable is the target variable
The Boston data frame has 506 rows and 14 columns.This data frame contains the following columns:
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
full-value property-tax rate per \$10,000.
ptratio
pupil-teacher ratio by town.
black
1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
lstat
lower status of the population (percent).
medv
median value of owner-occupied homes in \$1000s.
Gradient Descent :
Gradient descent is an optimization algorithm used to find the values of parameters (coefficients) of a function (f) that minimizes a cost function (cost).

Result:
Managed to successfully implement the algorithm using feature scaling and got a accuracy score of 0.75 i.e we get an average accuracy of 75+%.
