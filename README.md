# **Analysis of Voter Abstention on Brazil's Presidential Elections through Data Clustering**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/heitornolla/voter-absention-clustering/blob/main/jupyter-notebook/notebook.ipynb)

**Disclaimer:** _This is a personal project intended for educational purposes only_

This project performs an unsupervised learning analysis on official voter abstention justification data from Brazilian elections. Using clustering techniques, we aim to uncover patterns in voter abstention across demographic and geographic groups.

# Overview

Data preprocessing, encoding, and normalization techniques are applied to prepare the dataset, followed by clustering using K-Means and visualization with PCA. 

# Project Steps

## 1. **Data Loading & Cleaning**
   - Load .csv dataset.
   - Drop irrelevant columns.
   - Map binary values to numeric format.
   - Handle unknown or missing values.

## 2. **Encoding & Scaling**
   - Ordinal encoding of ordered categories.
   - One-hot encoding of nominal categorical variables.
   - Standard scaling of numeric features.

## 3. **Clustering**
   - Apply Elbow Method to understand optimal amount of clusters
   - Apply KMeans clustering with the Elbow Method's output.

## 4. **Cluster Analysis**
   - Evaluate and interpret each cluster based on feature distributions.


# **Future Works**

This project is still being developed and will be updated.

# **Technologies Used**

Python 3.12.1

Pandas for Data Cleaning

Scikit-learn for Clustering
