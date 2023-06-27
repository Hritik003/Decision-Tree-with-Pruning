# Decision-Tree-with-Pruning
Decision Tree Algorithm in Python using NumPy and Pandas.

## Overview of the Implementation

The Decision Tree algorithm implemented here can accommodate customizations in the maximum decision tree depth, the minimum sample size, the number of random features if the users want to choose some d features randomly without replacement when splitting a node, and the number of random splits, if the users want to split a node for some s times and choose the best split among these s, splits instead of choosing the best split among all potential splits of the node.

The algorithm can also work with datasets containing categorical data natively, so it requires those datasets to be preprocessed such as converting ordinal data into integers. After converting all categorical string values in a dataset to integers, a user can use that dataset with the algorithm. 

## Motivation

Building such prediction models can aid in our understanding of a nation's population and the numerous elements influencing economic growth.
Such variables are something that governments can comprehend and work to address, which will help the nation thrive.


## Steps followed:
1. Loading the Data
2. Data Pre-processing
3. Discretization
4. Label Encoding
5. Reduced Error Pruning
6. Test results

## Decision Tree

![decision tree image](https://github.com/Hritik003/Decision-Tree-with-Pruning/assets/73677045/783d0e8e-8a54-4534-83f3-400b25ee5afa)

## Before-Pruning Graph

![graph](https://github.com/Hritik003/Decision-Tree-with-Pruning/assets/73677045/31fad18d-ce47-4674-b855-76a422f535da)

## Post-Pruning Graph
![download](https://github.com/Hritik003/Decision-Tree-with-Pruning/assets/73677045/5e46ebdb-b442-4535-8230-8981739c33bd)



