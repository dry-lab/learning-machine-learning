---
title: Learning Machine Learning
subtitle: >-
  With applications in Molecular Biology, Physics, and other Sciences
date: '2018-10-06 13:25'
category: Dry-Lab
alias: Machine Workshop
---
> We have a lot of data. How can we understand it? How can we extract meaningful
  insight from it? In many places around the globe, researchers in academia and
  industry are using <em>Machine Learning</em> to answer these questions. Artificial
  Intelligence tools provide big advantages for the scientist that use them.
  This workshop (also known as "The Machine Atelier") aims to update us into the current state-of-the-art
  computational and mathematical tools that are useful in Molecular Biology,
  Physics, and other sciences.
 
The challenge for contemporary science is moving from *data production* to *knowledge discovery*. Ideas such as *Data Mining* and *Big Data* are popular today. We can track their origin to more than 30 years ago, when Artificial Intelligence and Neural Networks were being developed. Today computers are much more powerful (by several orders of magnitude) and data is abundant. Collecting and storing data is cheap and easy.

Although these techniques can be used in a wide variety of subjects, we will focus on scientific applications, mainly in Molecular Biology and in Physics

# Work plan

![The textbook we will follow](https://covers.oreillystatic.com/images/0636920052289/lrg.jpg)


We meet every Monday at 17:00 in the MBG II room, at the Science Faculty. Bring your computer.
We will use R and Python, and discuss the mathematics behind the tools.

The idea is to follow the book ["Hands-On Machine Learning with Scikit-Learn and TensorFlow"](http://shop.oreilly.com/product/0636920052289.do)
by Aurélien Géron, **and** some exercises in R. We will also discuss some of the underlaying mathematical theory, so we can really *understand* the tools.

You can preview the book on [Google Books](https://books.google.com.tr/books?id=khpYDgAAQBAJ&lpg=PP1&pg=PP1#v=onepage&q&f=false).
I will keep a little library of books on the bookshelf in my office, so anybody can check them. They include books about Python and computing techniques, some math books about Pattern Recognition and Classification, and something about the ethical and philosophical implications of Machine Learning.

## Topics
This is the initial plan. We may add more topics later, inspired by the textbook [table of contents](book-toc.html).

+ *Unsupervised classification*, also known as *Clustering* or *Pattern recognition*
    + K-means
        + distance
    + Self Organized maps (Kohonen networks)
    + Hierarchical clustering
        + average, simple, and complete linkage
+ _Supervised classification_, also known as _Machine Learning_ or _Pattern classification_
    + K-nearest neighbors
    + Bayesian classification
    + Linear models
        + Probit
        + Logit
    + Classification and Regression Trees
    + Support Vector Machines
    + Neural Networks

## Tools
We will use publicly available machine learning libraries written for Python including:

- Scikit-learn: general purpose machine learning library
- Keras: deep learning Python library
- Tensorflow
