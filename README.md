# 🍷 Logistic Regression on Wine Quality Dataset — Exploring Scaling Techniques

In this project, I explored how **feature scaling** (Standard, MinMax, Robust) impacts Logistic Regression's performance using the Wine Quality dataset.

## 📌 Objectives

- Understand the impact of different scaling methods
- Solve convergence issues in Logistic Regression
- Compare model accuracy before and after scaling

---

## 📊 Accuracy Comparison

| Method              | Accuracy (No max_iter) |
|---------------------|------------------------|
| ❌ No Scaling        | 0.755                  |
| 📉 MinMaxScaler      | 0.751                  |
| 💪 RobustScaler      | **0.764**              |

✅ RobustScaler performed best — even without changing `max_iter`.

---

## 🧠 Observations

- Logistic Regression without scaling gives convergence warnings
- Scaling resolves optimization issues
- RobustScaler was most effective for this dataset

---

## 🛠️ Technologies Used

- Python
- scikit-learn
- Pandas, NumPy
- Jupyter Notebook

---

## 📂 Dataset

- Wine Quality dataset (from Kaggle/UCI)

---
