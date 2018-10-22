---
title: Learning Machine Learning, session 1
date: "2018-10-07 19:17"
category: Dry-Lab
---


The first session is based on one of my early classes of 2016, available [on line](https://anaraven.bitbucket.io/slides/2016/cmb2/Class3.html).

To get the full idea, I recommend that, before looking at the class, you first read the short story “Funes the Memorious” (by Argentine writer Jorge Luis Borges). You can find it on the web. There is even a PDF in Turkish language. Google “Funes ve Sonsuz Bellek” and look on pages 111-119.

After reading it, *do you want to have perfect memory?* Why?

# Project library
I will keep a small library of relevant books on my office's bookshelf.
These are some of the books:

![Books with the theory.](https://lh3.googleusercontent.com/r62IFkQHy5JKLArIjAZNX2kbhHtjYaiOcFFE-wEaBJElesBjxIdF-H3UaDHklnToENPVy19AvApPqI4SncZELc8cDn6IlnowmoEixZQJB_Z7ZD3BNK5swzTqVQgGluVTkg2962XUA40=w2400)

![Good book in plain Python.](https://lh3.googleusercontent.com/_Zub5EZmjkasFV_uAmopLDZGvh8oHPB9XJK0DwU0eDxVly3xbf9P8cxvpL7uv-UE3Nw7ipYG-1HnTsho6UDZEpbB2xLk2_IP6XRph9CHmB5aGVANqgzbwJfZVlwPmtQqqcYQQe46aYM=w2400){height=300px}

![Also using Python, and _ad-hoc_ libraries such as NumPy, Pandas, and Scikit-learn.](https://lh3.googleusercontent.com/im4hfTJWWeHT2tIJjUu_wZznyw__6DkcO27RiRKQP2ECXUrRmmXkYD96K10FH7hP1xDlhumCO6iks3POPIQnCqkwOp-N-wbsB-JGDOhHGSNpPAvhbMew6B9Lv6jV9B7flzO9yCXwh7g=w2400)

The idea we discuss in these slides is that *learning is forgetting*. Not in the sense of forgetting memories, but forgetting details. In the Borges' story, the protagonists has perfect memory and cannot forget any detail. Therefore, Borges concludes, he is incapable of thinking, or of making abstractions.

In this sense, machine learning is programming computers so they can ignore some details and make abstractions, in the sense of *classes of objects*. If a computer can recognize a dog in a picture, then in some sense the computer has learned the concept of *dog*, very much like the Platonic model of *idea*.

We spoke about the two main branches of machine learning: supervised and unsupervised classification. In the first cases we start with some examples of the classes, such as pictures that we know include dogs, and train the computer to find a rule to recognize them. In the second case, we just train with a lot of pictures and let the computer figure out which are the classes.

# Datasets
The main reason why *machine learning* has returned to the forefront^[In the 80's there was a lot of development on artificial intelligence, but the limited computing power and data availability turned it out-of-fashion.] is the easy access to massive data.

One data source that we mentioned was the [Netflix Prize](http://www.netflixprize.com), a contest to improve the recommendation system of this movie provider. The winning team got one million dollar, and the runner up got new business proposals for several times that figure. Recommendation systems are the base of many business models, including Amazon.com, Google and Facebook. These companies are really pushing the science of machine learning, and we will indeed use some of their tools. It is also possible that we will use their infrastructure, in the form of *cloud servers*. At least, that is the idea.

In our case we will try to use Molecular Biology data, or data for any other scientific question. In particular there is a lot of gene expression data from microarray or RNAseq experiments. We can also use genetic data, if we code it properly.

# GitHub
Can Kandemir, one of our co-learners, proposed that we use GitHub for our code. I agree with that idea, it is how things are done today. He will prepare a talk for one of the future sessions.

By coincidence, I had just listened to a podcast that spoke about GitHub and his impact. The speaker is Seth Godin, one of the thinkers I'm following nowadays. The podcast episode also touches other subjects about how technology is changing our world, including Science. You can hear the podcast episode at <https://www.akimbo.me/blog/s-2-e-9-distribution-and-cultural-destiny>.

