# K-Means Clustering on Wheat Seeds

An unsupervised machine learning lab that groups wheat seeds into clusters
based on their physical measurements, without using the species labels.

## What this lab covers
- Loading and exploring the seeds dataset (210 samples, 6 features)
- Scaling features with `MinMaxScaler`
- Reducing dimensions to 2D with PCA for visualization
- Choosing the number of clusters using the Elbow Method (WCSS)
- Training a K-Means model with 3 clusters
- Comparing the discovered clusters against the true species (~88% match)

## Files
- `seeds_kmeans.ipynb`: the notebook
- `seeds.csv`: the dataset
- `seeds_kmeans_hierarchical.ipynb`: K-Means vs hierarchical clustering with Silhouette score

## Tools
Python, pandas, scikit-learn, matplotlib

## Dataset
Seeds dataset from the UCI Machine Learning Repository (Dua, D. and Graff, C., 2019).
