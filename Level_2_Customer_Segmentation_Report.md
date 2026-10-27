
# Level 2: Customer Segmentation Analysis

## 1. Project Overview
This project groups customers into segments based on their annual
income and spending score using the K-Means clustering algorithm.

## 2. Objectives
- Explore customer demographic and spending data.
- Prepare the dataset for clustering.
- Determine a suitable number of clusters.
- Identify customer groups and develop business insights.

## 3. Tools and Technologies
Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

## 4. Dataset
The Mall Customers dataset contains 200 records and five columns:
CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).

## 5. Methodology
1. Load and inspect the dataset.
2. Select annual income and spending score as clustering features.
3. Use the Elbow Method to help select the cluster count.
4. Apply K-Means clustering with five clusters.
5. Visualize the customer segments and summarize their characteristics.

## 6. Results
The analysis produced five clusters. The silhouette score was 0.5539.
Cluster sizes were:
- Cluster 0: 81 customers
- Cluster 1: 39 customers
- Cluster 2: 22 customers
- Cluster 3: 35 customers
- Cluster 4: 23 customers

## 7. Business Insights
- Cluster 1 has relatively high income and high spending scores.
- Cluster 2 has relatively low income and high spending scores.
- Cluster 3 has relatively high income and low spending scores.
- Cluster 4 has relatively low income and low spending scores.
- Cluster 0 represents a larger, more moderate-spending group.

These segments can help a business consider differentiated marketing
strategies. They are exploratory groups, not proven customer behaviors.

## 8. Conclusion
K-Means clustering identified five customer segments using income
and spending score. The results can support targeted marketing and
further customer analysis.

## 9. Deliverables
- Python notebook
- Customer segment summary CSV
- Customer segmentation results CSV
- Cluster visualization(s)
- This project report
