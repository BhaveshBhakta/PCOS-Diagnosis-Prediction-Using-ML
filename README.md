## 👩‍⚕️ PCOS Diagnosis Prediction

### 📌 Project Overview

This project focuses on predicting the **diagnosis of Polycystic Ovary Syndrome (PCOS)** based on a dataset containing various physiological and hormonal parameters. The goal is to develop a machine learning model that can assist in the early and accurate identification of PCOS, contributing to timely intervention and management.

-----

### ⚙️ Technical Highlights

  * **Dataset**: [Kaggle - PCOS Diagnosis Dataset](https://www.kaggle.com/datasets/samikshadalvi/pcos-diagnosis-dataset)
  * **Size**: 1000 entries, 6 columns
  * **Key Features**:
      * Age, BMI, Menstrual\_Irregularity, Testosterone\_Level(ng/dL), Antral\_Follicle\_Count
  * **Approach**:
      * Exploratory Data Analysis (Histograms, Boxplots, Heatmaps)
      * No Missing Values or Duplicates Found
      * Label Encoding (applied to all columns, including numerical, as per the notebook)
      * Data Standardization using `StandardScaler`
      * Handling Class Imbalance with `SMOTE` (Synthetic Minority Over-sampling Technique)
      * Binary Classification (PCOS Diagnosis: `1`, No PCOS: `0`)
      * Models Used:
          * Logistic Regression, Ridge Classifier, SVC, Random Forest, XGBoost, AdaBoost, Gradient Boosting, Bagging, Decision Tree
  * **Best Accuracy**:
      * 99.5% with XGBoost and Gradient Boosting.
      * 99% with Random Forest, Bagging, and Decision Tree.
      * 98.5% with AdaBoost.
      * 95.5% with SVC.

-----

### 🎯 Purpose and Applications

  * Aid medical professionals in **early and accurate PCOS diagnosis**.
  * Support patient screening and risk assessment for PCOS.
  * Contribute to personalized treatment plans based on predictive insights.
  * Facilitate research into the contributing factors and diagnostic markers of PCOS.

-----

### 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/BhaveshBhakta/PCOS-Diagnosis-Prediction-Using-ML.git
cd PCOS-Diagnosis-Prediction-Using-ML
```

Install the necessary libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn xgboost
```

-----

### 🤝 Collaboration

We welcome contributions to improve the project. You can help by:

  * Improving model robustness via hyperparameter tuning and cross-validation.
  * Exploring more advanced feature engineering techniques.
  * Adding explainability (e.g., SHAP or LIME) to understand feature importance in diagnosis.
  * Integrating the model into a user-friendly application for clinical use.
