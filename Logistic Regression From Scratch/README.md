# Logistic Regression From Scratch

## What is Logistic Regression?

Similar to Linear Regression, Logistic Regression is a regression model based on supervised learning. It is mainly used for binary classification problems. It aims to minimize the gradient of the logistic loss function. The logistic loss function is as follows:

$$f(\theta) = -\frac{1}{m} \sum_{i=1}^{m} log(\sigma(y_ix_i^T\theta)), \quad \sigma(s) = 1/(1+e^{-s})$$
Taking the gradient of this and setting it to 0 results in the normal equation which is as follows:

$$\nabla f(\theta) = -\frac{1}{m}  \sum_{i=1}^{m} (\sigma(y_ix_i^T\theta)-1)$$
Iterating over this by using gradient descent allows us to minimize loss and reduce misclassification. In this project I have also implemented minibatches with stochastic gradient descent which offers a further improvement to the speed and accuracy of the algorithm.