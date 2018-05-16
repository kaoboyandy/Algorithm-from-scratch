
# Selection Of Machine Learning Algorithms From Scratch

### This post aims to demonstrate the absolute bones of various algorithms without using any external APIs. As such most of the codes are written in numpy or python utilizing classes and functions. 

### By doing so, this will give you a sense of what's happening when you use an algorithm from sklearn, and hopefully demonstrate how you can learn more by trying to implement them yourself.

<br>
#### It is often known that coding from scratch is the most in-depth way of learning a model as it requires:
  1) A complete understanding of the algorithm

  2) In-Depth knowledge of the programming languages

  3) Consolidation of knowledge from theory to practical and thus knowing the applicable variations

# PCA

Dimensionality reduction is useful for two reason:

* It makes it easier to view higher dimensional data
* Can reduce computational cost of running learning algorithms.

PCA or principal compenent analysis, is a dimensionality reduction technqiue that allows us to more easily visulize higher dimensional data. This is achieved by applying a linear transform to the data, we'll cover more on linear transformation later. For now think of it as rotating it so we can view it from the best angle.  The way PCA finds the new axis for the rotation is by looking for the directions of maximum variance.

# K Means Clustring

k-means clustering is a method of vector quantization, originally from signal processing, that is popular for cluster analysis in data mining. k-means clustering aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster. With K-Mean means the goal is to seperate our examples in $ k $ clusters $ C = \{C_1,C_2,...,C_k \} $. 


# Decision Tree

A decision tree is a decision support tool that uses a tree-like graph or model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. It is one way to display an algorithm that only contains conditional control statements.

Decision trees are commonly used in operations research, specifically in decision analysis, to help identify a strategy most likely to reach a goal, but are also a popular tool in machine learning.

# Backpropagation

Backpropagation is a method used in artificial neural networks to calculate a gradient that is needed in the calculation of the weights to be used in the network. It is commonly used to train deep neural networks, a term referring to neural networks with more than one hidden layer.

The algorithm generally involves two phases:



### Phase 1: Forward
![image.png](attachment:image.png)

### Phase 2: Weight update
![image.png](attachment:image.png)

__[Image from Quora](https://www.quora.com/What-is-the-best-visual-explanation-for-the-back-propagation-algorithm-for-neural-networks)__
