# RFM Analysis of Online Retail Dataset

## Executive Summary

- This project tests the Pareto Principle (20% of customers drive 80% of revenue) using real transactional data from the [Online Retail dataset
 from the UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail). 
 
- The dataset covers 541,909 transactions from a UK-based online retailer selling all-occasion gifts, spanning December 2010 to December 2011. 

- Data includes features such as InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country. 

- Using this data, I performed RFM (Recency, Frequency, Monetary) analysis to segment customers and measure how much revenue is driven by high value customers.

## Key Findings

- High value customers make up ~28.86% of all customers but drive ~77.13% of total revenue.
  
  <img width="859" alt="image" src="https://github.com/AryanDeGr8/RFM-Analysis-of-E-Commerce-Data/blob/main/Distribution%20of%20Customers%20on%20RFM%20Segment.png">
  
  <img width="859" alt="image" src="https://github.com/AryanDeGr8/RFM-Analysis-of-E-Commerce-Data/blob/main/Percent%20of%20Revenue%20Generated%20per%20RFM%20Segment.png">

  This roughly confirms the Pareto Principle which states that 80% of revenue is driven by the top 20% of customers. Our goal is to understand this particular segment of customers.
  
- Most of these high value customers joined before May 2011.
  
  <img width="859" alt="image" src="https://github.com/AryanDeGr8/RFM-Analysis-of-E-Commerce-Data/blob/main/Distribution%20of%20High%20Value%20Customer%20Joining%20Dates.png">

  The huge spike in December 2010 shows a lot of high value customers made their first purchases within this time period followed by a steady decrease in the rate of acquisition of high value customers. 
  
  <img width="859" alt="image" src="https://github.com/AryanDeGr8/RFM-Analysis-of-E-Commerce-Data/blob/main/Cumulative%20Distribution%20of%20High%20Value%20Customer%20Joining%20Dates.png">

  The Cumulative Distribution plot clearly shows more than 900 of the 1262 high value customers joined before May 2011. This is a point of concern since it means the business's rate of acquisition of high value customers has slowed down. However, it should be noted that some of the customers who made their first purchases in the last 7 months maybe haven't had enough time to convert to high value customers.

- Customers who buy more frequently tend to also spend more (i.e. higher monetary value).
  
  <img width="859" alt="image" src="https://github.com/AryanDeGr8/RFM-Analysis-of-E-Commerce-Data/blob/main/Heatmap%20of%20Correlation%20between%20R%2C%20F%20and%20M.png">

  The above heatmap shows great positive correlation between F and M, suggesting customers who buy more frequently also spend more. The correlation between R and M, and R and F, on the other hand is not very strong. This highlights an opportunity to send send discounts and promo codes for customers who recently made a purchase so that they are incentivized to buy from the business again.

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



