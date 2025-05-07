# Task 8: K-Means Clustering - Mall Customer Segmentation

## 📌 Objective
Apply K-Means to cluster customers based on features like Age, Gender, Annual Income, and Spending Score.

## 🧰 Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib

## 📊 Dataset
**Mall_Customers.csv** containing:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## ✅ Steps Performed
1. Preprocessed data (encoding, scaling).
2. Used Elbow Method to determine optimal number of clusters.
3. Applied KMeans for clustering with optimal `k`.
4. Used PCA for 2D visualization of clusters.
5. Evaluated clustering using Silhouette Score.

## 📈 Results
- Optimal `k`: 5
- Silhouette Score: ~0.55
- Visualized customer segments using PCA.

## 🧠 What I Learned
- How K-Means clustering groups similar data points.
- How to determine `k` using Elbow Method.
- Importance of feature scaling and dimensionality reduction (PCA).
- Cluster evaluation using Silhouette Score.

