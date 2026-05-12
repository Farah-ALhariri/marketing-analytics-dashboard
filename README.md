# Marketing Analytics & Customer Behavior Dashboard

I built this dashboard to analyze customer spending and marketing campaign performance using the iFood marketing dataset. The project focuses on understanding customer behavior, campaign effectiveness, purchasing patterns, and retention trends through interactive Power BI dashboards and advanced KPI analysis.

---

## Project Goal

The main objective of this project was to move beyond static reporting and explore the relationship between customer demographics, purchasing behavior, and marketing campaign performance.

Key business questions included:

* Which customer groups generate the highest revenue?
* Which marketing campaigns drive the best conversion rates?
* How does customer behavior vary across income and age segments?
* At what point does customer inactivity become a retention risk?
* Which product categories contribute most to total sales?

The dashboard was designed to help marketing teams make more data-driven decisions around customer targeting, retention strategies, and promotional effectiveness.

---

## What’s in the Data?

The analysis is based on a retail customer and marketing dataset containing approximately 2,200 customer records.

### Dataset Includes:

### Customer Demographics
* Age
* Income
* Education
* Household composition

### Product Spending Categories
* Wines
* Fruits
* Meat
* Fish
* Sweets
* Gold products

### Marketing Campaign Data
* Campaign acceptance rates
* Final campaign responses
* Discount usage behavior

### Purchase Channels
* Web purchases
* Catalog purchases
* In-store purchases

---

# Dashboard Walkthrough

## 1. Executive Summary

![Executive Summary](executive_summary.png)

This page provides a high-level overview of overall business and marketing performance.

### Key Metrics:
* Total Revenue
* Total Customers
* Average Customer Spend
* Campaign Conversion Rates

### Key Findings:
* Wine products contributed more than 54% of total revenue
* Revenue concentration was heavily driven by a limited number of high-spending customers
* Certain customer segments generated significantly higher purchasing activity

### Business Impact
* Helps stakeholders quickly identify top-performing product categories
* Supports revenue-focused marketing and product strategies
* Improves visibility into customer purchasing behavior

---

## 2. Customer Behavior & Retention

![Customer Behavior](customer_behavior.png)

This page focuses on customer engagement, purchasing frequency, and retention behavior.

### Analysis Included:
* Customer inactivity tracking
* Website visit analysis
* Customer segmentation by age and income
* Purchase frequency evaluation

### Key Findings:
* A clear customer retention drop-off occurs around 40 days of inactivity
* Customers with higher website engagement show stronger purchasing behavior
* Spending behavior varies significantly across income groups

### Business Impact
* Helps identify at-risk customers before churn occurs
* Supports customer retention and re-engagement strategies
* Assists in optimizing customer targeting efforts

---

## 3. Campaign Performance

![Campaign Performance](campaign_performance.png)

This page evaluates the effectiveness of marketing campaigns and promotional behavior.

### Analysis Included:
* Campaign conversion rates
* Discount usage behavior
* Customer response segmentation
* Campaign performance comparison

### Key Findings:
* The latest campaign achieved a 15.4% conversion rate
* “Bargain Hunters” responded more positively to discount-driven campaigns
* Full-price customers showed lower campaign engagement rates

### Business Impact
* Helps marketing teams optimize promotional spending
* Supports better campaign targeting strategies
* Improves understanding of customer response behavior

---

## 4. Product Spending Correlation

![Product Correlation](product_correlation.png)

A correlation analysis was performed using Python to identify relationships between purchasing categories.

### Key Findings:
* Customers purchasing meat products were also highly likely to purchase fruits and fish
* Several product categories showed strong positive purchasing correlations
* Cross-category purchasing patterns suggest bundle opportunities

### Business Impact
* Supports cross-selling and bundled promotion strategies
* Helps improve product recommendation planning
* Assists in identifying high-value product relationships

---

# Tech Stack

### Dashboard & BI Tools
* Power BI Desktop
* Power Query
* DAX

### Data Processing & Analysis
* Python
* Pandas
* Seaborn
* Matplotlib

### Data Source
* CSV dataset (`ifood_df.csv`)

---

# KPI & DAX Measures

The project includes several custom KPI calculations and analytical measures, including:

* Conversion Rate (CVR%)
* Discount Usage Rate
* Average Spend per Customer
* Customer Retention Segmentation
* Customer Activity Binning
* Revenue Contribution Analysis

---

# Setup & Usage

1. Download the following files:
   * `Marketing_Performance_Analysis.pbix`
   * `ifood_df.csv`

2. Open the `.pbix` file using Power BI Desktop

3. If the visuals do not load:
   * Go to:
     `Transform Data → Data Source Settings`
   * Update the dataset file path
   * Click Refresh

4. Interact with the dashboard using filters and slicers to explore customer segments, income groups, product categories, and campaign performance.

---

# Future Improvements

* Build a predictive churn model to identify at-risk customers earlier
* Add automated customer retention alert systems
* Integrate real-time campaign monitoring
* Expand segmentation using RFM analysis
* Develop forecasting models for customer lifetime value

---

# Key Business Insights & Recommendations

* Wine products generate the majority of total revenue, suggesting strong customer preference and premium upselling opportunities
* Customer inactivity sharply increases after approximately 40 days, indicating a critical retention window for re-engagement campaigns
* “Bargain Hunters” respond significantly better to discount-based campaigns than full-price shoppers
* Cross-category purchasing behavior suggests opportunities for bundled promotions between related products
* Higher-income customer segments demonstrate stronger average purchase values, supporting premium-focused targeting strategies
* Personalized marketing campaigns may improve conversion rates while reducing customer churn

---

# Final Note

This project demonstrates how customer behavior, campaign performance, and purchasing data can be transformed into actionable business insights using Power BI, DAX, customer segmentation, and advanced analytics techniques.
