# Clustering Project

## Overview
This project performs k-means clustering on a dataset of heights and weights to separate individuals into clusters, such as male and female groups. The clustering process involves iterative calculations of distances, centroid updates, and data visualisation.

## Files
- **Clustering Project.ipynb**: Jupyter Notebook containing the full implementation of the clustering algorithm and visualisations.
- **Weight-Height.csv**: Dataset containing height, weight, and gender information for individuals.

## Features
1. **Dataset Visualisation**:
   - Plots the height vs. weight data to observe clusters visually.

2. **K-Means Clustering**:
   - Implements the k-means algorithm step-by-step:
     - Randomly initialises cluster centroids.
     - Assigns data points to clusters based on distance.
     - Iteratively updates centroids until convergence.

3. **Cluster Analysis**:
   - Outputs cluster proportions for males and females.
   - Visualises the final clusters with centroids.

4. **Python Libraries Used**:
   - `numpy`
   - `matplotlib`
   - `pandas`

## Instructions
1. Clone the repository
2. Open `Clustering Project.ipynb` in a compatible environment.
3. Ensure the datasset `Weight-Height.csv` is in the same directory.
4. Run all cells in the notebook to:
   - Visualise the data
   - Perform clustering
   - View the cluster analysis and final plots
