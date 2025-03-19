# Clustering Algorithms - Iris Dataset

## Overview
This project implements **KMeans** and **Hierarchical Clustering** on the Iris dataset to analyze and visualize clusters.

## Dataset
- **Source:** `sklearn.datasets.load_iris()`
- **Features:** Sepal length, Sepal width, Petal length, Petal width
- **Preprocessing:** Standardized using `StandardScaler`

## Clustering Implemented
1. **KMeans Clustering**
   - Partitions data into `k=3` clusters
   - Uses Euclidean distance to minimize variance
   - Visualized with a scatter plot, including cluster centroids

2. **Hierarchical Clustering**
   - Uses Ward’s linkage to minimize variance within clusters
   - Dendrogram plotted for hierarchical structure
   - Scatter plot to visualize assigned clusters

## Results
- Clusters are well-separated in both methods.
- KMeans provides fast results, while Hierarchical clustering offers a hierarchical view.



