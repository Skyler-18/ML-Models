# Gradient Descent Implementations from Scratch

Three complete implementations of gradient descent algorithms for linear regression:

1. **Batch Gradient Descent** (`BatchGD.ipynb`)
2. **Stochastic Gradient Descent** (`StochasticGD.ipynb`)
3. **Mini-Batch Gradient Descent** (`MiniBatchGD.ipynb`)

## 🎯 Key Features

- **From-scratch implementations** (No sklearn except for verification)
- **Unified API** across all variants:
  ```python
  gd = GradientDescent(lr=0.01, epochs=100)
  gd.fit(X_train, y_train)
  predictions = gd.predict(X_test)
