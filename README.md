E-Commerce Transactions Analysis

Overview

This repository contains the analysis and modeling performed on an e-commerce dataset, including exploratory data analysis (EDA), customer segmentation, and a lookalike recommendation model. The goal is to derive business insights, segment customers into meaningful groups, and recommend similar customers based on transaction history and profile data.

Files in Repository

1. Data Files

Customers.csv: Contains customer demographic information.

Products.csv: Details about products available in the e-commerce store.

Transactions.csv: Records of transactions made by customers.

2. Scripts

EDA_Analysis.ipynb: A Jupyter Notebook performing exploratory data analysis and summarizing business insights.

Lookalike_Model.ipynb: A script for building a lookalike recommendation model, generating the Lookalike.csv file.

Customer_Clustering.ipynb: A script for customer segmentation using clustering techniques and evaluating cluster quality.

3. Generated Outputs

Lookalike.csv: Recommendations for similar customers based on profile and transaction history.

Customer_Segments.csv: Segmentation results including cluster assignments for each customer.

EDA_Report.pdf: A PDF summarizing the business insights derived from EDA.

Clustering_Report.pdf: A PDF documenting clustering results, metrics, and visualizations.

Key Features

1. Exploratory Data Analysis (EDA)

Uncovered key business insights, such as customer behavior trends, product popularity, and sales distribution.

Delivered actionable recommendations based on observed patterns.

2. Lookalike Recommendation Model

Built a similarity-based recommendation system using cosine similarity.

Recommended top 3 similar customers for the first 20 customers in the dataset.

Generated similarity scores for actionable marketing strategies.

3. Customer Segmentation

Segmented customers into distinct clusters using KMeans.

Evaluated clustering quality using the Davies-Bouldin Index (DB Index) and silhouette scores.

Visualized clusters using PCA to understand group differences.
Install the required Python packages:

pip install -r requirements.txt

Run the scripts:

Perform EDA: Open and run EDA_Analysis.ipynb.

Generate Lookalike Recommendations: Open and execute Lookalike_Model.ipynb.

Perform Customer Segmentation: Open and run Customer_Clustering.ipynb.

Outputs:

Lookalike recommendations will be saved in Lookalike.csv.

Customer segmentation results will be saved in Customer_Segments.csv.

Requirements

Python 3.8+

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Results Summary

EDA Insights:

Identified seasonal trends in customer acquisition and transaction patterns.

Recognized the importance of high-frequency customers and cross-selling opportunities.

Lookalike Model:

Recommended similar customers with assigned similarity scores, aiding personalized marketing strategies.

Customer Clustering:

Formed 4 clusters with a Davies-Bouldin Index of 0.89 and a silhouette score of 0.62.

Derived actionable insights from distinct customer groups.

