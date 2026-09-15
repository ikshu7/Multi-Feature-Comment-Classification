# Multiclass Comment Classification

A machine learning project for classifying comments into **4 classes (0–3)** using **NLP and structured features**.

## Approach

* Performed EDA and feature engineering on comment metadata.
* Extracted text features using **TF-IDF**.
* Combined TF-IDF features with engineered numerical and categorical features.
* Compared **Logistic Regression, Linear SVM, XGBoost, and LightGBM**.
* Tested an **XGBoost + LightGBM probability ensemble**.
* Evaluation metric: **Macro F1-score**.

## Results

| Model              |  Macro F1 |
| ------------------ | --------: |
| XGBoost            |     0.784 |
| LightGBM           | **0.811** |
| XGBoost + LightGBM |     0.801 |

**Best Model:** LightGBM — **0.811 Macro F1**

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, TF-IDF, XGBoost, LightGBM, Matplotlib, Seaborn.