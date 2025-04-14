# **🧠 Principal Component Analysis (PCA) from Scratch**

In this notebook, I implement Principal Component Analysis (PCA) from scratch using Python, NumPy, and Pandas.

This project serves as a personal mastery checkpoint — showcasing my understanding of PCA’s inner workings, dimensionality reduction, and the underlying linear algebra that powers it.

## 🔍 What This Project Covers
- This notebook walks through PCA step-by-step using first principles, including:
- Standardizing the dataset to ensure fair variance comparison
- Calculating the covariance matrix to capture feature relationships
- Performing eigen decomposition to identify principal components
- Selecting the top eigenvectors based on eigenvalues
- Projecting the original data onto a lower-dimensional space
- Visualizing 3D → 2D projection to show information preservation
- Validating dimensionality reduction by separating classes visually

## 📚 Table of Contents
1. 📊 Generating Synthetic Dataset
2. 📉 Exploring the Dataset
3. ⚖️ Standardizing Features
4. 🧮 Calculating Covariance Matrix
5. 🧠 Eigen Decomposition
6. 🧲 Selecting Principal Components
7. 🔄 Projecting Data onto New Axes
8. 🖼️ Visualizing Dimensionality Reduction
9. ✅ Conclusion

## ⚙️ Technologies Used
- NumPy – Matrix operations and eigen decomposition
- Pandas – Data handling and manipulation
- scikit-learn – Only used for StandardScaler (no PCA module used)
- Plotly – 3D and 2D visualization of data and projections

## 🎯 Why This Project?
This is not a library showcase — this is a “learn by building” initiative. I wanted to understand exactly:

- How PCA identifies directions of maximum variance
- How eigenvectors relate to new feature axes
- What “dimensionality reduction” really means behind the scenes
