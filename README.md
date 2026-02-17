# Mall-Customer-Segmentation-Data
Customer Segmentation using K-Means Clustering
Project Overview

This project implements K-Means Clustering to segment retail store customers based on their purchasing behavior. The objective is to group customers into distinct segments using their Annual Income and Spending Score, enabling data-driven marketing and business strategies.

Problem Statement

Develop a K-Means clustering model to group customers of a retail store based on their purchase history and behavioral patterns.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Dataset

File: Mall_Customers.csv

Features Used:

Annual Income (k$)

Spending Score (1–100)

Methodology

Data loading and preprocessing

Feature selection

Data standardization using StandardScaler

Determination of optimal clusters using the Elbow Method

Application of K-Means clustering

Visualization of customer segments

Model Selection

The Elbow Method was applied to determine the optimal number of clusters.
Based on the WCSS curve, the optimal number of clusters selected was:

K = 5

Results

The algorithm successfully segmented customers into five distinct groups, including:

High Income – High Spending

High Income – Low Spending

Low Income – High Spending

Low Income – Low Spending

Average Customers

These segments can help businesses design targeted marketing strategies, improve customer engagement, and optimize revenue generation.

How to Run the Project

Install required dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

customer_segmentation.ipynb

Conclusion

K-Means clustering effectively identified meaningful customer segments based on purchasing behavior. This project demonstrates the practical application of unsupervised machine learning in business analytics and customer strategy development.
