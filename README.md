# task-8-K-mean-elevatelabs
This repo contains tasks from my internship "ElevateLabs"

# Task 8: K-Means Clustering

## 📌 Objective
Perform unsupervised learning using **K-Means clustering** on a dataset (Customer Segmentation).

## 🛠 Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib, Seaborn

## 📊 Steps
1. Load and explore dataset.
2. Preprocess data (scaling).
3. Apply **K-Means algorithm**.
4. Use **Elbow Method** to find optimal clusters.
5. Evaluate with **Silhouette Score**.
6. Visualize clusters using PCA.

## 📈 Results
- Optimal K: 5  
- Silhouette Score: ~0.55  
- Clear segmentation visible in PCA 2D plot.

## 📁 Dataset
[Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

## 🚀 How to Run
```bash
pip install pandas matplotlib scikit-learn seaborn
python kmeans_clustering.py
