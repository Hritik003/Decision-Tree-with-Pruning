# Decision-Tree-with-Pruning
Decision Tree Algorithm in Python using NumPy and Pandas.

## Overview of the Implementation

The Decision Tree algorithm implemented here can accommodate customizations in the maximum decision tree depth, the minimum sample size, the number of random features if the users want to choose some d features randomly without replacement when splitting a node, and the number of random splits, if the users want to split a node for some s times and choose the best split among these s, splits instead of choosing the best split among all potential splits of the node.

The algorithm can also work with datasets containing categorical data natively, so it requires those datasets to be preprocessed such as converting ordinal data into integers. After converting all categorical string values in a dataset to integers, a user can use that dataset with the algorithm. 

## Steps followed:
1. Loading the Data
2. Data Pre-processing
3. Discretization
4. Label Encoding
5. Reduced Error Pruning
6. Test results

## Decision Tree

![decision tree image](https://github.com/Hritik003/Decision-Tree-with-Pruning/assets/73677045/783d0e8e-8a54-4534-83f3-400b25ee5afa)
