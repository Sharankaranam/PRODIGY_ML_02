# 📊 Customer Segmentation with K-Means Clustering 📊

## Overview

This project involves creating a K-means clustering algorithm to group customers of a retail store based on their purchase history. The goal is to identify distinct customer segments to tailor marketing strategies and improve customer experience.

## Project Overview

### Data Preparation

- **Dataset**: `Mall_Customers.csv`
  - **Features**:
    - `Age`
    - `Annual Income (k$)`
    - `Spending Score (1-100)`

### Methodology

1. **Finding Optimal Clusters**:
   - **Elbow Method**: Plotted the within-cluster sum of squares (WCSS) against the number of clusters to identify the "elbow point," which helps in determining the optimal number of clusters.
   - **Silhouette Score**: Calculated silhouette scores for different numbers of clusters to assess the quality of clustering and identify the optimal number of clusters.

2. **Clustering Analysis**:
   - Applied K-means clustering with the identified optimal number of clusters.
   - Added cluster labels to the dataset for further analysis.

3. **Visualization**:
   - Visualized the customer segments using scatter plots based on different feature combinations:
     - Annual Income vs. Spending Score
     - Age vs. Spending Score
     - Age vs. Annual Income

## Results

- **Optimal Number of Clusters**: 5
- **Visualizations**:
  - Scatter plots showing customer segments by various feature combinations, highlighting distinct clusters.

## Installation

To run the code, you need the following Python packages:

```bash
pip install pandas matplotlib seaborn scikit-learn
