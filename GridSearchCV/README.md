# 🔍 SVC Hyperparameter Tuning with GridSearchCV

This project demonstrates how to improve the performance of a **Support Vector Classifier (SVC)** model using **GridSearchCV** from the `scikit-learn` library by tuning its hyperparameters.

---

## 📌 Project Overview

In this project, we:
- Train a baseline SVC model on a sample dataset.
- Use **GridSearchCV** to perform an exhaustive search over specified parameter values.
- Select the best combination of hyperparameters.
- Evaluate the optimized model on test data.
# ⚙️ Hyperparameters Tuned

Using `GridSearchCV`, we explored different combinations of the following parameters:

```python
parameters = [
    {'C': [1, 10, 100, 1000], 'kernel': ['linear']},
    {'C': [1, 10, 100, 1000], 'kernel': ['rbf'], 'gamma': [0.1, 0.2, ..., 1]}
]