# Naive Bayes from Scratch

## What is Bayes Theroem and the Naive Bayes assumption?

The basic idea behind Bayes theorem is that the probability of a hypothesis (H) given some evidence (E) is equal to the probability of the evidence given the hypothesis (P(E|H)) times the probability of the hypothesis (P(H)) divided by the probability of the evidence (P(E)). This is written mathematically as:

$$P(H|E) = \frac{P(E|H) * P(H)} {P(E)} $$

Bayes theorem is widely used in a variety of applications, including machine learning, where it is used to update the probabilities of different hypotheses based on new evidence.

The Naive Bayes assumption is a simplifying assumption that is often made when using Bayes theorem in machine learning. It assumes that the features (i.e., the independent variables) in the data are independent of each other given the label (i.e., the dependent variable). This assumption allows the probability of the label given the features to be calculated as the product of the individual probabilities of each feature given the label.
