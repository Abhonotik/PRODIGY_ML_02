# 🧠 Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers of a retail store based on their purchasing behavior.

## 📂 Dataset
Used the [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) from Kaggle.

### Features Used:
- `Annual Income (k$)`
- `Spending Score (1–100)`

## 📌 Objective
To group similar customers together to:
- Understand customer behavior
- Improve marketing strategy
- Personalize offers and services

## 🛠️ Technologies Used
- **Python**
- `Pandas` for data handling  
- `Matplotlib`, `Seaborn` for visualization  
- `scikit-learn` for applying K-Means

## 📊 Methodology

### 1. Data Preprocessing
- Handled missing values (if any)
- Selected relevant features for clustering

### 2. Elbow Method
Used the **Within-Cluster Sum of Squares (WCSS)** to determine the optimal number of clusters.

### 3. K-Means Clustering
- Applied K-Means algorithm with `k=5`
- Visualized clusters with color-coded segments
- Plotted centroids to show cluster centers

### 4. Visualization
Created 2D scatter plots with:
- Distinct colors for each cluster
- Yellow centroid markers
- Labels, legends, and grid

