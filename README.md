# CODTECH.TASK4
# Clustering Analysis for Library Management System

**COMPANY**: CODTECT IT SOLUTIONS

**NAME**:MUHSINA CT

**INTERN ID**:CT08FAA

**DOMAIN**:DATA SCIENCE

**BATCH DURATION**:20 DECEMBER 2024 TO 20 JANUARY 2025


## Overview
This project performs unsupervised learning using clustering techniques on a dataset of library books. The goal is to identify natural groupings or patterns within the data without predefined labels. Clustering algorithms such as **K-means**, **DBSCAN**, and **Hierarchical Clustering** are used to group the books based on features like **Signal Strength**, **Category**, **Cabinet**, and **Rack**.

## Steps

1. **Data Preprocessing**
   - Load and clean the dataset.
   - Scale features for clustering.

2. **Clustering Algorithms Implemented**
   - **K-means**: A centroid-based algorithm that groups books into a predefined number of clusters.
   - **DBSCAN**: A density-based clustering algorithm that identifies clusters of varying shapes and sizes.
   - **Hierarchical Clustering**: Builds a hierarchy of clusters and visualizes it using a dendrogram.

3. **Evaluation**
   - **Silhouette Score**: Measures how similar an object is to its own cluster compared to other clusters.
   - **Davies–Bouldin Index**: Measures the average similarity ratio of each cluster with the one most similar to it.

4. **Visualizations**
   - **2D Scatter Plots**: To visualize the clusters formed by the algorithms.
   - **Dendrogram**: For hierarchical clustering visualization.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
