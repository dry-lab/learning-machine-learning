# Unsupervised Learning in Python

Learn how to cluster, transform, visualize, and extract insights from unlabeled datasets using `scikit-learn` and `scipy`.

### Prerequisites

-   [Intro to Python for Data Science](/courses/intro-to-python-for-data-science)
-   [Intermediate Python for Data Science](/courses/intermediate-python-for-data-science)
-   [Statistical Thinking in Python (Part 1)](/courses/statistical-thinking-in-python-part-1)

### Datasets

-   [Company stock price movements](https://assets.datacamp.com/production/course_2072/datasets/company-stock-movements-2010-2015-incl.csv)
-   [Eurovision 2016](https://assets.datacamp.com/production/course_2072/datasets/eurovision-2016.csv)
-   [Fish measurements](https://assets.datacamp.com/production/course_2072/datasets/fish.csv)
-   [Grains](https://assets.datacamp.com/production/course_2072/datasets/Grains.zip)
-   [LCD digits](https://assets.datacamp.com/production/course_2072/datasets/lcd-digits.csv)
-   [Musical artists](https://assets.datacamp.com/production/course_2072/datasets/Musical%20artists.zip)
-   [Wikipedia articles](https://assets.datacamp.com/production/course_2072/datasets/Wikipedia%20articles.zip)
-   [Wine](https://assets.datacamp.com/production/course_2072/datasets/wine.csv)

# Course Description

Say you have a collection of customers with a variety of characteristics such as age, location, and financial history, and you wish to discover patterns and sort them into clusters. Or perhaps you have a set of texts, such as wikipedia pages, and you wish to segment them into categories based on their content. This is the world of unsupervised learning, called as such because you are not guiding, or supervising, the pattern discovery by some prediction task, but instead uncovering hidden structure from unlabeled data. Unsupervised learning encompasses a variety of techniques in machine learning, from clustering to dimension reduction to matrix factorization. In this course, you\'ll learn the fundamentals of unsupervised learning and implement the essential algorithms using scikit-learn and scipy. You will learn how to cluster, transform, visualize, and extract insights from unlabeled datasets, and end the course by building a recommender system to recommend popular musical artists.

Learn how to cluster, transform, visualize, and extract insights from unlabeled datasets using scikit-learn and scipy.

# Course Outline

## Clustering for dataset exploration

Learn how to discover the underlying groups (or \"clusters\") in a dataset. By the end of this chapter, you\'ll be clustering companies using their stock market prices, and distinguishing different species by clustering their measurements.

-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=1)

### Unsupervised learning

-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=2)

### How many clusters?
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=3)

### Clustering 2D points
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=4)

### Inspect your clustering
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=5)

### Evaluating a clustering
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=6)

### How many clusters of grain?
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=7)

### Evaluating the grain clustering
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=8)

### Transforming features for better clusterings
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=9)

### Scaling fish data for clustering
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=10)

### Clustering the fish data
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=11)

### Clustering stocks using KMeans
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/clustering-for-dataset-exploration?ex=12)

### Which stocks move together?

## 2. Visualization with hierarchical clustering and t-SNE

In this chapter, you\'ll learn about two unsupervised learning techniques for data visualization, hierarchical clustering and t-SNE. Hierarchical clustering merges the data samples into ever-coarser clusters, yielding a tree visualization of the resulting cluster hierarchy. t-SNE maps the data samples into 2d space so that the proximity of the samples to one another can be visualized.

-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=1)

### Visualizing hierarchies
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=2)

### How many merges?
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=3)

### Hierarchical clustering of the grain data
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=4)

### Hierarchies of stocks
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=5)

### Cluster labels in hierarchical clustering
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=6)

### Which clusters are closest?
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=7)

### Different linkage, different hierarchical clustering!
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=8)

### Intermediate clusterings
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=9)

### Extracting the cluster labels
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=10)

### t-SNE for 2-dimensional maps
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=11)

### t-SNE visualization of grain dataset
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/visualization-with-hierarchical-clustering-and-t-sne?ex=12)

### A t-SNE map of the stock market

## 3. Decorrelating your data and dimension reduction

Dimension reduction summarizes a dataset using its common occuring patterns. In this chapter, you\'ll learn about the most fundamental of dimension reduction techniques, \"Principal Component Analysis\" (\"PCA\"). PCA is often used before supervised learning to improve model performance and generalization. It can also be useful for unsupervised learning. For example, you\'ll employ a variant of PCA will allow you to cluster Wikipedia articles by their content!

-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=1)

### Visualizing the PCA transformation
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=2)

### Correlated data in nature
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=3)

### Decorrelating the grain measurements with PCA
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=4)

### Principal components
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=5)

### Intrinsic dimension
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=6)

### The first principal component
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=7)

### Variance of the PCA features
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=8)

### Intrinsic dimension of the fish data
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=9)

### Dimension reduction with PCA
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=10)

### Dimension reduction of the fish measurements
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=11)

### A tf-idf word-frequency array
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=12)

### Clustering Wikipedia part I
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/decorrelating-your-data-and-dimension-reduction?ex=13)

### Clustering Wikipedia part II

## 4. Discovering interpretable features

In this chapter, you\'ll learn about a dimension reduction technique called \"Non-negative matrix factorization\" (\"NMF\") that expresses samples as combinations of interpretable parts. For example, it expresses documents as combinations of topics, and images in terms of commonly occurring visual patterns. You\'ll also learn to use NMF to build recommender systems that can find you similar articles to read, or musical artists that match your listening history!

-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=1)

### Non-negative matrix factorization (NMF)
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=2)

### Non-negative data
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=3)

### NMF applied to Wikipedia articles
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=4)

### NMF features of the Wikipedia articles
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=5)

### NMF reconstructs samples
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=6)

### NMF learns interpretable parts
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=7)

### NMF learns topics of documents
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=8)

### Explore the LED digits dataset
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=9)

### NMF learns the parts of images
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=10)

### PCA doesn\'t learn parts
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=11)

### Building recommender systems using NMF
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=12)

### Which articles are similar to \'Cristiano Ronaldo\'?
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=13)

### Recommend musical artists part I
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=14)

### Recommend musical artists part II
-   [](https://campus.datacamp.com/courses/unsupervised-learning-in-python/discovering-interpretable-features?ex=15)

### Final thoughts
[View Chapter Details]() [Play Chapter Now](/users/sign_up?redirect=%2Fcourses%2Funsupervised-learning-in-python%2Fchapters%2F5851%2Fcontinue)

# Course Instructor
Benjamin Wilson

Director of Research at lateral.io

Ben is a machine learning specialist and the director of research at lateral.io. He is passionate about learning and has worked as a data scientist in real-time bidding, e-commerce, and recommendation. Ben holds a PhD in mathematics and a degree in computer science.


[Start Course For Free](/users/sign_up?redirect=%2Fcourses%2Funsupervised-learning-in-python%2Fcontinue)

# Learn

-   [Courses](/courses)
-   [Skill Tracks](/tracks/skill)
-   [Career Tracks](/tracks/career)
-   [Pricing](/pricing)
-   [Become an Instructor](/create)

# Resources

-   [Community](/community/)
-   [RDocumentation](https://www.rdocumentation.org)
-   [Course Editor](/teach/)
-   [Upcoming Courses](https://trello.com/b/BLplifUB/datacamp-course-roadmap)
-   [Support](https://support.datacamp.com)

DataCamp offers interactive R, Python, Sheets, SQL and shell courses. All on topics in data science, statistics and machine learning. Learn from a team of expert teachers in the comfort of your browser with video lessons and fun coding challenges and projects.

[About the company](/about)

-   -   -   -

© 2018 DataCamp Inc.

