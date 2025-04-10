# CustomerSegmentationUsingK-Means
In this project, the goal is to perform customer segmentation using K-Means clustering on a dataset of mall customers. Here's a summary of the steps:

Data Preprocessing: The 'Gender' column is converted to numerical values (0 for Male, 1 for Female).

Feature Selection: Three features are selected for clustering: 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)'.

Feature Scaling: The features are standardized using StandardScaler to normalize them.

Finding Optimal Clusters: The Elbow method is used to determine the optimal number of clusters (k=4).

K-Means Clustering: K-Means is applied to the scaled data with 4 clusters.

PCA for Visualization: Principal Component Analysis (PCA) is used to reduce the data to 2 dimensions for easy visualization.

Cluster Visualization: A scatter plot shows the clusters in 2D space.
