# Customer-Segmentation-using-RFM-Analysis

Customer Segmentation using RFM [Recency, Frequency, Monetary]
This project builds an end-to-end pipeline to analyze e-commerce transactions, compute RFM scores per customer, and segment users with K-Means clustering to drive targeted marketing. It includes data cleaning, time-window exploration, RFM computation, cluster selection, segment profiling, and actionable recommendations. 

**What’s inside**

Data & EDA [Exploratory Data Analysis]: 541,909 rows × 8 columns; coverage from 2010-12-01 to 2011-12-09; null handling, date parsing, and derived fields for date/time analysis. 

RFM computation: Recency in days from last purchase, Frequency as unique invoices, Monetary as total spend per customer. Weighted and concatenated RFM scores included. 

Clustering: Standardized RFM features → Elbow and Silhouette checks → K-Means with 4 clusters; cluster summaries with mean R, F, M and customer counts. 

Segment profiling: Interpretable segments (e.g., high-value/engaged, loyal-but-inactive, at-risk, low-engaged) with behaviors and levers to pull. 

Marketing playbook: Win-back offers, loyalty/VIP perks, cross-sell/upsell, referral nudges, and lifecycle emails aligned to each segment. 

Visuals: Correlation heatmap and 3D scatter of clusters; weekly/hourly order patterns; seasonal/monthly distributions. 


**Notable findings**

Unique customers: 4,372. Top revenue category: DOTCOM POSTAGE (≈ 206,245.48). Top orderers and top 10 StockCodes identified. 

Clusters (example snapshot): a tiny elite cohort with extremely high Frequency/Monetary, a sizable recent-buyers group with moderate spend, and a large long-tail with low activity—ideal targets for re-engagement or nurture. 


**Stack**
Python, pandas, NumPy, scikit-learn, seaborn, matplotlib. 
