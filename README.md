
# Unsupervised Learning

## Introduction

In this lesson, you'll get a high level overview of unsupervised learning, an entire class of algorithms in machine learning. To date, you've only seen examples of supervised learning tasks such as regression and classification. As the name implies,unsupervised learning is a bit different then these tasks. In supervised learning, you define an X and y and the algorithm attempts to generalize this transformation in order to predict y given X. In unsupervised learning, you do not define an X or y. Instead, you feed in a given dataset and the unsupervised learning algorithm returns some new representation of the data based on the structure and patterns within the data itself.

## Objectives

You will be able to:

* Understand and explain the challenges inherent in unsupervised learning
* Identify real-world use cases for unsupervised learning
* Compare and Contrast Supervised and unsupervised learning, and identify algorithms that belong to each


## Supervised versus Unsupervised Learning


The main difference between Supervised and unsupervised learning are their goals. Supervised Learning needs concrete, ground-truth labels to train models that answer very specific questions. Unsupervised learning differs in that the task it is trying to accomplish is much less well-defined&mdash;it can usually be summed up as "are there any natural patterns in this data that are recognizable?"  To illustrate this, assume that you have a basket of various different kinds of fruit. A supervised learning task would be building an apple classifier that tells us if a given fruit is or isn't an apple, based on the size, shape, color, texture, taste, and any other data that you've encoded for each piece of fruit. A similar unsupervised learning task would be to analyze only the features, and sort them into groups without being told what type of fruit each was. In general, supervised learning uses data to accomplish a clear task while unsupervised learning has no clear task, but is instead used for analysis.


## Unsupervised Learning Tasks

The two most common unsupervised learning tasks are clustering and dimensionality reduction. Clustering groups data into homogeneous groups, where members share common traits. Dimensionality reduction attempts to reduce the overall number of features of a dataset while preserving as much information as possible. With that, let's take a deeper look into some general notes on each.

### Clustering

There are a few different kinds of clustering algorithms, but they all do the same thing&mdash;finding different ways to group a dataset based on patterns in the data.  One common use-case for clustering is market segmentation. In market segmentation, you would try to decompose an audience into subsets for more precise targeting for business purposes such as advertising. Even though there's no way to verify that these groups are correct, in practice it usually does quite well, often providing useful subgroups which can then be individually examined.

<img src='images/kmeans.gif'>

[gif by David Sheehan](https://dashee87.github.io/data%20science/general/Clustering-with-Scikit-with-GIFs/)

### Dimensionality Reduction

The most common dimensionality reduction algorithm is Principal Component Analysis (PCA). Dimensionality reduction algorithms work by projecting data from it's current N-dimensional subspace into a smaller subspace, while losing as little information as possible in the process. Dimensionality reduction algorithms still lose _some_ information, but you can quantify this information loss to make an informed decision about the number of dimensions reduced versus the overall information lost. Dimensionality Reduction algorithms are a must-have in any data scientist's toolbox, because they provide a way for us to deal with the **Curse of Dimensionality**. The curse of dimensionality is a key concept as datasets scale. In short, as the number of features in a dataset increases, the processing power and search space required to optimize a given machine learning algorithm explodes exponentially. As this often creates intractable problems that are infeasible to solve computationally, dimensionality reduction techniques such as PCA can be an essential preprocessing technique.

<img src='images/pca.gif'>

[gif by amoeba](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues/140579#140579)

## Summary

In this lesson, you explored the differences between supervised and unsupervised learning. You also learned about the types of problems we can solve with unsupervised learning, including clustering and dimensionality reduction.



```python

```
