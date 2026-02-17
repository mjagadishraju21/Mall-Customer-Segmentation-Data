# Customer Segmentation using K-Means Clustering

## Project Overview

This project implements K-Means Clustering to segment retail store customers based on their purchasing behavior. The objective is to group customers into distinct segments using Annual Income and Spending Score, enabling data-driven marketing and strategic decision-making.

---

## Problem Statement

Develop a K-Means clustering model to group customers of a retail store based on their purchase history and behavioral patterns.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset

File: Mall_Customers.csv

Features Used:
- Annual Income (k$)
- Spending Score (1–100)

---

## Methodology

1. Data Loading and Preprocessing
2. Feature Selection
3. Data Standardization using StandardScaler
4. Determination of Optimal Clusters using the Elbow Method
5. Application of K-Means Clustering
6. Visualization of Customer Segments

---

## Model Selection

The Elbow Method was applied to determine the optimal number of clusters.

Optimal Number of Clusters Selected: K = 5

---

## Results

The algorithm successfully segmented customers into five distinct groups:

- High Income – High Spending
- High Income – Low Spending
- Low Income – High Spending
- Low Income – Low Spending
- Average Customers

These segments help businesses design targeted marketing strategies, improve customer engagement, and optimize revenue generation.

---

## How to Run the Project

1. Install required dependencies:

   pip install -r requirements.txt

2. Run the Jupyter Notebook:

   customer_segmentation.ipynb

---

## Conclusion

K-Means clustering effectively identified meaningful customer segments based on purchasing behavior. This project demonstrates the practical application of unsupervised machine learning techniques in business analytics.
