# Types of Machine Learning

### Supervised learning

The computer is presented with example inputs and their desired outputs, given by a "teacher", and the goal is to learn a general rule that maps inputs to outputs. This type of learning includes classification, regression, ranking.

### Unsupervised learning

no labels are given to the learning algorithm, leaving it on its own to find structure in its input. Unsupervised learning can be a goal in itself \(discovering hidden patterns in data\). This type of learning includes: clustering, dimensionality reduction.

### Reinforcement learning

This is somewhere between supervised and unsupervised learning. The algorithm gets told when the answer is wrong but does not get told how to correct it. It has to explore and try out different possibilities until it works out how to get the answer right. Reinforcement learning is sometime called learning with a critic because of this monitor that scores the answer but does not suggest improvements.

###  Evolutionary learning

Biological evolution can be seen as a learning process: biological organisms adapt to improve their survival rates and chance of having offspring in their environment. Weill look at how we can model this in a computer. using an idea of fitness. which corresponds to a score for how good the current solution is.

Another categorization of machine learning tasks arises when one considers the desired output of a machine-learned system.

### Classification

In classification, inputs are divided into two or more classes, and the learner must produce a model that assigns unseen inputs to one \(or multi-label classification\) or more of these classes. This is typically tackled in a supervised way. Spam filtering is an example of classification, where the inputs are email \(or other\) messages and the classes are "spam" and "not spam".

### Regression

In regression, also a supervised problem, the outputs are continuous rather than discrete. Estimating the relationships between variables by optimizing the reduction of error.

![](../.gitbook/assets/image%20%281%29.png)

### Clustering

In clustering, a set of inputs is to be divided into groups. Unlike in classification, the groups are not known beforehand, making this typically an unsupervised task.

### Density Estimation

Density estimation finds the distribution of inputs in some space.

### Dimensionality Reduction

Dimensionality reduction simplifies inputs by mapping them into a lower-dimensional space. Topic modeling is a related problem, where a program is given a list of human language documents and is tasked to find out which documents cover similar topics.

