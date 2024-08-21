# Customer Segmentation Using K-means Clustering
# Introduction
Customer segmentation is a crucial aspect of any business strategy. It involves dividing customers into distinct groups based on their purchasing behavior and demographics. This allows businesses to tailor their marketing efforts, improve customer satisfaction, and increase sales.

K-means clustering is one of the most popular unsupervised machine learning algorithms used for customer segmentation. It aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean. This method is particularly useful when you have a large dataset and want to find hidden patterns within the data.

# Project Overview
In this project, we use K-means clustering to group customers of a retail store based on their purchase history. The dataset contains information about customers including their age, annual income, and spending score.

# Dataset
The dataset used in this project can be found on Kaggle: Customer Segmentation Dataset. It contains the following columns:

CustomerID: Unique identifier for each customer
Gender: Gender of the customer
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousands of dollars
Spending Score (1-100): Score assigned by the store based on customer behavior and spending
# Project Steps
1. Data Preprocessing:

- Load the dataset and check for any missing values.
- Select relevant features for clustering (Age, Annual Income (k$), Spending Score (1-100)).
- Normalize the data to ensure that each feature contributes equally to the distance computation.
2. Finding the Optimal Number of Clusters:

- Use the Elbow Method to determine the optimal number of clusters by plotting the inertia for different values of k.
3. Training the K-means Model:

- Train the K-means model using the optimal number of clusters determined from the Elbow Method.
- Assign each customer to a cluster.
4. Model Evaluation:

- Compute the Silhouette Score and Davies-Bouldin Index to evaluate the quality of the clusters.
5. Cluster Visualization:

- Use pairplots and 3D scatter plots to visualize the clusters.
6. Saving the Model:

- Save the trained K-means model for future use.
