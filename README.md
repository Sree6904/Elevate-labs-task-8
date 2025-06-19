# Elevate-labs-task-8
 Mall Customer Segmentation using K-Means

## 🔍 Objective
Segment mall customers into distinct groups based on their annual income and spending behavior using K-Means clustering.

## 📁 Dataset
- **Source:** 'Mall_Customers.csv'
- **Features Used:**
  - 'Annual Income (k$)'
  - 'Spending Score (1–100)'

## 📌 Key Concepts Covered
- K-Means Clustering
- Elbow Method
- Cluster Visualization
- Silhouette Score

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

## 🚀 Implementation Steps
1. Loaded dataset and dropped irrelevant columns
2. Scaled features using 'StandardScaler'
3. Applied Elbow Method to determine optimal clusters
4. Trained KMeans and predicted cluster labels
5. Visualized clusters and centroids
6. Evaluated model using Silhouette Score

## 📈 Results

- **Optimal K:** 5 (from Elbow Method)
- **Silhouette Score:** ~0.55
- Plotted clusters with clear separation
