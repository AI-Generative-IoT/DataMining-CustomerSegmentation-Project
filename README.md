🔍📊 Scientific Abstract  

Unveiling Retail Dynamics: Mining Predictive Insights and Customer Segmentation from Online Retail Data  

This study investigates online retail dynamics by integrating customer segmentation and predictive analytics using the UCI Online Retail dataset. The primary objective is to identify behaviorally distinct customer groups and to accurately predict high-value customers (top 30% by revenue contribution) through a unified analytical pipeline. The methodology combines RFM analysis (Recency, Frequency, Monetary Value), K-Means clustering, and multiple supervised machine learning models—including Logistic Regression, Random Forest, XGBoost, and Deep Learning—to balance interpretability and predictive performance.  

🧹 After rigorous data cleaning and feature engineering, customers were segmented based on purchasing behavior. Cluster validity was confirmed using Elbow and Silhouette methods, with PCA-based visualizations revealing well-separated and interpretable customer groups. Notably, the Champions segment represented approximately 0.3% of customers while generating over 65% of total revenue, highlighting strong revenue concentration effects.  

🤖 In the predictive modeling phase, a Deep Learning model achieved the highest performance (ROC AUC = 0.932, F1-score = 0.78), effectively capturing non-linear behavioral patterns. Logistic Regression, while slightly less performant, demonstrated strong robustness and transparency, making it well-suited for business reporting and decision support. A key empirical finding is that high-value customers can be reliably predicted using only Recency, Frequency, and cluster membership, without direct monetary inputs.  

💡 The results demonstrate that combining unsupervised segmentation with supervised learning provides a powerful and scalable framework for customer value prediction, CRM optimization, and data-driven marketing strategies in e-commerce environments. The proposed approach is both scientifically grounded and practically deployable, offering actionable insights for customer retention, personalization, and revenue maximization.  

🔑 Keywords: Customer Segmentation, RFM Analysis, K-Means Clustering, Predictive Modeling, E-Commerce Analytics, Machine Learning, Customer Value Prediction.  
