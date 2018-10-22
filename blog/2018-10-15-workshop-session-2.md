---
title: 'Learning Machine Learning, session 2'
date: '2018-10-15 10:16'
category: Dry-Lab
published: true
featured: false
---

::: {.marginnote .smaller}
## Keywords
+ Git
+ Github
+ Kmeans clustering
+ Gene expression Datasets
:::

The second session of the workshop focused mainly on collaboration tools that we will use, and we saw our first machine learning application.

# Git and GitHub

Can Kandemir made a nice presentation, available [on line](https://docs.google.com/presentation/d/1QMP_5i9T_ntjLcMhm9o3rF26IBKvdpPKe-EVKcLE6lY/edit?usp=sharing). Faruk Üstünel pointed us to this [Udemy online course](https://www.udemy.com/git-started-with-github/learn/v4/content). Their explanation is very clear.

For my side I showed some examples using RStudio *git* interface. In my experience it is easy to start with *git* using a graphical interface, but the real deal comes with the command line tools. It is a long subject, but we do not need to be experts. 

There is plenty of material on line. Two pages that I personally like are ["Introduction to Git"](https://dzone.com/articles/intro-git) and ["Getting started with Git"](https://dzone.com/refcardz/getting-started-git?chapter=1). The last one is a Reference card, that can be printed. The page is free but you have to register. Maybe that is not a good idea, so feel free to find other material, and share with the rest of us.

To begin, I've created a public repository for us. You can see it at <https://github.com/dry-lab/learning-machine-learning>. Go there, create an account, clone it, and start making mistakes.

Remember, this workshop is for everybody to learn, and the best way to learn is to teach. Believe me, I know a little bit about teaching and learning.

# Kmeans
The first example we saw used gene expression data for *E. coli*, taken from [Many Microbe Microarrays Database (M3D)](http://m3d.mssm.edu/norm/). We downloaded the last version, which has an approximate value of 2 million US dollars, although it is 10 years old.

We loaded this data in R and we did a quick clustering using the `kmeans()` function.

For the next session we have two challenges:

1. Doing k-means in python
2. Finding the _"best value of **k**"_

See you there!

<style>
.marginnote h2 {
    margin: 0;
    padding: 0;
}
.marginnote ul, .marginnote p {
    margin-top: 0;
}
figcaption {
    width: 95%;
    padding-bottom: 1.2em;
    text-align: right;
}
</style>
