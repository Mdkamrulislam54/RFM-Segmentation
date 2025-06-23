# 🧠 RFM Customer Segmentation Project
# 🎯 Goal
Segment customers based on their purchasing behavior using the RFM (Recency–Frequency–Monetary) model and K-Means clustering to enable targeted marketing strategies .
![Alt text](https://github.com/Mdkamrulislam54/RFM-Segmentation/blob/338a07751cefb64394ed982b1af663ecbbce422c/Customer-segmentation.png)

# 🔍 Business Context
You’re an online store manager looking to drive higher ROI through customized campaigns. By grouping customers into meaningful clusters—such as loyal, slipping, or promising—you can tailor rewards, recommended products, or win-back offers .

# 🧩 Methodology & Workflow
Data Overview & Cleansing
Imported UK-based online retail transactional data from Dec 2010–Dec 2011. Removed missing or anomalous entries; standardized data types .

RFM Metrics Calculation
• Recency: Days since last purchase
• Frequency: Total transactions per customer
• Monetary: Total spend per customer

![Alt text](https://github.com/Mdkamrulislam54/RFM-Segmentation/blob/338a07751cefb64394ed982b1af663ecbbce422c/rfm-analysis.png)

Data Preparation
Grouped data at the customer level and applied scaling—utilizing techniques like log-transformations and dimensionality reduction pipelines .

Cluster Analysis
Selected cluster count using Elbow Curve and silhouette scores. Applied K-Means and profiled clusters:

Cluster 0: Low‑frequency, low‑spend, likely slipping

Cluster 1: High‑frequency, high‑spend, loyal

Cluster 2: Frequent but moderate spend; promising

Actionable Recommendations
• Loyal: Launch loyalty programs, offer free shipping, encourage advocacy
• Promising: Upsell via targeted product suggestions
• Slipping: Re‑engage with promotions or new product launches

# ✅ Why It’s Valuable

Data-driven segmentation** fuels personalized marketing

Clustering insights simplify customer lifecycle management

Scalable approach—fully reproducible and adaptable to other retail data


