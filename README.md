# Customer Segmentation with K-Means Clustering

This project applies unsupervised machine learning to segment customers into meaningful groups based on their purchasing behavior. The insights can be used for targeted marketing, personalized offers, and customer retention strategies.

# Project Objectives
   - Perform Exploratory Data Analysis (EDA) on customer transactions.
   - Engineer RFM features (Recency, Frequency, Monetary value).
  -  Apply K-Means clustering to segment customers.
   - Visualize and interpret clusters for actionable business insights.
   - Explore potential extensions for research and real-world deployment.

# Technologies Used

  -  Python: pandas, NumPy, scikit-learn, matplotlib, seaborn
   - Clustering: K-Means, Elbow Method, Silhouette Score
   - Visualization: Seaborn, Matplotlib, cluster heatmaps

# Project Workflow

  - Data Preprocessing: cleaning, missing values, scaling.

  - Feature Engineering: RFM metrics for customer behavior.

   - Clustering: Optimal cluster selection (elbow & silhouette).

   - Evaluation: Segment profiles and intra/inter-cluster distances.
   - Visualization: 2D projections, boxplots of cluster characteristics.

# Results (from my analysis)

  - Best cluster number: 3
  - Silhouette Score: ~0.54
  - Cluster breakdown:
  - Cluster 0 (≈ 40% of customers):
      High Recency (avg ~90 days since last purchase)
      Low Frequency (avg ~2 purchases)
      Low Monetary (avg ~$200 spent)

➝ Churn-risk, low-value customers
 - Cluster 1 (≈ 30% of customers):
    Low Recency (avg ~20 days)
    High Frequency (avg ~10 purchases)
    High Monetary (avg ~$1,200 spent)
➝ Loyal, high-value customers
  - Cluster 2 (≈ 30% of customers):
    Medium Recency (avg ~45 days)
    Medium Frequency (avg ~5 purchases)
    Medium Monetary (avg ~$600 spent)
➝ Potential growth customers
 
