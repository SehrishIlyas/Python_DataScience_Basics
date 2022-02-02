# Types of Machine Learning

## Supervised Learning

### Logistic Regression
Logistic regression models a relationship between predictor variables and a categorical response variable.  Logistic regression helps us estimate a probability of falling into a certain level of the categorical response given a set of predictors.

### K-Nearest Neighbors 
A family of techniques that can be used for regression or classification
- As a nonparametric learning algorithm:
    - It is not restricted to a fixed no of parameters
- A simple function of the training data
     - When we want to produce output y for input x, we find k-nearest neighbors to x in the training data X. We then return the average of the corresponding y values in the training set

### Support Vector Machines
It is a classification algorithm. In the support vector machine, we use a hyperplane to classify the dependent variable when we have only two dependent variables.
An influential approach to supervised learning. This model is similar to logistic regression in that it is driven by a linear function w<sup>T</sup>x+b.
Unlike logistic regression, SVM does not provide probabilities, but only outputs class identity
 - SVM predicts positive class when w<sup>T</sup>x+b > 0
 - SVM predicts negative class when w<sup>T</sup>x+b < 0

### Kernel SVM
A key innovation associated with SVM 

### Decision Tree
 It breaks down the dataset into a smaller subset and associate decision with it. As a result, we get a tree with decision nodes and leaf nodes. A learning algorithm that breaks the input space into regions and has separate parameters for each region.

## Unsupervised Learning

### K-Means Clustering:
Clustering your data points or text into a character “K” of mutually exclusive clusters. A lot of the complexity surrounds how you should pick the appropriate number for K.

## Hierarchical Clustering:
Clustering your data points into parent & child clusters. You might split your customers between younger & older ages & then split each of those groups into their clusters as well.

## Probabilistic Clustering:
Clustering your data points or text into clusters on a probabilistic scale.

## Reinforcement Learning Algorithms
There are three approaches to implement a Reinforcement Learning algorithm.

### Value-Based:
In a value-based Reinforcement Learning method, you should try to maximize a value function V(s). In this method, the agent is expecting a long-term return of the current states under policy π.

### Policy-based:
In a policy-based RL method, you try to come up with such a policy that the action performed in every state helps you to gain maximum reward in the future.

### Model-based:
In this Reinforcement Learning method, you need to create a virtual model for each environment. The agent learns to perform in that specific environment.