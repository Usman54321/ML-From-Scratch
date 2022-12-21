# Linear and Ridge Regression From Scratch

## What is Linear Regression in ML?

Linear Regression is a regression model based on supervised learning. Given some set of points, linear regression attempts to find the line (or hyperplane in higher dimensions) that best fits the data. This line can be of any order, not just first order (i.e., a straight line) as is the case of polynomial regression where the line is of a higher order (e.g., second order, third order, etc.).

The normal equation provides an analytical solution to the linear regression problem. The normal equation is as follows:

$$ \theta = (X^T X)^{-1} X^T * y $$

where theta is the vector of coefficients, X is the matrix of independent variables, and y is the vector of dependent variables. The normal equation aims to find the coefficients that minimize the sum of the squared errors.

## What is Ridge Regression?

Ridge regression is a type of linear regression that is used to prevent overfitting in the model. It is called "ridge" regression because it adds a "ridge" penalty term to the cost function of the linear regression, which forces the coefficients of the model to be small and prevents them from becoming too large.

In contrast, linear regression does not include a regularization term in the cost function, and therefore the coefficients of the model can become arbitrarily large. This can lead to overfitting, where the model fits the training data well but does not generalize well to new data.