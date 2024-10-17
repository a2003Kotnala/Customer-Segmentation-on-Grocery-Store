# Customer Segmentation on Grocery Store 
 
Overview -

This project focuses on customer segmentation in a grocery store using machine learning techniques. By segmenting customers into groups, grocery stores can better target their marketing strategies, offer personalized services, and optimize their overall operations. This project employs two clustering algorithms: KMeans Clustering and Agglomerative Clustering, to identify distinct customer segments based on their purchasing patterns.

Table of Contents
1. Project Overview
2. Tech Stack
3. Dataset
4. Approach
5. Clustering Techniques
6. KMeans Clustering
7. Agglomerative Clustering
8. Results



Tech Stack : 
-> Programming Language: Python
-> Libraries:
   -> Pandas
   -> NumPy
   -> Scikit-learn
   -> Matplotlib
   -> Seaborn
-> Machine Learning

Dataset
The dataset used in this project contains various features related to customer purchase behavior, such as:
-> Annual Spend: Amount spent by customers in a year.
-> Purchase Frequency: How often customers shop at the store.
-> Customer Age: Age of the customers.
-> Shopping Preferences: Categories or types of products frequently purchased.


Approach
1. Data Preprocessing: The dataset is cleaned, normalized, and prepared for clustering. This includes handling missing values, feature scaling, and exploratory data analysis (EDA) to understand the relationships between variables.
2. Feature Selection: Relevant features are selected that help in distinguishing customer segments effectively.
3. Clustering Algorithms: Two clustering algorithms, KMeans and Agglomerative Clustering, are applied to group customers based on their spending behavior.
4. Evaluation: Different metrics such as Silhouette Score and Inertia are used to evaluate the performance of the clustering algorithms.


Clustering Techniques
1. KMeans Clustering
(KMeans is a partition-based clustering algorithm that divides customers into K clusters, where each customer belongs to the cluster with the nearest mean.)

Steps Involved:
-> Choose the number of clusters (K).
-> Assign customers to the nearest cluster based on distance.
-> Update the centroids and repeat the process until convergence.

2. Agglomerative Clustering
(Agglomerative Clustering is a hierarchical clustering method that builds nested clusters by merging or splitting them based on distance measures.)

Steps Involved:
-> Start with each customer as its own cluster.
-> Iteratively merge the closest pairs of clusters.
-> Continue until all customers are merged into a single cluster or the desired number of clusters is reached.


Results
-> KMeans Clustering produced clear customer segments based on spending habits.
-> Agglomerative Clustering provided a hierarchical structure to understand how customers are grouped at different levels.
-> The Silhouette Score was used to validate the effectiveness of each clustering method.

