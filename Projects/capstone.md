---
layout: page
title: Phishing Website Detection (Capstone Project)
---

# Phishing Website Detection (Capstone Project)

This Capstone project applied a wide range of machine learning techniques to classify phishing websites using **11,055 URLs** and **88 engineered features**, including lexical patterns, domain metadata, and webpage characteristics.

---

## 🔍 Problem Overview
Phishing attacks continue to escalate, targeting individuals, businesses, and financial institutions. Traditional rule-based detection systems fail to catch new, evolving patterns.  
The goal of this project was to develop a **data-driven, adaptable ML model** capable of identifying phishing URLs with high accuracy and interpretability.

---

##  Machine Learning Methods Used
This project demonstrates one of the most comprehensive model comparisons in my portfolio, including:

### **Supervised Learning Models**
- Logistic Regression  
- Polynomial Regression (Degree 2 & 3)  
- K-Nearest Neighbors (multiple distance metrics)  
- Linear Support Vector Machine  
- RBF Support Vector Machine  
- Decision Tree  
- Random Forest  
- Gradient Boosting Classifier  
- XGBoost Classifier  
- Ridge, Lasso, and Elastic Net (regularized models)

### **Unsupervised & Dimensionality Reduction**
- K-Means Clustering (k = 2,3,4)  
- PCA for visualization & variance analysis  
- Feature importance ranking across multiple methods

### **Additional Components**
- Feature scaling (Standardization, Normalization)  
- Outlier detection  
- Train/Val/Test splitting  
- Extensive hyperparameter tuning  
- Ensemble comparison  
- ROC/AUC evaluation for all top models  
- Confusion matrix & error analysis  
- Overfitting mitigation

---

## Key Results
After testing more than a dozen models:

- **XGBoost achieved the best performance**, with:
  - **Accuracy ≈ 0.96**
  - **AUC ≈ 0.99**
  - Excellent recall for phishing class
- Gradient Boosting and Random Forest also performed competitively  
- SVM (RBF) achieved strong performance but with higher computational cost  
- Logistic Regression performed surprisingly well given its simplicity

A key insight was that **lexical and host-based features** were the strongest indicators of malicious behavior.

---

##  Artifacts
These will be uploaded into this GitHub portfolio:

- **Executive Summary (PDF) — Non-technical report**  
- **Technical Report (PDF)** (full modeling, evaluation, visuals)  
- **Visuals**
  - ROC curve
  - Confusion matrix
  - Feature importance bar charts
  - PCA scatterplot for clustering
  - Performance comparison tables

---

## Takeaways
This Capstone demonstrates:

- End-to-end ML development  
- Deep model comparison across >10 algorithms  
- Meaningful feature engineering  
- Strong evaluation using AUC, ROC, and interpretability  
- Real-world applicability to cybersecurity & fraud detection  

It is the most complete machine learning project of my graduate program, integrating lessons from **Machine Learning, Advanced ML, Data Science, and Applied ML coursework** at Boston University.

