# **Analysis of Voter Abstention on Brazil's Presidential Elections through Data Clustering**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/heitornolla/voter-absention-clustering/blob/main/jupyter-notebook/notebook.ipynb)

**Disclaimer:** _This is a personal project intended for educational purposes only_

This project performs an unsupervised learning analysis on official voter abstention justification data from Brazilian elections. Using clustering techniques, it seeks to identify behavioral patterns in abstention reasons across demographic and regional variables.

# Overview

The project performs data preprocessing and cleaning, transforming it for machine learning. It then applies the K-Prototypes clustering algorithm to discover hidden structures in the data. Visualizations are shown to help interpret the results and understand the composition of the identified clusters.

# Project Steps

## 1. **Data Loading & Cleaning**
   - Load the .csv dataset containing official voter justification records.
   - Drop irrelevant or uniform columns (e.g., protocol numbers, identical values).
   - Map binary values (SIM/NAO) to numeric format.
   - Handle missing or ambiguous values like "NAO INFORMADO".
   
## 2. **Encoding & Scaling**
   - Ordinal encoding of ordered categories.
   - One-hot encoding of nominal categorical variables.

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
