# Customer-Segmentation-Using-K-Means-Clustering-Analysis-
This project applies machine learning (K-Means Clustering) to segment customers based on spending behavior, recency, frequency, and demographics. The goal is to help businesses understand customer groups and personalize marketing strategies.
customer-segmentation/
│
├── data/
│   ├── customers.csv
│   └── customers_segmented.csv
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── visuals/
│   ├── income_vs_spending_clusters.png
│   ├── age_vs_spending_clusters.png
│   ├── recency_vs_frequency_clusters.png
│   └── cluster_profile.png
│
└── README.md
Objective

Group customers into meaningful segments

Understand spending patterns

Identify loyal vs at-risk customers

Improve targeted marketing using machine learning insights

🧰 Tools & Technologies

Python

Pandas, NumPy

Matplotlib / Seaborn

Scikit-learn (KMeans, StandardScaler)

Google Colab / Jupyter Notebook

🧹 Data Preparation

Steps performed:

Loaded dataset

Encoded Gender

Cleaned missing values

Selected features for clustering

Scaled numerical features using StandardScaler

Prepared data for K-Means

🤖 Machine Learning – K-Means Clustering
✔ Steps:

Applied Elbow Method to find optimal number of clusters

Trained K-Means model

Added cluster labels to dataset

Calculated cluster profiles

Assigned meaningful segment names

Exported final dataset

✔ Final Segments Identified:
Segment	Description
High-Value Loyal Customers	High spending, recent, frequent purchasers
Low-Value / At-Risk Customers	Low spending, inactive, rarely purchase
📊 Visualizations

Created the following charts:

Annual Income vs Spending Score (clusters)

Age vs Total Spend

Recency vs Frequency

Cluster profile comparison

These visualizations help explain how different customer groups behave.

🔍 Key Insights

High-value customers spend more, buy more frequently, and make recent purchases.

At-risk customers show long gaps since last purchase and low spend.

Younger customers show higher spending and frequency.

Spending Score and Frequency strongly correlate with Total Spend.

🧭 Business Recommendations

Reward high-value customers with loyalty programs.

Send win-back offers to at-risk customers.

Target potential customers with personalized promotions.

Improve customer retention by monitoring recency trends.
