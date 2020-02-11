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

For example, say you have a lot of data about your blog’s visitors. You may want to run a _clustering_ algorithm to try to detect groups of similar visitors. At no point do you tell the algorithm which group a visitor belongs to: it finds those connections without your help. For example, it might notice that 40% of your visitors are males who love comic books and generally read your blog in the evening, while 20% are young sci-fi lovers who visit during the weekends. If you use a _hierarchical clustering_ algorithm, it may also subdivide each group into smaller groups. This may help you target your posts for each group.

