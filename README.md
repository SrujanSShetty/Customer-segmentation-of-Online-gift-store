# Customer Segmentation and Market Basket Analysis

## Introduction
This project explores customer segmentation and market basket analysis using the publicly available Online Retail dataset. The dataset includes transactions from a UK-based online retail company specializing in unique all-occasion gifts, covering the period from 01/12/2010 to 09/12/2011. The primary goals are to apply unsupervised learning methods to segment customers and use association rule mining to identify patterns and rules within the transaction data.

### Objectives
- **Customer Segmentation**: Identify distinct customer groups based on purchase behavior using unsupervised learning techniques.
- **Market Basket Analysis**: Understand interesting patterns and associations in customer transactions to gain deeper insights into purchasing behavior.

## Concepts

### Customer Segmentation
Customer segmentation involves analyzing customer interactions to uncover meaningful information about different customer groups. This often includes evaluating their purchase behaviors and patterns to tailor marketing strategies and improve business decisions.



## Table of Contents
1. **Load Dependencies and Configuration Settings**
   - Set up the environment and load necessary libraries.
2. **Load Dataset**
   - Import the Online Retail dataset for analysis.
3. **Exploratory Data Analysis (EDA)**
   - **3.1 Take a First Look at the Data**: Initial examination of the dataset to understand its structure and contents.
   - ![Exploratory Data Analysis](https://github.com/user-attachments/assets/4344c8ac-2083-4688-b063-20fdbf14cc30)
4. **Customer Segmentation**
   - **4.1 RFM Model for Customer Value**:
     - **4.1.1 Recency**: Measure the time since the last purchase.
     - **4.1.2 Frequency**: Count the number of purchases.
     - **4.1.3 Monetary Value**: Calculate the total spend.
   - **4.2 Data Preprocessing**: Prepare the data for clustering.
   - **4.3 Clustering for Segments**:
     - **4.3.1 K-Means Clustering**:
       - **4.3.1.1 K-means++**: Initialization method to improve clustering results.
     - **4.3.2 The Elbow Method**: Determine the optimal number of clusters.
      ![Model Selection]![Model selection](https://github.com/user-attachments/assets/12ab1974-5347-4577-a963-cbd07ae01a73)
     - **4.3.3 Silhouette Analysis on K-Means Clustering**: Evaluate cluster quality.
     - **4.3.4 Cluster Centers**: Analyze the centroids of the clusters.
     - **4.3.5 Cluster Insights**: Interpret the characteristics of each cluster.
      - ![Cluster Insights]![Overall Cluster Details](https://github.com/user-attachments/assets/c8576419-3c8e-4452-acfe-a1d7271ec5a8)
     - **4.3.6 Drill Down Clusters**: Detailed analysis of individual clusters.

## Team
This analysis was conducted by **Group939**, focusing on leveraging unsupervised learning methods to gain valuable insights from the Online Retail dataset.

## Acknowledgments
Special thanks to the developers and maintainers of the Online Retail dataset for providing the data used in this analysis.

## Contact
For any questions or feedback, please contact [SrujanSShettyofficial@gmail.com] or open an issue in the repository.

---

**Developed by [Srujan Shekar Shetty]**
