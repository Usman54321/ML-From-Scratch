# Decision Trees From Scratch

## What are Decision Trees?

A decision tree is a type of predictive model in machine learning that is used to make predictions based on certain features or characteristics of the data. It is called a "decision tree" because it starts with a single root node (representing the entire dataset) and splits it into branches that represent different possible outcomes or decisions.

The basic idea behind decision trees is to recursively split the data into smaller and smaller subsets, based on certain features or attributes, until each subset contains only a single class or label. This process is called "tree induction" or "tree growing."

At each step of the tree induction process, the decision tree algorithm selects the feature that best splits the data into subsets with the most pure classes (i.e., the subsets contain examples belonging to a single class). This is done using a metric called "information gained" of the data, which measures how much you learn by splitting on a given feature.

Once the tree is fully grown, it can be used to make predictions on new data by following the branches of the tree based on the values of the input features.