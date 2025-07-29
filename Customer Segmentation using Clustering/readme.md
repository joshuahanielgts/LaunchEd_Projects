# 📊 Customer Segmentation using Clustering (K-Means)

> Segmenting mall customers based on spending habits and income using unsupervised machine learning.

---

## 🚀 Project Overview

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to segment mall customers based on their **Age**, **Annual Income**, and **Spending Score**. This helps businesses better understand customer behaviors and tailor marketing strategies.

---

## 🎯 Objective

- Identify distinct customer groups using clustering.
- Visualize patterns in spending habits and income levels.
- Help businesses target the right customer with the right products.

---

## 🗂️ Dataset

- **Name:** Mall_Customers.csv  
- **Source:** [Kaggle - Customer Segmentation](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)

---

## 📌 Features Used

- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 🧰 Technologies & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Scikit-learn (StandardScaler, KMeans)
- Google Colab / Jupyter Notebook

---

## 🔍 Workflow

### 1. **Data Loading and Cleaning**
- Loaded the dataset
- Dropped irrelevant columns (`CustomerID`)
- Checked for missing values

### 2. **Exploratory Data Analysis (EDA)**
- Visualized distributions
- Created pairplots and heatmaps to observe feature relationships

### 3. **Feature Scaling**
- Standardized data using `StandardScaler` to improve clustering performance

### 4. **Optimal K Value**
- Used the **Elbow Method** to determine the optimal number of clusters

### 5. **K-Means Clustering**
- Applied `KMeans` with the optimal value of `K=5`
- Added cluster labels to the dataset

### 6. **Visualization**
- 2D scatter plots of income vs spending score
- Interactive 3D visualization using Plotly (`Age`, `Income`, `Score`)

### 7. **Cluster Interpretation**
- Described each cluster’s characteristics (e.g., high spenders, careful spenders, etc.)

---

## 📈 Sample Results

- **Cluster 0:** High income, low spending → *Careful spenders*
- **Cluster 1:** Young, low income, high spending → *Impulsive young shoppers*
- **Cluster 2:** Moderate income, moderate spending → *Average customers*
- **Cluster 3:** High income, high spending → *Premium customers*
- **Cluster 4:** Older, low income, low spending → *Low-value customers*

---

## 📌 Key Takeaways

- K-Means clustering effectively uncovered distinct behavioral patterns.
- The Elbow Method was vital in determining the optimal number of clusters.
- Insights from this segmentation can be used for **targeted marketing**, **customer retention**, and **product recommendation** systems.

---

## 💡 Future Improvements

- Use **PCA** for dimensionality reduction in larger datasets.
- Try other clustering algorithms (DBSCAN, Hierarchical).
- Include additional demographic features (e.g., region, gender encoding).

---

## 📎 Files Included

- `Mall_Customers.csv` — Dataset
- `Customer_Segmentation_KMeans.ipynb` — Full notebook (Colab-ready)
- `README.md` — Project documentation
