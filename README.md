# Customer Segmentation with K-Means

This repository contains a customer segmentation project using the Mall Customers dataset and the K-Means clustering algorithm. The goal is to identify customer groups based on annual income and spending score.

## Files

- `Mall_Customers.csv` - The dataset containing customer details.
- `Training.ipynb` - Jupyter notebook with data exploration, preprocessing, and K-Means clustering.

## Project Overview

The notebook performs the following steps:

1. Load the Mall Customers dataset.
2. Explore the data and check for missing values or duplicates.
3. Select `Annual Income (k$)` and `Spending Score (1-100)` for clustering.
4. Use the elbow method to choose the optimal number of clusters.
5. Train a K-Means model with the selected cluster count.
6. Visualize customer segments and cluster centroids.

## How to Run

1. Open `Training.ipynb` in Jupyter Notebook or JupyterLab.
2. Make sure the dataset file `Mall_Customers.csv` is in the same folder as the notebook.
3. Run the notebook cells in order.

## Requirements

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Notes

- The notebook uses the elbow method to determine the best number of clusters.
- The final clustering is performed on two features: annual income and spending score.

## Result

The output shows segmented customer groups and their centroids, which can help identify patterns in customer spending and income levels.
