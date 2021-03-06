
# Dota hero clustering with k-means

## What is k-means clustering?
K-means clustering is an unsupervised machine learning method which attempts to group a population into a specified number of clusters based on similarity metrics. When an instance of the algorithm is created, cluster centroids are randomly initialized based on the desired number of clusters. Each observation is assigned a cluster based on how similar its values are to those of the centroid.  At each iteration, the location of each centroid is recomputed and observations are reallocated if necessary. This continues until the locations of the centroids and cluster allocations no longer change. 
The algorithm is often applied to unlabeled data in order to uncover structure, but in this case we do have the true category labels, so they were used to evaluate the model's performance.

## Implementation and libraries
This task was carried out using pandas, matplotlib and seaborn, and two modules from scikit-learn, KMeans and StandardScaler

## The task
The task at hand was to use k-means clustering to group Dota heroes into 3 clusters based on their attributes. Given that the true category membership of the heroes is known, the performance of the k-means algorithm could be evaluated. High accuracy was achieved after exploring the dataset and trimming down attributes. 

## Dataset
The dataset is publicly available from https://www.kaggle.com/datasets/prokid1911/dota-2-all-hero-data-727d. Many thanks to Mridul Gupta for putting this together

## Repository contents
This repository consists of a .py file and an .ipynb file as well as the dataset (also linked above)

## Status
This project is complete. I have interest in pursuing further Dota-related machine learning projects, namely clustering based on the many hero roles instead of the 3 hero categories, which will be a much more complicated task
