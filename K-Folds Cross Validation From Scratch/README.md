# K-Folds Cross Validation From Scratch

## What is K-Folds Cross Validation and why use it?

K-Folds cross-validation is a technique for evaluating the performance of a machine learning model. It involves dividing the data into a number of "folds", and then training and evaluating the model on each fold using a different combination of training and validation data.

For example, in K = 5-Folds cross-validation, the data is divided into 5 folds, and the model is trained and evaluated 5 times. In each iteration, one of the folds is used as the validation data, and the remaining folds are used as the training data. The performance of the model is then evaluated on the validation data, and the performance scores are averaged across all K folds to give an overall estimate of the model's performance.

K-Folds cross-validation is a useful technique because it allows the model to be trained and evaluated on different subsets of the data, which can help to reduce the bias and variance of the performance estimates. It also allows for the use of all of the data for training and evaluation, which can be important when the amount of data is limited.