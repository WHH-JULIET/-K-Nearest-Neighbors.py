# 🔍 K-Nearest Neighbors (KNN) Classifier – Custom vs scikit-learn

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** classification algorithm using both:
- A **custom implementation** in pure Python
- The **built-in implementation** from `scikit-learn`

It also includes a hands-on comparison using toy data and the popular Iris dataset.

---

## 📁 Files

- `knn_classifier.py` – Python script containing:
  - Custom KNN class
  - scikit-learn KNN usage
  - Accuracy comparison

---

## ⚙️ How It Works

### 🔧 Custom KNN:
1. Computes **Euclidean distance** between the input and training points
2. Picks the **k nearest neighbors**
3. Returns the **most common label** among those neighbors

```python
def euclidean_distance(x1, x2):
    return np.sqrt(np.sum((x1 - x2) ** 2))
