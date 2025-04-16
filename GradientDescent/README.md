# Gradient Descent Implementations: From Scratch vs Scikit-Learn
### This repository contains three Jupyter notebooks that demonstrate different implementations of gradient descent algorithms for linear regression, comparing custom implementations with scikit-learn's built-in solutions.

## Notebooks Overview
1. **Stochastic Gradient Descent (SGD) Implementation**
File: `Stochastic Gradient Descent.ipynb`

This notebook compares:
- A custom SGD implementation from scratch
- Scikit-learn's SGDRegressor

Key features:
- Uses the diabetes dataset from sklearn
- Implements SGD using Python class with:
  - Weight updates for each data point
  - Adjustable learning rate and epochs
- Compares performance with scikit-learn's implementation
- Achieves comparable R² scores (0.492 custom vs 0.388 scikit-learn)

2. **Batch Gradient Descent (BGD) Implementation**
File: `Batch Gradient Descent.ipynb`

This notebook demonstrates three approaches:
- Scikit-learn's LinearRegression (baseline)
- Custom Gradient Descent for 1D data
- Custom Batch Gradient Descent for multi-dimensional data

Key features:
- Uses synthetic regression data
- Implements both vanilla GD (1D) and batch GD (multi-dimensional)
- Shows nearly identical results to scikit-learn (R² ≈ 0.669 for all)
- Visualizes the synthetic dataset

3. **Mini-Batch Gradient Descent Implementation**
File: `Mini-Batch Gradient Descent.ipynb`

This notebook implements:
- Custom Mini-Batch Gradient Descent (MBGD)
- Compares with:
  - Analytical solution (LinearRegression)
  - Scikit-learn's SGDRegressor

Key features:
- Uses the diabetes dataset
- Implements MBGD with adjustable batch size
- Shows performance metrics (R² scores):
  - LinearRegression: 0.492
  - Custom MBGD: 0.449
  - SGDRegressor: 0.029

## Key Learning Points
1. Gradient Descent Variants:
- Batch GD: Uses entire dataset for each update
- Stochastic GD: Uses one random sample per update
- Mini-Batch GD: Compromise using small random batches

2. Implementation Comparisons:
- Custom implementations can match scikit-learn's performance
- Vectorization is crucial for efficiency
- Learning rate and epochs significantly affect results

3. Practical Considerations:
- Batch GD is stable but computationally expensive
- SGD is noisy but can escape local minima
- Mini-Batch offers a good balance
