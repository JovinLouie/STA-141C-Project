# Predicting Breast Cancer Subtypes Using Gene Expression Profiles - STA 141C Final Project

By Ada Phoo, Dasha Tymoshchuk, Jenny Xu, Jovin Louie, Ricky Nunez\
Professor Qijia Jiang\
STA 141C: Big Data and High Performance Statistical Computing\
Spring Quarter 2025 - UC Davis

---

We developed a full machine learning pipeline to classify breast cancer subtypes using microarray
gene expression data that was obtained from Kaggle. After exploratory data analysis, we performed
preprocessing steps including normalization, PCA for dimensionality reduction, and class balancing
through upsampling. We trained and evaluated five classification models (Lasso Logistic Regression,
SVM, KNN, Decision Tree, and Random Forest) using 5-fold cross-validation. Lasso on PCA-transformed
data yielded the best performance with high precision, recall, and interpretability, also enabling
identification of subtype-specific marker genes.

## Abstract

This project explores the classification of breast cancer subtypes using high-dimensional gene
expression data. Using a dataset of 151 samples and over 54,000 gene features from the CuMiDa
repository, we applied various machine learning models to predict six cancer subtypes. Principal
Component Analysis (PCA) was used to reduce dimensionality, and Lasso logistic regression emerged as
the most accurate and interpretable model, achieving ~97% test accuracy and perfect AUC score.

## References

- Dataset Source:
  https://www.kaggle.com/datasets/brunogrisci/breast-cancer-gene-expression-cumida/data
