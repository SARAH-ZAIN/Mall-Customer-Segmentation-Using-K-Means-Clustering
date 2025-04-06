# Mall-Customer-Segmentation-Using-K-Means-Clustering

This project applies **K-Means Clustering** to group mall customers based on their **annual income** and **spending score**. The aim is to segment customers into distinct clusters for better targeting and personalization in marketing strategies.

---

## Project Objective

To identify and visualize customer segments using unsupervised machine learning on mall customer data, helping businesses understand purchasing behavior.

---

## Dataset

The dataset used is from [Kaggle - Mall Customer Segmentation Data]. It contains the following columns:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## Features Used for Clustering

- **Annual Income**
- **Spending Score**

These two features were selected for creating clusters that reflect different types of customers (e.g., high income - low spending, low income - high spending, etc.).

---

## Algorithm Used

- **K-Means Clustering**:
  - Unsupervised algorithm for grouping data based on similarity
  - Elbow method used to find optimal number of clusters (k = 5)

---

## Visualizations

- Gender Distribution
- Income vs Spending Score Scatterplot
- Cluster Visualization with Color-coded Groups

---

## Requirements

See `requirements.txt` for Python package dependencies.

---

## Output

The final output visualizes customer segments and provides insights into:
- Which customers spend the most
- Income groups with high/low spending
- Potential marketing strategies for each group
