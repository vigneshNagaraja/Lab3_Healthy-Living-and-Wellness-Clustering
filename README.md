# Lab3_Healthy-Living-and-Wellness-Clustering


##  Overview

This project explores unsupervised machine learning techniques to segment individuals based on health and wellness behaviors. Using a simulated dataset of 200 entries, we applied **K-Means clustering** and **Principal Component Analysis (PCA)** to uncover distinct wellness profiles and simplify data interpretation.

---

##  Methods Used

### ✅ 1. Exploratory Data Analysis (EDA)
- Histograms to explore distribution of exercise, meals, sleep, stress, and BMI
- Correlation heatmap to check for multicollinearity

### ✅ 2. K-Means Clustering
- Optimal cluster count selected using the **Elbow Method**
- **Silhouette Score** used to evaluate cluster quality
- Compared **k=3** and **k=4** to validate segmentation

### ✅ 3. PCA for Dimensionality Reduction
- Reduced features from 5D to 2D using **PCA**
- Applied KMeans again on PCA-transformed data
- Visualized cluster separation in PC1 vs PC2 space

---

## Key Visualizations

- **Figure 1**: Distribution Histograms
- **Figure 2**: Correlation Heatmap
- **Figure 3**: Elbow Method Plot
- **Figure 4**: Silhouette Score Comparison (K=3 vs K=4 vs PCA)
- **Figure 5**: Clusters Before PCA (Exercise vs BMI)
- **Figure 6**: Clusters After PCA (PC1 vs PC2)

---

##  Insights

- **Three distinct clusters** were identified:
  1.  At-Risk (low exercise and meals)
  2.  Balanced Lifestyle (good sleep, low stress)
  3.  Stressed but Active (high activity and stress)

- **K=3** yielded the best silhouette score (**0.152**) vs **K=4** (**0.131**)
- PCA slightly reduced the score (**0.138**) but improved visual interpretability

---

## Files

| File                     | Description                              |
|--------------------------|------------------------------------------|
| `Lab_3 (4).ipynb`        | Final Jupyter notebook with code and plots |
| `figure6_pca_clusters.png` | PCA-based cluster visualization         |
| `LAB3.pdf`               | Final APA-formatted report (if applicable) |

---

##  Conclusion

This project demonstrates how clustering and PCA can uncover meaningful subgroups in wellness data. These insights can guide **personalized wellness programs** for different population segments.

---


