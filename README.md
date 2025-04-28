# Customer Segmentation using RFM Analysis

This project implements **Recency, Frequency, and Monetary (RFM)** analysis to segment customers into distinct groups. The aim is to gain actionable insights to enhance marketing strategies and improve customer retention.

## Project Overview

The primary goal of this project is to analyze customer purchase data using RFM metrics:
- **Recency**: How recently a customer made a purchase.
- **Frequency**: How often the customer makes purchases.
- **Monetary**: How much money the customer spends.

These metrics are used to classify customers into clusters that represent different value segments, guiding targeted marketing actions.

## Contents

- [Objectives](#objectives)
- [Data Processing](#data-processing)
- [Segmentation](#segmentation)
- [Cluster Insights & Recommendations](#cluster-insights--recommendations)
- [Marketing Recommendations](#marketing-recommendations)
- [Dataset Information](#dataset-information)
- [Visualization](#visualization)
- [Analysis Summary](#analysis-summary)

## Objectives

- Segment customers based on RFM metrics
- Provide targeted recommendations for marketing and customer retention
- Identify key characteristics of each customer segment

## Data Processing

The project involves calculating RFM scores based on customer transaction history:

- **Recency**: Days since last purchase
- **Frequency**: Number of purchases
- **Monetary**: Total spend per customer

## Segmentation

Using clustering algorithms, customers are segmented into:

1. **High-Value Customers** (Recent, frequent, and high monetary spending)
2. **Mid-Value Customers** (Moderately recent, regular frequency, moderate spend)
3. **Low-Value Customers** (Infrequent, low spend, less recent)
4. **Dormant Customers** (Rarely purchase, minimal recent interaction)

## Cluster Insights & Recommendations

### High-Value Customers
- Implement exclusive loyalty programs
- Offer personalized recommendations
- Conduct VIP events
- Special anniversary offers

### Mid-Value Customers
- Introduce loyalty programs
- Run limited-time promotions
- Execute cross-sell campaigns
- Collect feedback surveys

### Low-Value Customers
- Run targeted reactivation campaigns
- Offer bundle deals
- Provide educational content
- Limited-time discounts

### Dormant Customers
- Execute win-back campaigns
- Provide reactivation incentives
- Collect feedback to understand dormancy
- Personalized re-engagement offers

## Marketing Recommendations

- Tailor communication based on segments
- Engage actively on social media
- Implement feedback loops for strategy refinement
- Continuously monitor and adapt strategies

## Dataset Information

- **Total Records**: 4372 rows, 8 columns
- **Time Period**: From December 1, 2010, to December 9, 2011 (373 days)
- **Columns**:
  - InvoiceNo
  - StockCode
  - Description
  - Quantity
  - InvoiceDate
  - UnitPrice
  - CustomerID
  - Country

## Visualization

Visual summaries clearly depict segment distributions:
- High-value customers (1415)
- Mid-value customers (1466)
- Low-value customers (786)
- Dormant customers (705)

## Analysis Summary

- Most orders occur on Thursdays around 12 PM.
- Maximum sales are observed in Autumn, likely due to holiday seasons.
- Top countries by order volume and product trends have been identified.
- Insufficient data available for payment, profitability, and customer satisfaction analyses.

