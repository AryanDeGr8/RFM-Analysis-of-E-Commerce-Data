# RFM Analysis of Online Retail Dataset

## Executive Summary

- This project tests the Pareto Principle (20% of customers drive 80% of revenue) using real transactional data from the [Online Retail dataset
 from the UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail). 
 
- The dataset covers 541,909 transactions from a UK-based online retailer selling all-occasion gifts, spanning December 2010 to December 2011. 

- Data includes features such as InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country. 

- Using this data, I performed RFM (Recency, Frequency, Monetary) analysis to segment customers and measure how much revenue is driven by high value customers.

## Key Findings

- High value customers make up ~28.86% of all customers.

- These same high value customers drive ~77.13% of total revenue.

- Most of these high value customers joined before May 2011.

- Customers who buy more frequently tend to also spend more (i.e. higher monetary value).

## Implications & Recommendations

From a business strategy standpoint, the analysis suggests:

- Retain existing high value customers using discounts or promo codes.

- Investigate why the rate of new high value customers declined, to ensure the business continues to acquire them.

- Use targeted, timely discounts for customers who made recent purchases: increasing purchase frequency correlates with increased revenue.

## Conclusion

- The Pareto Principle holds in this dataset: a minority of your customer base contributes the majority of your revenue.

- Focusing efforts on top customers (both retaining and replacing/improving) is a high ROI strategy.

- This RFM analysis completes the segmentation work for this project, enabling actionable insights for marketing, retention, and acquisition strategies.

## Repository Contents

- Visualizations showing distributions, revenue contributions, customer profiles

- Summary statistics & segment definitions

- Jupyter notebook to reproduce analysis

## How to Use / Next Steps

- Clone the repo and download the [Online Retail dataset from the UCI ML Repository](https://archive.ics.uci.edu/dataset/352/online+retail) to reproduce results or adapt to your own customer data.

- Use the RFM segments to tailor marketing campaigns and customer outreach.

- Monitor changes over time — track whether new high value customers are being added.

- Consider further segmentation (clustering, cohort analysis), predictive modeling (e.g. churn prediction), and linking with customer behavior metrics beyond purchases.

## Credits

- Data source: UCI ML Repository — Online Retail Dataset
- Author: Aryan 



