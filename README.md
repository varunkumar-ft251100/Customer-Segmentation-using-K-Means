# Project Title: Customer-Segmentation-using-K-Means
### Objective
To segment customers into distinct groups based on their demographics and spending behavior, enabling tailored marketing strategies and personalized customer engagement.
### Tools and Libraries Used
Programming Language: Python
Libraries:
Pandas: Data manipulation and analysis.
Matplotlib and Seaborn: Data visualization.
Scikit-learn: Scaling, clustering (K-Means), and metrics.
### Dataset
Data Source: Mall Customer Dataset
Number of Records: 200
Features Used:
Age: Customer age in years.
Annual Income (k$): Customer annual income in thousands of dollars.
Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature.
### Features Selected for Clustering
Age
Annual Income (k$)
Spending Score (1-100)
### Data Preprocessing
Scaling: StandardScaler was applied to normalize the features for better clustering performance.
Clustering Algorithm: K-Means
Number of Clusters (k): 5 (Optimal k determined using the Elbow Method).

### Visualizations
Pie Chart: Cluster distribution in percentages.
Scatter Plot: Visualization of clusters based on Spending Score and Annual Income.
8. Key Insights
Cluster 0: Largest group (40.5%), balanced income and spending, middle-aged customers.
Cluster 1: High income but low spending; opportunity to drive engagement.
Cluster 2: Low income and low spending; focus on budget-friendly options.
Cluster 3: Young, low income but high spending; target with trendy and affordable products.
Cluster 4: High income and high spending; retain with premium offerings.
### Recommendations
Cluster 0: Loyalty programs and mid-range offerings.
Cluster 1: Premium campaigns to engage high-income customers.
Cluster 2: Discounts and value-for-money options.
Cluster 3: Social media marketing and affordable products.
Cluster 4: VIP programs and exclusive experiences.





