# ecommerce-customer-clustering
mini project of unsupervised machine learning
Project Description

This project implements an end-to-end customer clustering pipeline for an e-commerce dataset using machine learning techniques. The workflow begins with data preprocessing, followed by feature engineering, and finally applies clustering algorithms to segment customers into meaningful groups.

The dataset is first loaded and cleaned by handling missing values (e.g., filling missing income values with the median). New features are then created to enhance analysis, such as:

Age (derived from year of birth)
Customer tenure (based on enrollment date)

These engineered features help in better understanding customer behavior.

Workflow Overview
1. Data Preprocessing
Loaded dataset using Pandas
Checked for missing values
Handled null values (Income column)
Converted date columns into proper datetime format
2. Feature Engineering
Created Age from Year_Birth
Calculated Customer Tenure (days since joining)
Prepared dataset for clustering
3. Exploratory Data Analysis (EDA)
Used Matplotlib and Seaborn for visualization
Analyzed distributions and relationships between features
4. Clustering
Applied K-Means clustering algorithm
Grouped customers based on purchasing behavior and engagement
Identified distinct customer segments

Purpose of the Code

The main goal of this implementation is to:

Transform raw customer data into meaningful insights
Identify hidden patterns in customer behavior
Enable data-driven marketing strategies
Help businesses target specific customer groups effectively

Result

The final output of the model is a set of customer clusters, where each group represents customers with similar:

Spending habits
Engagement levels
Demographic characteristics

These clusters can be used for:

Personalized marketing
Customer retention strategies
Business growth optimization
