# RFM-and-CLV-Analysis-of-E-Commerce-Data
RFM and CLV Analysis of Online Retail Dataset

🧾 Project Summary

This project investigates whether the Pareto Principle (“20% of customers drive 80% of revenue”) holds true for e-commerce, using the Online Retail dataset from the UCI Machine Learning Repository. With this work, my RFM (Recency, Frequency, Monetary) analysis is complete.

📚 Dataset Description

Name: Online Retail (UCI ML Repository) 
UCI Machine Learning Repository

Period Covered: 01 December 2010 to 09 December 2011 
UCI Machine Learning Repository

Size: ~541,909 transactions 
UCI Machine Learning Repository

Features include:

InvoiceNo, StockCode, Description

Quantity, InvoiceDate, UnitPrice

CustomerID, Country 
UCI Machine Learning Repository

🔍 Key Findings

High value customers make up 28.86% of the total customers.

These high value customers drive 77.13% of the revenue.

Majority of the high value customers joined before May 2011.

Customers who buy more frequently also spend more money in general.

📈 Implications & Recommendations

Retain existing high value customers using discounts and promo codes.

Investigate what caused the rate of new high value customers to drop, so the business consistently acquires them.

Target recent purchasers with timely discounts — increasing purchase frequency correlates with revenue growth.

🧮 Conclusion

The Pareto Principle holds in this dataset: a minority of customers generate the majority of revenue.

Focusing on your top customers (both retaining and growing that segment) yields high return on investment.

RFM segmentation enables actionable strategies for marketing, customer retention, and acquisition.

🗂 Repository Structure
├── data/
│     └── raw/                 # Original Online Retail dataset files
│     └── processed/           # Cleaned/aggregated data, RFM features
├── notebooks/
│     └── EDA_and_visualizations.ipynb
│     └── RFM_analysis.ipynb
├── src/
│     └── preprocessing.py
│     └── rfm_calculation.py
│     └── visualization_helpers.py
├── visualizations/
│     └── revenue_contribution.png
│     └── rfm_segments_distribution.png
├── README.md                  # This file
└── requirements.txt           # Python / R dependencies

🔧 How to Use / Reproduce

Clone the repo.

Install dependencies listed in requirements.txt.

Load the raw data from the UCI repository.

Preprocess (clean, filter cancellations/returns, compute total spend).

Calculate RFM metrics for each customer.

Segment customers based on RFM scores.

Generate visualizations and summary statistics as in this project.

🤝 Next Steps

Apply this RFM framework on your own business/customer data to see how it behaves.

Monitor changes over time: are you losing or gaining high-value customers?

Combine RFM with cohort analysis or predictive modeling (e.g. churn prediction).

Use segments for personalized marketing: separate offers for high value vs. low-value or inactive customers.

⚠️ Data Source & License

Data Source: Online Retail Dataset, UCI Machine Learning Repository 
UCI Machine Learning Repository

License: CC BY 4.0 (UCI dataset licensing) 
UCI Machine Learning Repository

💡 Author

Your Name Here
