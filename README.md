Customer Segmentation using K-Means Clustering
This project implements K-Means Clustering to segment customers based on Annual Income and Spending Score from a dataset. The aim is to group customers into distinct segments to better understand their purchasing behavior and preferences.

Overview
Businesses often need to identify patterns in customer data to improve marketing strategies, product recommendations, and customer engagement. This project uses the K-Means++ algorithm to create 5 clusters that represent different customer categories, ranging from low-income low-spenders to high-income high-spenders.

Key Steps
Data Preprocessing

Selecting relevant features: Annual Income (k$) and Spending Score (1–100)

Scaling features for better clustering accuracy.

Model Training

Applied K-Means++ initialization for optimal centroid placement.

Determined the number of clusters using the Elbow Method.

Visualization

Generated a 2D scatter plot displaying clusters in different colors.

Marked centroids of each cluster for better interpretability.

Added axis labels and grid for clarity.

Applications
Targeted Marketing – Identify customer groups for personalized promotions.

Product Placement – Optimize product recommendations for each segment.

Customer Retention – Recognize high-value customers and improve engagement.

Technologies Used
Python

Pandas, NumPy

Matplotlib

scikit-learn

How It Works
Load and clean the dataset.

Extract relevant features and scale them.

Apply K-Means++ clustering to group customers.

Visualize clusters and centroids.

This project serves as a practical example of unsupervised machine learning for real-world business intelligence. It can be extended with more features such as age, gender, and spending habits for deeper segmentation.