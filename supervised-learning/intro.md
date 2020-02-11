# Introduction

### What Is Machine Learning?

Machine Learning is the science \(and art\) of programming computers so they can _learn from data_.

Here is a slightly more general definition:

> \[Machine Learning is the\] field of study that gives computers the ability to learn without being explicitly programmed.
>
> Arthur Samuel, 1959

And a more engineering-oriented one:

> A computer program is said to learn from experience _E_ with respect to some task _T_ and some performance measure _P_, if its performance on _T_, as measured by _P_, improves with experience _E_.
>
> Tom Mitchell, 1997

Your spam filter is a Machine Learning program that, given examples of spam emails \(e.g., flagged by users\) and examples of regular \(nonspam, also called “ham”\) emails, can learn to flag spam. The examples that the system uses to learn are called the _training set_. Each training example is called a _training instance_ \(or _sample_\). In this case, the task _T_ is to flag spam for new emails, the experience _E_ is the _training data_, and the performance measure _P_ needs to be defined; for example, you can use the ratio of correctly classified emails. This particular performance measure is called _accuracy_, and it is often used in classification tasks.

If you just download a copy of Wikipedia, your computer has a lot more data, but it is not suddenly better at any task. Thus, downloading a copy of Wikipedia is not Machine Learning.

### Types of Machine Learning Systems

There are so many different types of Machine Learning systems that it is useful to classify them in broad categories, based on the following criteria:

* Whether or not they are trained with human supervision \(supervised, unsupervised, semisupervised, and Reinforcement Learning\)
* Whether or not they can learn incrementally on the fly \(online versus batch learning\)
* Whether they work by simply comparing new data points to known data points, or instead by detecting patterns in the training data and building a predictive model, much like scientists do \(instance-based versus model-based learning\)

#### Supervised/Unsupervised Learning

Machine Learning systems can be classified according to the amount and type of supervision they get during training. There are four major categories: supervised learning, unsupervised learning, semisupervised learning, and Reinforcement Learning.

#### SUPERVISED LEARNING

In _supervised learning_, the training set you feed to the algorithm includes the desired solutions, called _labels._

A typical supervised learning task is _classification_. The spam filter is a good example of this: it is trained with many example emails along with their _class_ \(spam or ham\), and it must learn how to classify new emails.

Another typical task is to predict a _target_ numeric value, such as the price of a car, given a set of _features_ \(mileage, age, brand, etc.\) called _predictors_. This sort of task is called _regression_ _._ To train the system, you need to give it many examples of cars, including both their predictors and their labels \(i.e., their prices\).

