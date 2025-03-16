# PRODIGY_ML_02
## Customer Segmentation using K-Means Clustering
This repository contains a Python implementation of customer segmentation using K-Means clustering based on purchase history data from a retail store. The goal is to group customers into distinct segments based on their behavior, such as their annual income, spending score, and age. This kind of segmentation can help businesses target specific customer groups with personalized marketing strategies.

# Table of Contents

Project Overview
Technologies Used
Dataset
Installation
Usage
Steps Involved
License

# Project Overview
In this project, we apply K-means clustering to group customers based on their purchase behavior. We use the Mall Customers Dataset, which contains customer data including their Age, Annual Income (k$), Spending Score (1-100), and Gender.

The project includes the following key steps:

Data loading and preprocessing
Scaling and normalizing data
Finding the optimal number of clusters using the Elbow Method
Applying K-means clustering
Analyzing and visualizing customer segments
Technologies Used
Python
Pandas
NumPy
scikit-learn
Matplotlib
Seaborn

# Dataset
The dataset used in this project is available on Kaggle and contains the following columns:

CustomerID: Unique identifier for each customer
Gender: Gender of the customer ('Male' or 'Female')
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousands of dollars
Spending Score (1-100): A score assigned to the customer based on their spending behavior
You can download the dataset from Kaggle here.


# Steps Involved
Data Loading: Load the dataset using Pandas and explore the first few rows.
Preprocessing:
Remove unnecessary columns like CustomerID.
Handle missing values (if any).
Convert categorical data like Gender into numerical values.
Feature Selection: Select relevant features for clustering (Age, Annual Income, Spending Score).
Scaling: Normalize the data using StandardScaler to ensure all features are on a similar scale.
K-means Clustering:
Use the Elbow Method to determine the optimal number of clusters (K).
Apply K-means clustering with the selected number of clusters.
Assign each customer to a cluster.
Visualization: Use a scatter plot to visualize customer segments based on their Annual Income and Spending Score.
Results
The script performs K-means clustering and produces the following results:

The optimal number of clusters based on the Elbow Method.
Cluster centers showing the average values of features for each cluster.
A scatter plot that visualizes how the customers are grouped into different segments based on their income and spending behavior.

