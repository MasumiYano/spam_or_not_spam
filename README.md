# Spam or Not Spam
## Index
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Limitations](#limitations)
- [License](#license)
- [Contact](#contact)

## Introduction
<a name="introduction"></a>
In this project, I trained machine learning model to determine wheter email is spam or not using Random Forest Classifier from scikit learn.

## Methodology
<a name="methodology"></a>
### Overview of Random Forest
Random forest is a one of the most famous supervised machine learning algorithm where it combines the output of multiple [decision trees](#decision_trees) to reach a single result. 
This estimator is famous due to its capability of tacking both classification and regression problems effectively. It trained throught bagging, which is an ensemble meta-algorithm that 
improves the accuracy of machine learning algorithms. This algorithm establishes the outcome based on the predicitons of the decision trees. This algorithm successed to avoid the limitation of a decision tree algorithm.
It reduce the overfitting od datasets and increases precision. The outcome is determined by majority-vote.

### Decison Trees
<a name="decision_trees"></a>
To understand the random forest algorithm, we have to take a look at how decision trees are working. It is a building blocks of a random forest algorithm. 
Decision tree is a tree-like structure, and contains three components; decision nodes, leaf nodes, and root node. Decision tree divides a training dataset into
branches, and keep dividing until the node cannot be divided futher (attained leaf node). This image from [Wikipedia](https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FDecision_tree&psig=AOvVaw0oLruMy1tA3eG7rC9hkdaq&ust=1705955695951000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCKCDyKyq74MDFQAAAAAdAAAAABAD) illustrates the idea of decision tree better. 

## Limitation
<a name="limitations"></a>
The biggest limitation of this tranined model is that the accuracy of this model is low, as its best is 93.8%. Also, we reduced the dimensionality down to 8 from 52. However, if we reduced it even further, the accuracy of the model 
got progressively lower and lower. Despite the sucess of reducing the dimensionality down to 15% of actual features, this is still a high-dimensionality in my personal opinion. 

## License
MIT License obtained

## Contact
Email: [masumi76@uw.edu](masumi76@uw.edu)
