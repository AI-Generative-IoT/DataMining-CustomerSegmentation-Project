# Unveiling Retail Dynamics: "Mining Predictive Insights and Customer Segmentation from Online Retail Data"

---

## Project Overview

This project focuses on **customer behavior analysis**, **segmentation**, and **predictive modeling** using an **online retail dataset**.  
The goal is to clean and transform transactional data, extract insights through **RFM analysis** and **clustering**, and build models that **predict high-value customers** to inform better marketing strategies.

---

## Project Structure

| Section | Description |
|:-------:|:------------|
| **1. Data Cleaning** | Handling missing values, cancellations, non-product codes, outliers, and standardizing features |
| **2. Feature Engineering** | Creating new features: Revenue, Invoice Month/Day/Hour, Weekend flag, Country codes |
| **3. Exploratory Data Analysis (EDA)** | Visualizing orders and revenues across countries, months, days, and hours |
| **4. RFM Analysis and Customer Segmentation** | Assigning RFM scores, mapping customer segments, and visualizing segment performance |
| **5. Clustering (K-Means)** | Applying K-Means clustering on standardized RFM data to uncover hidden customer groups |
| **6. Predictive Modeling** | Building Logistic Regression and Random Forest models to predict high-value customers |
| **7. Business Recommendations** | Using insights to drive marketing strategies and customer targeting |

---

## Key Techniques Used

- **Data Preprocessing**: Missing value handling, feature extraction, outlier removal
- **Exploratory Data Analysis**: Seaborn, Matplotlib, Plotly, Geopandas
- **Segmentation**:  
  - RFM (Recency, Frequency, Monetary) scoring  
  - K-Means clustering
- **Predictive Modeling**:
  - Logistic Regression
  - Random Forest Classifier
- **Model Evaluation**: Accuracy, ROC-AUC, Precision, Recall, F1-Score
- **Feature Importance** analysis for marketing optimization

---

## Key Insights

- **Champions** (5% of customers) contribute the majority of revenue.
- **Thursday** is the most active purchasing day.
- **Revenue peaks** around November and December, hinting at strong seasonality.
- **Top 10 products** vary significantly across customer segments.
- **Predictive models** achieved **87%+ accuracy** in identifying high-value customers.

---

## Project Highlights

- 📈 **87.4% Accuracy and 93% ROC-AUC** with Logistic Regression
- 🌍 **World map** showing customer distribution
- 🛒 **Top product analysis** by customer segment
- 🎯 **Marketing strategy recommendations** based on data-driven segmentation
- 🔥 **Professional, production-ready** Python code with clean structure

---

## ⚙Requirements

Install required libraries via:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn plotly geopandas
