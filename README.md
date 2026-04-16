# 🍷 Wine Dataset Clustering using PCA & K-Means

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Unsupervised-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)
![PCA](https://img.shields.io/badge/Technique-PCA-purple)
![Clustering](https://img.shields.io/badge/Algorithm-KMeans-red)

---

## 📌 Project Overview

This project demonstrates **Unsupervised Machine Learning** techniques using the Wine dataset. It focuses on:

- Exploratory Data Analysis (EDA)
- Data preprocessing and outlier handling
- Dimensionality reduction using **Principal Component Analysis (PCA)**
- Clustering using **K-Means Algorithm**
- Performance comparison between original and PCA-transformed data

The goal is to understand how PCA impacts clustering performance and visualization.

---

## 🎯 Objectives

- Perform detailed exploratory data analysis on the Wine dataset
- Identify and handle missing values and outliers
- Reduce dimensionality using PCA while preserving maximum variance
- Apply K-Means clustering on both original and PCA-transformed data
- Evaluate and compare clustering performance using metrics

---

## 📊 Dataset Information

- **Dataset Name:** Wine Dataset (`wine.csv`)
- **Type:** Multivariate classification dataset (used here for clustering)
- **Features:** Chemical properties of wine samples
- **Instances:** Multiple wine samples with numerical attributes

---

## ⚙️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Machine Learning Workflow

### 1️⃣ Exploratory Data Analysis (EDA)
- Data shape and structure analysis
- Summary statistics
- Missing value and duplicate checks
- Feature distribution visualization
- Correlation heatmap analysis

---

### 2️⃣ Data Preprocessing
- Outlier detection using **IQR method**
- Outlier treatment using capping
- Feature scaling using **StandardScaler**

---

### 3️⃣ Dimensionality Reduction (PCA)
- Applied PCA to standardized dataset
- Scree plot used to determine optimal components
- Transformed data into principal components

---

### 4️⃣ Clustering (Original Data)
- Applied **K-Means clustering**
- Visualized clusters
- Evaluated using:
  - Silhouette Score
  - Davies-Bouldin Index

---

### 5️⃣ Clustering (PCA Data)
- Applied K-Means on PCA-reduced dataset
- Visualized clusters in 2D PCA space
- Evaluated performance using same metrics

---

### 6️⃣ Comparison & Analysis
- Compared clustering performance between:
  - Original feature space
  - PCA-transformed space
- Observed improvements in visualization and cluster separation

---

## 📈 Evaluation Metrics

- **Silhouette Score** → Measures cluster cohesion and separation (higher is better)
- **Davies-Bouldin Index** → Measures cluster similarity (lower is better)

---

## 📊 Key Results

- PCA reduced dataset dimensionality while retaining most variance
- Clustering on PCA data improved visualization clarity
- In some cases, PCA improved clustering performance
- Reduced noise and feature redundancy improved structure understanding

---

## 💡 Key Insights

- PCA is highly effective when features are correlated
- Dimensionality reduction improves visualization significantly
- K-Means performs better when irrelevant features are reduced
- Trade-off: loss of interpretability vs improved efficiency

---

## ⚖️ Advantages of PCA in Clustering

- Reduces computational cost
- Removes redundant features
- Improves visualization in 2D/3D
- Helps in handling multicollinearity

---

## ⚠️ Limitations

- Reduced interpretability of features
- Possible information loss
- Requires proper scaling before application

---

## 🚀 Future Improvements

- Try DBSCAN clustering for comparison
- Use 3D PCA visualization
- Automate optimal K selection using Elbow Method
- Deploy as a Streamlit dashboard

---

## 🧑‍💻 Author

**Meghana C Varghese**  
Data Scientist | Machine Learning Enthusiast  

