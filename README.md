1. Project Title: Customer-Segmentation-using-K-Means
2. Objective
To segment customers into distinct groups based on their demographics and spending behavior, enabling tailored marketing strategies and personalized customer engagement.

3. Dataset
Data Source: Mall Customer Dataset
Number of Records: 200
Features Used:
Age: Customer age in years.
Annual Income (k$): Customer annual income in thousands of dollars.
Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature.
4. Features Selected for Clustering
Age
Annual Income (k$)
Spending Score (1-100)
5. Data Preprocessing
Scaling: StandardScaler was applied to normalize the features for better clustering performance.
Clustering Algorithm: K-Means
Number of Clusters (k): 5 (Optimal k determined using the Elbow Method and Silhouette Score).
6. Cluster Summary
Cluster	Age	Annual Income (k$)	Spending Score (1-100)	Percentage (%)	Cluster Size
0	42.7	55.3	49.5	40.5%	81
1	41.1	88.2	17.1	17.5%	35
2	45.2	26.3	20.9	11.5%	23
3	25.3	25.8	79.4	11.0%	22
4	32.7	86.5	82.1	19.5%	39
7. Visualizations
Pie Chart: Cluster distribution in percentages.
Scatter Plot: Visualization of clusters based on Spending Score and Annual Income.
8. Key Insights
Cluster 0: Largest group (40.5%), balanced income and spending, middle-aged customers.
Cluster 1: High income but low spending; opportunity to drive engagement.
Cluster 2: Low income and low spending; focus on budget-friendly options.
Cluster 3: Young, low income but high spending; target with trendy and affordable products.
Cluster 4: High income and high spending; retain with premium offerings.
9. Recommendations
Cluster 0: Loyalty programs and mid-range offerings.
Cluster 1: Premium campaigns to engage high-income customers.
Cluster 2: Discounts and value-for-money options.
Cluster 3: Social media marketing and affordable products.
Cluster 4: VIP programs and exclusive experiences.
10. Tools and Libraries Used
Programming Language: Python
Libraries:
Pandas: Data manipulation and analysis.
Matplotlib and Seaborn: Data visualization.
Scikit-learn: Scaling, clustering (K-Means), and metrics.
11. Performance Metrics
Optimal k: 5 (determined by Elbow Method and Silhouette Score).
Silhouette Score for k=5: ~0.42 (indicating moderate clustering performance).
12. Future Work
Explore alternative clustering algorithms (e.g., DBSCAN, GMM).
Incorporate additional features (e.g., frequency of visits, product categories).
Perform dimensionality reduction (PCA) for better visualization and feature importance analysis.
