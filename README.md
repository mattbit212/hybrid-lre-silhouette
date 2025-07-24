# Hybrid LRE-Silhouette: Hybrid Geometric and Validity Measures for Optimal Cluster Estimation

📌 **Status**: Under review at *International Journal of Electrical and Computer Engineering (IJECE)*  
🔍 **Abstract Available**: [Link to Prosiding if available]  
🧠 **Author**: [Akhmad Yusuf](https://github.com/mattbit212)

---

## 📖 Overview

**Hybrid LRE-Silhouette** is a hybrid method that integrates geometric analysis (LRE) and structural evaluation (Silhouette Score) to estimate the optimal number of clusters (*k*) in unsupervised learning. This unified approach addresses the limitations of prior methods by balancing curve sensitivity with intra-cluster compactness.

This repository includes:
- The complete codebase for the Hybrid LRE-Silhouette method
- Benchmark experiments on 8 datasets (including MNIST and Digits)
- Statistical validation using Wilcoxon signed-rank test and rank-biserial effect size
- Visualization scripts and experimental result files

---

## 📈 Key Features

- ✅ Automatic cluster number estimation (*k*)
- ✅ Normalized hybrid scoring (LRE + Silhouette)
- ✅ Benchmark comparison with 7 other methods: Gap Statistic, X-means, PG-means, Dip-means, etc.
- ✅ Statistical testing (Wilcoxon + effect size)
- ✅ Visual outputs: heatmaps, bar plots, runtime comparisons

---

## 📂 Repository Structure

hybrid-lre-silhouette/
├── scripts/ # Google Colab
├── results/ # Output images and Excel results
├── data/ # (Optional) Placeholder or links for datasets
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── LICENSE # Open-source license
