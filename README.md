# Customer Segmentation Analysis for KJ Marketing

## Introduction

This repository contains the analysis and model implementation for classifying new customers into identified customer segments based on historical sales data. The primary objective is to enhance KJ Marketing's ability to tailor its marketing strategies to individual customer preferences, thereby improving customer satisfaction and business performance.

## Objective

- **Primary Objective:** Classify new customers into segments based on historical sales data.
- **Business Impact:** Enhance KJ Marketing's personalized marketing strategies to maintain a competitive advantage and foster customer loyalty.

## Context

KJ Marketing is a leading retail supermarket chain in Sri Lanka, offering a wide range of products. With a network of 22 outlets, the company seeks to adopt personalized marketing strategies to better cater to its diverse customer base.

## Data Preprocessing

### Handling Missing Values, Duplicates, and Outliers

- **Missing Values:** Mean imputation for numerical features and mode imputation for categorical features.
- **Duplicates:** Retained to preserve valuable transaction data.
- **Outliers:** Removed using the Z-score method with a threshold of ±3.

## Feature Engineering

- **Feature Selection:** Based on domain knowledge, correlation analysis, and preliminary modeling experiments.
- **Feature Scaling:** Standard scaling method to standardize features.
- **Encoding Strategies:** One-hot encoding for categorical features.

## Correlation Analysis

Analyzed the correlation between features and the target variable using one-way ANOVA, confirming significant associations.

## Target Variable Analysis

Conducted a comprehensive analysis of the target variable "cluster_category" to understand the characteristics of different customer segments.

## Model Selection and Training

- **Algorithms Considered:** K-Means, Gradient Boosting, and Random Forest.
- **Final Model:** Random Forest was chosen for its superior performance, achieving an accuracy score of 0.9998.

## Cluster Interpretation

- **Cluster 1 :** Dry Goods Cluster
- **Cluster 2 :** Value Shoppers Cluster
- **Cluster 3 :** Affluent Shoppers Cluster
- **Cluster 4 :** Bulk Buyers Cluster
- **Cluster 5 :** Balanced Shoppers Cluster
- **Cluster 6 :** High-End Shoppers Cluster

## Business Implications

- **Marketing Strategy Enhancement:** Tailored promotions and personalized marketing campaigns.
- **Strategic Resource Allocation:** Optimized marketing budgets and improved customer loyalty.

## Conclusion

The analysis successfully classified customers into segments, providing valuable insights for targeted marketing strategies. Future work includes exploring temporal data, other algorithms, and real-time implementation.

## Contributors

- **Akith Chandinu** - [Akith-002](https://github.com/Akith-002)
- **Vinuka Fernandopulle** - [VinukaVilhan](https://github.com/VinukaVilhan)
- **Saradi Dassanayake** - [Saradi140](https://github.com/Saradi140)
---
- If github does not render the jupiter file use <a href='https://nbviewer.jupyter.org/'>nbviewer</a> 
