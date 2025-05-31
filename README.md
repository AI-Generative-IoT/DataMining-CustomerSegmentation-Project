#  Unveiling Retail Dynamics: Mining Predictive Insights and Customer Segmentation from Online Retail Data

---

##  Project Overview

This project presents a comprehensive **customer segmentation and predictive modeling pipeline** using the UCI Online Retail Dataset. Leveraging **RFM analysis**, **K-Means clustering**, and **supervised machine learning models** (Logistic Regression, Random Forest, XGBoost, Deep Learning), it explores how businesses can identify, classify, and forecast high-value customers based on behavioral data.

The methodology is grounded in both academic research and practical relevance—supporting targeted marketing, CRM optimization, and long-tail customer value maximization in e-commerce settings.

---

## Objectives

- Understand key purchasing patterns and product associations.
- Segment customers using RFM scores and K-Means clustering.
- Predict high-value customers using ML models based on behavioral signals.
- Provide actionable insights for targeted marketing and retention strategies.

---

## Project Structure

| Section | Description |
|-----------|----------------|
| **1. Data Cleaning** | Handled missing values, duplicate entries, cancellations, and pricing outliers. |
| **2. Feature Engineering** | Created `Revenue`, `Recency`, `Frequency`, `InvoiceTime`, `IsWeekend`, and `CountryCode`. |
| **3. RFM Segmentation** | Assigned RFM scores (1–5) per customer and grouped into strategic segments (e.g., Champions, At-Risk). |
| **4. Clustering** | Applied K-Means to RFM data (k=4), validated using Elbow and Silhouette methods, visualized via PCA. |
| **5. Predictive Modeling** | Built and compared 4 models (LogReg, RF, XGB, DL) to predict top 30% high-value customers. |
| **6. Evaluation & Business Insights** | Measured using Accuracy, ROC AUC, F1-score, and confusion matrix; translated findings into CRM strategies. |

---

## Key Technologies

- **Languages**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `scikit-learn`, `geopandas`, `keras`, `xgboost`
- **ML Models**:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Deep Learning (Neural Network)
- **Evaluation Metrics**: Accuracy, ROC-AUC, F1-score, Confusion Matrix

---

## Key Findings

- 🎯 **Champions (0.3%) generate 65%+ of total revenue**—top priority for loyalty programs.
- 🔄 **Cluster labels** (from K-Means) significantly improved model performance.
- 🔍 **PCA revealed interpretable clusters**, confirming the validity of segmentation.
- 🤖 **Deep Learning outperformed all models** (ROC AUC: **0.932**, F1-score: **0.78**).
- 💡 **High-value customers can be predicted** using only Recency, Frequency, and Cluster ID—no monetary input needed.

---

## Model Performance Summary

| Metric         | Logistic Regression | Random Forest | XGBoost | Deep Learning |
|----------------|---------------------|----------------|----------|----------------|
| Accuracy       | 0.869               | 0.867          | 0.867    | **0.874**      |
| ROC AUC        | 0.923               | 0.917          | 0.920    | **0.932**      |
| F1-score (Class 1) | 0.76             | 0.76           | 0.76     | **0.78**       |

✅ Deep Learning captured non-linear customer behaviors;  
✅ Logistic Regression remains suitable for interpretable business reporting.

---

## Business Impact

- 📈 Real-time prediction of customer value for CRM platforms
- 🛍️ Segment-specific marketing and re-engagement strategies
- 💰 Improved ROI through customer retention and behavior-driven personalization
- 🧩 Deployable models with high interpretability and generalization

---

## Installation

To install the required packages:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn plotly geopandas xgboost keras
