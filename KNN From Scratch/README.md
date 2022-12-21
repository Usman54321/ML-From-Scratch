# K-Nearest Neighbors From Scratch

## What is the K-Nearest Neighbor algorithm?

The K-Nearest Neighbors (KNN) algorithm is a non-parametric method used for classification. In KNN classification, the output is a label. An object is classified by a majority vote of its neighbors, with the object being assigned to the label most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the label of that single nearest neighbor.

KNN is a simple and powerful algorithm for classification. It is a lazy learning algorithm since it doesn't have a specialized training phase. Rather, it uses all of the data for training while classifying a new data point.

To classify a new data point using KNN, the algorithm does the following:

1.  Calculate the distance between the new data point and all of the training data points.
2.  Select the k training data points that are closest to the new data point.
3.  Assign the new data point to the label that is most common among the k nearest neighbors (i.e., the one with the most "votes").