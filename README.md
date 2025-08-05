
# 🧠 Unsupervised Learning Project

This project applies multiple **unsupervised learning** techniques on a selected dataset to explore patterns, reduce dimensionality, and extract meaningful insights.

---

## 📦 Project Structure

```
project-root/
│
├── data/                         # Raw and cleaned datasets
│
├── kmeans/                      # KMeans clustering
│   ├── kmeans_model.ipynb
│   ├── kmeans_elbow_plot.png
│   └── kmeans_results.csv
│
├── hierarchical/                # Hierarchical Agglomerative Clustering
│   ├── hierarchical_model.ipynb
│   └── dendrogram_plot.png
│
├── dbscan/                      # Density-Based Spatial Clustering (DBSCAN)
│   ├── dbscan_model.ipynb
│   └── dbscan_clusters.png
│
├── pca/                         # Principal Component Analysis (PCA)
│   ├── pca_analysis.ipynb
│   └── pca_variance_plot.png
│
├── kernel_pca/                  # Kernel PCA (nonlinear dimensionality reduction)
│   ├── kernel_pca_model.ipynb
│   └── kernel_pca_results.csv
│
├── matrix_factorization/        # Matrix Factorization
│   ├── matrix_factorization.ipynb
│   └── latent_features.csv
│
└── README.md                    # This file
```

---

## 🔍 Objectives

- Apply various **unsupervised learning models** to analyze the dataset
- Compare clustering results using different methods
- Reduce data dimensions using PCA and Kernel PCA
- Extract latent features using Matrix Factorization

---

## 🧪 Models and Techniques

### 1. 📊 KMeans Clustering
- Uses Elbow method to choose optimal k
- Assigns data into distinct clusters

### 2. 🧬 Hierarchical Agglomerative Clustering
- Bottom-up clustering
- Visualized with dendrogram

### 3. 🌐 DBSCAN
- Detects clusters based on density
- Handles noise and outliers better

### 4. 📉 PCA (Principal Component Analysis)
- Reduces dataset dimensions while preserving variance
- Useful for visualization and preprocessing

### 5. 🔁 Kernel PCA
- Non-linear PCA using kernel tricks
- Captures complex structures in the data

### 6. 🧱 Matrix Factorization
- Decomposes data matrix into latent features
- Commonly used in recommendation systems

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Explore each model by running the Jupyter notebooks inside each subfolder.

---

## ✅ Recommended Environment

- Python 3.8+
- Jupyter Notebook / JupyterLab
- Required libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `scipy`

---

## 📈 Results & Insights

Each model’s notebook contains:
- Data visualization
- Model implementation
- Cluster/feature interpretation
- Summary of key findings

---

## 🧠 Next Steps

- Try other dimensionality reduction techniques like t-SNE or UMAP
- Apply ensemble clustering
- Fine-tune DBSCAN parameters
- Explore deeper latent structure with NMF or SVD

---

## 🧔 Author

*Prepared with ❤️ by a true data beast.*
