#  eCommerce Transactions Dataset Analysis
An eCommerce Transactions dataset consisting of three files: Customers.csv, Products.csv, and Transactions.csv. Performed exploratory data analysis (EDA), built predictive models, and derived actionable insights.

## Overview
This project involves analyzing an eCommerce dataset containing information about customers, products, and transactions. The objectives include performing exploratory data analysis (EDA), building a lookalike model for customer recommendations, and conducting customer segmentation using clustering techniques.

## Files and Deliverables
1. **EDA Report**
   - A detailed report summarizing key trends, outliers, and relationships in the dataset.
   - Includes 5 actionable business insights based on EDA.
   
2. **Lookalike Model**
   - A Python script for recommending similar customers using Cosine Similarity.
   - Output file: `Lookalike.csv`, mapping CustomerIDs to their top 3 similar customers and scores.

3. **Clustering Analysis**
   - A Python script for customer segmentation using KMeans clustering.
   - Metrics such as Davies-Bouldin Index and Silhouette Score are reported.

4. **Jupyter Notebooks**
   - Includes implementations for EDA, Lookalike Model, and Clustering.

## Insights Summary

### Task 1: Exploratory Data Analysis
- Customers are primarily located in Asia and North America.
- Electronics and Apparel categories generate the highest sales.
- A small group of high-value customers contributes most revenue.
- Seasonal trends show sales peaks during holidays.
- High-value transactions are linked to premium products.

### Task 2: Lookalike Model
- Recommends 3 similar customers for each input customer based on transaction history and profile.
- Enables targeted marketing and personalized customer engagement.

### Task 3: Customer Segmentation
- Identified 4 customer clusters:
   1. High spenders with frequent transactions.
   2. Moderate spenders focused on specific categories.
   3. Occasional buyers with low transaction value.
   4. New customers with minimal history.
- Cluster analysis supports personalized strategies to enhance customer engagement.
