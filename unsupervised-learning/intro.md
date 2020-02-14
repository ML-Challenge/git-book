# Introduction

#### UNSUPERVISED LEARNING

In _unsupervised learning_, as you might guess, the training data is unlabeled. The system tries to learn without a teacher.

Here are some of the most important unsupervised learning algorithms:

* Clustering
  * K-Means
  * DBSCAN
  * Hierarchical Cluster Analysis \(HCA\)
* Anomaly detection and novelty detection
  * One-class SVM
  * Isolation Forest
* Visualization and dimensionality reduction
  * Principal Component Analysis \(PCA\)
  * Kernel PCA
  * Locally Linear Embedding \(LLE\)
  * t-Distributed Stochastic Neighbor Embedding \(t-SNE\)
* Association rule learning
  * Apriori
  * Eclat

For example, say we have a collection of customers with a variety of characteristics such as age, location, and financial history, and we wish to discover patterns and sort them into clusters. Or perhaps we have a set of texts, such as Wikipedia pages, and we wish to segment them into categories based on their content. This is the world of unsupervised learning, called as such because we are not guiding, or supervising, the pattern discovery by some prediction task, but instead uncovering hidden structure from unlabeled data. Unsupervised learning encompasses a variety of techniques in machine learning, from clustering to dimension reduction to matrix factorization. In this week, we'll learn the fundamentals of unsupervised learning and implement the essential algorithms using `scikit-learn` and `scipy`. We will learn how to cluster, transform, visualize, and extract insights from unlabeled datasets, and end the course by building a recommender system to recommend popular musical artists.

