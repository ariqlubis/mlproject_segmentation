# Customer Segmentation using RFM Analysis and K-means Clustering

## Overview

This project focuses on customer segmentation using Recency, Frequency, and Monetary (RFM) analysis, followed by K-means clustering. The goal is to categorize customers into distinct segments to enable targeted marketing strategies and improve customer relationship management.

## Project Components

### 1. Data Preparation

**Objective:** Load and preprocess the data for analysis.

- **Data Loading:** Import the dataset containing customer transactions and relevant attributes.
- **Preprocessing:** Clean the data by handling missing values, removing duplicates, and ensuring consistency in data formats.
- **RFM Metrics Computation:** Calculate Recency, Frequency, and Monetary metrics for each customer. These metrics represent:
  - **Recency (R):** How recently a customer has made a purchase.
  - **Frequency (F):** How often a customer makes a purchase.
  - **Monetary (M):** How much money a customer spends.

### 2. RFM Analysis

**Objective:** Normalize and analyze RFM scores to understand customer behavior.

- **Normalization:** Normalize the Recency, Frequency, and Monetary scores to ensure comparability. This step helps in scaling the data so that each feature contributes equally to the clustering process.
  - **Recency Normalization:** Scale the recency values to a common range.
  - **Frequency Normalization:** Scale the frequency values to a common range.
  - **Monetary Normalization:** Scale the monetary values to a common range.
- **RFM Scores:** Analyze the normalized RFM scores to gain insights into customer behavior. This step helps in identifying patterns and trends in customer transactions.

### 3. Clustering with K-means

**Objective:** Apply K-means clustering to segment customers based on their RFM scores.

- **Determining Optimal Number of Clusters:**
  - Use the Elbow Method to determine the optimal number of clusters by plotting the inertia (within-cluster sum of squares) against the number of clusters.
- **K-means Clustering:**
  - Apply K-means clustering algorithm to the normalized RFM data.
  - Assign cluster labels to each customer based on the clustering results.


### 4. Future Work

- **Refinement of Clustering:** Experiment with different clustering algorithms (e.g., DBSCAN, Hierarchical Clustering) to compare results.
- **Advanced Analysis:** Incorporate additional features or external data to enhance the segmentation process.
- **NLP**: Review score and comments each order



