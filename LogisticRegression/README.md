# Logistic Regression from Scratch

This project demonstrates multiple implementations of **Logistic Regression** from scratch using Python and NumPy. It serves both as an educational exercise and a solid foundation for understanding how logistic regression works under the hood.

## 🧠 Key Implementations

1. **Logistic Regression using Sklearn**  
   A baseline using `sklearn.linear_model.LogisticRegression`.

2. **Perceptron with Step Function**  
   A simple binary classifier using the classic perceptron rule.

3. **Perceptron with Sigmoid Activation**  
   Uses sigmoid instead of step function to introduce probability outputs.

4. **Logistic Regression using Gradient Descent**  
   Core implementation from scratch with:
   - Sigmoid activation
   - Binary cross-entropy loss
   - Manual weight updates using gradient descent

## 📊 Dataset

- **Generated using `make_classification`** from Scikit-learn.
- Contains 2 features and binary labels.
- Well-separated classes for clear visualization and convergence.

## 📈 Visualization

A scatter plot is used to visualize the 2D feature space and color-coded class labels.
