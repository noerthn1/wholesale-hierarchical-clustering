# 📊 Hierarchical Clustering on Wholesale Customers Dataset

This project applies Hierarchical Agglomerative Clustering to segment wholesale customers based on their annual spending patterns. It is designed as a clear, portfolio-ready machine learning project using Python and Google Colab.

## 📁 Dataset: Wholesale Customers

- **Source:** UCI Machine Learning Repository
- **Rows:** 440
- **Features:**
  - Fresh
  - Milk
  - Grocery
  - Frozen
  - Detergents_Paper
  - Delicassen

Each row represents annual spending (in monetary units) of a wholesale client such as a retailer, hotel, or restaurant.

## 🎯 Project Objectives

- Perform customer segmentation using Hierarchical Clustering
- Visualize relationships using dendrograms & PCA
- Understand spending patterns and cluster characteristics
- Produce meaningful business insights

## 🛠️ Tools & Libraries

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-Learn
- SciPy
- Google Colab

## 🧹 Step 1: Data Loading & Cleaning

- Loaded the dataset from GitHub/UCI
- Checked for missing values
- Examined basic statistics

## 🔍 Step 2: Exploratory Data Analysis (EDA)

- Visualized distributions (histograms & boxplots)
- Checked correlations
- Identified skewness and outliers
- Observed which product categories dominate spending

## ⚙️ Step 3: Preprocessing

- Applied StandardScaler because hierarchical clustering is distance-based
- Generated a dendrogram to inspect cluster structure
- Determined a suitable number of clusters

## 🧩 Step 4: Hierarchical Clustering

- Used Agglomerative Clustering (Ward linkage)
- Added cluster labels to the DataFrame

## 🎨 Step 5: PCA Visualization

Performed PCA → reduced 6 dimensions to 2D. Used scatter plots to visualize cluster separation.

Example visualization improvements include:
- Transparent points
- Larger markers
- Custom palette
- Annotated centroids

## 📌 Step 6: Cluster Profiling

For each cluster:
- Calculated mean spend per category
- Identified customer characteristics

Example insights:
- Some clusters represent high grocery & detergent buyers
- Others represent low-volume mixed buyers
- One group may be heavy frozen goods purchasers

## 📈 Results Summary

Hierarchical clustering revealed clear groups with distinct spending patterns. These insights can help wholesale distributors:
- Build targeted marketing campaigns
- Predict customer needs
- Improve inventory planning
- Identify high-value client segments

## 📦 Folder Structure

```
├── README.md
├── hierarchical_clustering.ipynb
├── data/
│   └── wholesale_customers.csv
├── plots/
│   ├── dendrogram.png
│   ├── pca_clusters.png
│   └── heatmap.png
```

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload the dataset or load from URL
3. Install required Python packages
4. Run all cells

## 📝 Conclusion

This project demonstrates hierarchical clustering on real-world spending data, producing interpretable customer segments and helpful business insights.
