# Customer Segmentation using PCA and Clustering

## Overview

This project applies **unsupervised machine learning** techniques to segment customers based on their demographics, purchasing behavior, and marketing engagement.

Using **Principal Component Analysis (PCA)**, **K-Means Clustering**, and **Agglomerative Clustering**, the project identifies distinct customer groups that can help businesses improve customer targeting and marketing strategies.

---

## Objectives

- Analyze customer purchasing behavior.
- Reduce feature dimensionality using PCA.
- Identify meaningful customer segments.
- Compare clustering approaches.
- Generate actionable business insights.

---

## Dataset Features

The dataset contains customer information including:

- Income
- Recency
- Total Spending
- Web Purchases
- Catalog Purchases
- Store Purchases
- Deal Purchases
- Website Visits
- Campaign Acceptance
- Family Information

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Methodology

### Data Preprocessing
- Missing value treatment
- Feature engineering
- Encoding categorical variables
- Feature scaling

### Dimensionality Reduction
- Principal Component Analysis (PCA)

### Clustering
- K-Means Clustering
- Agglomerative Clustering

### Cluster Evaluation
- Elbow Method
- Silhouette Score

---

## Project Workflow

```text
Raw Data
    │
    ▼
Data Cleaning
    │
    ▼
Feature Engineering
    │
    ▼
Standard Scaling
    │
    ▼
   PCA
    │
    ▼
Clustering
 ├── K-Means
 └── Agglomerative
    │
    ▼
Cluster Analysis
    │
    ▼
Business Insights
```

---

## Results

The analysis identified **4 distinct customer segments**:

### Cluster 0 – Moderate-Value Customers
- Average income
- Moderate spending behavior
- Frequent website activity
- Price-sensitive shoppers

### Cluster 1 – High-Value Customers
- Highest income group
- Strong purchasing activity
- Significant revenue contribution
- Loyal customers

### Cluster 2 – Low-Spending Customers
- Lower income segment
- Limited purchases
- High browsing activity
- Potential target for promotions

### Cluster 3 – Premium Responsive Customers
- High spending behavior
- Strong campaign response rates
- Most valuable marketing segment

---

## Key Insights

- Income strongly influences spending behavior.
- High-value customers purchase more frequently across all channels.
- Low-value customers visit websites often but convert less.
- Customer groups respond differently to marketing campaigns.
- Segmentation can improve targeted marketing strategies.
