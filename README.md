# 🧪 KNN from Scratch – Flower and News Classification

This repository contains the full implementation of a **K-Nearest Neighbors (KNN)** classifier written from scratch in Python. The project was developed as part of a university lab assignment to understand the internal workings of KNN, evaluate its performance using custom metrics, and compare it against the built-in `scikit-learn` implementation.

---


## 🎯 Objectives

- Implement the KNN classification algorithm manually using NumPy.
- Apply the model to two datasets:
  - Iris flower dataset (numerical)
  - 20 Newsgroups dataset (text classification)
- Evaluate using:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-score
- Compare with `sklearn.neighbors.KNeighborsClassifier`.
- Auto-tune best `k` and split ratios for both datasets.

---

## 📦 Requirements

- Python 3.8+
- Libraries:
  - `numpy`
  - `sklearn` (for comparison and data loading)

Install dependencies:

```bash
pip install numpy scikit-learn
