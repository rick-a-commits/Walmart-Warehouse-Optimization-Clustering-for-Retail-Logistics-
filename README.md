# Walmart Warehouse Clustering

This project uses K-Means clustering on Walmart store location data to identify potential optimal warehouse locations across the United States.

## Problem Statement
Walmart operates thousands of stores across the U.S. Efficiently locating warehouses can significantly reduce shipping time and operational costs. This project applies unsupervised learning techniques to group stores and identify central hub locations.

## Approach
1. Load and explore store location data.
2. Apply KMeans clustering to latitude/longitude features.
3. Use the elbow method to select optimal cluster count.
4. Use Silhouette score to verfiy cluster choice
5. Visualize cluster assignments and centroids on a map.

## 📊 Key Results
- Identified **12 or 8 clusters** that suggest optimal hub placements based on Silhouette scores and elbow technique
- Identified stores per each cluser
- Visualized the clusters on geographic plots.

## 🚀 Tools Used
- Python (pandas, numpy, matplotlib, scikit-learn)
- Jupyter Notebook

## 📂 Project Structure
walmart-warehouse-clustering/
│
├── data/
│   └── walmart_store_location.csv   # Add a short README here about the dataset source
│
├── notebooks/
│   └── walmart_warehouse_clusters.ipynb
│
├── README.md
└── requirements.txt
