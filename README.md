# Task-8-K-Means_Clustering
# K-Means Clustering on Mall Customer Data

---

## Objective
Apply K-Means Clustering to segment mall customers into meaningful groups based on demographics and spending habits.
---

## Repository Structure

- **Mall_Customers.csv** — Original dataset
- **task_8-kmeans_clustering.py** — Python script for Support Vector Machine (SVM)
- **task 8.pdf** — Given task
- **Visual Outputs** — Folder containing all visual plots
- **README.md** — This documentation
---
 ## Dataset
- **Source:** Mall_Customers.csv
- **Features Used:**
  - Gender (encoded)
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)
---
## Key Visuals

### Elbow Method
Determines the optimal number of clusters by analyzing inertia.
![elbow_plot](https://github.com/user-attachments/assets/2bf1b095-fe22-4468-b9a1-c70646d2e0ec)


**Insight:**  
The elbow is at K=5, which balances model simplicity and effectiveness.
---
### Cluster Visualization (PCA)
Customers grouped in 2D using Principal Component Analysis (PCA).

![cluster_pca_visual](https://github.com/user-attachments/assets/f93fca66-9871-4ea4-aba1-14df2d6f0cfb)

**Observation:**  
Distinct and well-separated clusters suggest good clustering quality.
---
## Evaluation Metric

**Silhouette Score:** for K=5: 0.557

Interpretation: Values above 0.5 are considered good and show well-defined clustering.

---
## Cluster-Level Insights
[cluster_summary.csv](https://github.com/user-attachments/files/20629080/cluster_summary.csv)

## Patterns and Anomalies

**Patterns:**
- Younger females tend to have higher spending scores.
- A distinct cluster of low-income, low-spending customers exists.

**Anomalies:**
- A small group with very high income but low spending could represent high-income savers or outliers.

## Conclusion
K-Means successfully segmented mall customers into 5 well-defined groups.  
These insights can help:
- Personalize marketing campaigns
- Improve customer retention
- Target specific customer groups effectively

## Tools Used
- Pandas for data handling  
- Scikit-learn for clustering, PCA, metrics  
- Matplotlib and Seaborn for visualization


