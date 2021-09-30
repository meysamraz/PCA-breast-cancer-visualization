# PCA breast cancer visualization and clustring 
deploy PCA (Principal component analysis) on breast cancer data from [scikit-learn](https://scikit-learn.org/) 

![alt text](https://github.com/meysam810/PCA-breast-cancer-visualization/blob/master/plot.png")

## Overview

### 1) Load Data from scikit-learn

### 2) Scale Data using StandardScaler

### 3) Deploy PCA

### 4) Visualize  Deployment  



# What is PCA?
Basically, PCA is a linear dimensionality reduction technique (algorithm) that transforms a set of correlated variables (p) into smaller k (k<<p) number of uncorrelated variables called principal components while retaining as much of the variation of the original data as possible. In the context of Machine Learning (ML), PCA is an unsupervised machine learning algorithm in which we find important variables that can be useful for further regression, clustering and classification tasks.

# How PCA works?
PCA considers the correlation among variables. If the correlation is very high, PCA attempts to combine highly correlated variables and finds the directions of maximum variance in higher-dimensional data. The following image shows that the first principal component (PC1) has the largest possible variance and is orthogonal to PC2 (i.e. uncorrelated).

![alt text](https://miro.medium.com/max/633/1*kUnPhARG0D2zgrRyRPqDXQ.png")

# Libraries used in the project

- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [sklearn](https://scikit-learn.org/stable/)

