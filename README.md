# PRODIGY_ML_02
I created an unsupervised Machine Learning project using the K-Means algorithm to perform customer segmentation on mall data based on Annual Income and Spending Score.
Overview
This repository contains the solution for Task 02 of the Machine Learning Internship at Prodigy InfoTech. The objective was to implement the K-Means clustering algorithm to segment retail store customers based on their purchasing habits and financial metrics. This is a classic Unsupervised Learning problem used extensively in business intelligence and marketing.

Project Details
Algorithm: K-Means Clustering (Unsupervised Learning).
Dataset: Mall Customer Segmentation Data (Mall_Customers.csv).
Selected Features: Annual Income (k$) and Spending Score (1-100).
Optimal Clusters (K): Determined using the Elbow Method.

Methodology
1.  Feature Selection: Focused on Annual Income and Spending Score for meaningful 2D visualization.
2.  Elbow Method: Calculated the Within-Cluster Sum of Squares (WCSS) for $K=1$ to $10$ to find the optimal number of clusters. The optimal value was determined to be K=5.
3.  Model Training: Applied the K-Means algorithm with 5 clusters.
4.  Visualization: Plotted the 5 distinct clusters and their respective centroids.
