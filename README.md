# 🛍️ Customer Segmentation using K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)

> **Unsupervised Machine Learning project to segment mall customers into specific marketing groups.**

---

## 📌 Problem Statement
The marketing team wants to identify specific customer groups (segments) to target with different advertising strategies. The challenge is that we have data (Income, Age, Spending) but no labels (no "Target" column).

**Goal:** Use Clustering (K-Means) to group similar customers together.

---

## ⚙️ Workflow
1.  **EDA:** Visualized gender distribution and Income vs Spending patterns.
2.  **Elbow Method:** Used WCSS to find that the optimal number of clusters is **5**.
3.  **Model:** Trained K-Means Clustering algorithm.
4.  **Visualization:** Plotted the 5 distinct customer groups.

---

## 📊 Results (The 5 Segments)
The model identified 5 clear groups:
1.  **VIPs:** High Income, High Spending (Target for luxury items).
2.  **Savers:** High Income, Low Spending.
3.  **Standard:** Average Income, Average Spending.
4.  **Careless:** Low Income, High Spending.
5.  **Sensible:** Low Income, Low Spending.

---

## 🚀 How to Run
1.  Install dependencies: `pip install -r requirements.txt`
2.  Run the notebook: `jupyter notebook segmentation.ipynb`