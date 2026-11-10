# Customer Purchase Behavior Analysis | Retail Fashion

## 1. Project Overview

This project focuses on analyzing customer purchase behavior in the retail fashion industry using Microsoft Excel.

The objective is to understand customer preferences, purchasing patterns, revenue contribution, product category performance and customer satisfaction.

An interactive Excel dashboard was developed using PivotTables, PivotCharts, calculated columns and slicers to transform raw customer data into meaningful business insights.

## 2. Business Problem Statement

A retail fashion company wants to understand its customers' purchasing behavior to improve business performance, marketing strategies and inventory planning.

The company needs insights into:

- Which product categories generate the highest revenue?
- Which seasons contribute more to sales?
- Which age groups and genders contribute most to revenue?
- How do shipping and payment preferences vary?
- How are discounts associated with customer spending?
- What is the distribution of customer review ratings?
- How does purchase frequency vary among customers?
- How do previous purchases relate to current purchase amounts?

## 3. Project Objectives

- Understand customer purchasing behavior.
- Analyze revenue across different product categories and seasons.
- Identify valuable customer segments.
- Examine shipping and payment method preferences.
- Analyze discount usage and customer review ratings.
- Create an interactive Excel dashboard.
- Generate actionable business insights and recommendations.

## 4. Dataset Description

**Dataset:** `shopping_behavior_updated.csv`

The dataset contains:

- Total Records: 3,900
- Total Columns: 18
- Unique Customers: 3,900
- Missing Values: 0

### Dataset Columns

1. Customer ID
2. Age
3. Gender
4. Item Purchased
5. Category
6. Purchase Amount (USD)
7. Location
8. Size
9. Color
10. Season
11. Review Rating
12. Subscription Status
13. Shipping Type
14. Discount Applied
15. Promo Code Used
16. Previous Purchases
17. Payment Method
18. Frequency of Purchases

## 5. Tools and Technologies

- Microsoft Excel
- Excel Tables
- Excel Formulas
- Data Cleaning
- Data Preprocessing
- PivotTables
- PivotCharts
- Interactive Slicers
- Data Visualization
- Business Analysis

## 6. Data Cleaning and Preprocessing

The following data preparation activities were performed:

- Checked dataset structure and column names.
- Verified missing values and duplicate records.
- Reviewed categorical and numerical columns.
- Converted the dataset into an Excel Table.
- Created calculated columns for further analysis.

### Derived Columns

**Age Group**

Customers were classified into three age groups:

- Young: Age 25 or below
- Adult: Age 26 to 50
- Senior: Age above 50

**Revenue**

Purchase Amount (USD) was used as the revenue measure.

**Subscription Flag**

- Yes = 1
- No = 0

## 7. Dashboard and Data Visualization

An interactive Excel dashboard was developed using PivotTables and PivotCharts.

### Key Performance Indicators (KPIs)

- Total Revenue: $233,081
- Total Customers: 3,900
- Average Purchase Amount: $59.76
- Average Review Rating: 3.75

### Dashboard Visualizations

1. Revenue by Product Category
2. Revenue by Season
3. Revenue by Age Group and Gender
4. Purchase Amount vs. Shipping Type
5. Purchase Amount vs. Payment Method
6. Impact of Discounts and Promo Codes
7. Customer Review Rating Distribution
8. Customer Purchase Frequency
9. Customer Loyalty Analysis

### Interactive Filters

The dashboard includes slicers for:

- Gender
- Category
- Season
- Subscription Status
- Location

These filters allow users to explore customer segments and analyze different business dimensions.

## 8. Insights and Findings

### 1. Revenue by Product Category

- Clothing generated the highest revenue of $104,264.
- Accessories contributed $74,200.
- Footwear generated $36,093.
- Outerwear generated $18,524.

**Insight:** Clothing is the leading revenue-generating category, contributing approximately 44.7% of total revenue. Outerwear contributes the least.

### 2. Revenue by Season

- Fall: $60,018
- Spring: $58,679
- Winter: $58,607
- Summer: $55,777

**Insight:** Fall recorded the highest revenue, while Summer recorded the lowest. Revenue is relatively balanced across all four seasons.

### 3. Revenue by Age Group and Gender

- Adult Male: $73,201
- Adult Female: $36,770
- Senior Male: $60,595
- Senior Female: $27,885
- Young Male: $24,094
- Young Female: $10,536

**Insight:** Adult customers contribute the highest revenue among the age groups. Male customers contribute more revenue than female customers across all three age groups.

### 4. Purchase Amount vs. Shipping Type

- Free Shipping: $40,777
- Store Pickup: $38,931
- Express: $39,067
- Standard: $38,233
- Next Day Air: $37,993
- 2-Day Shipping: $38,080

**Insight:** Free Shipping generates the highest revenue among the shipping types, while Next Day Air generates the lowest.

### 5. Purchase Amount vs. Payment Method

- Credit Card: $40,310
- Cash: $40,002
- PayPal: $40,109
- Debit Card: $38,742
- Venmo: $37,374
- Bank Transfer: $36,544

**Insight:** Credit Card has the highest revenue contribution among the payment methods, while Bank Transfer has the lowest.

### 6. Impact of Discounts

- Purchases without discounts: $133,670
- Purchases with discounts: $99,411

**Insight:** Purchases without discounts contribute more total revenue than purchases with discounts.

### 7. Customer Review Ratings

- Average Review Rating: 3.75 out of 5.

**Insight:** Customers provide an average rating of 3.75, indicating generally positive customer feedback, with opportunities to improve customer satisfaction.

### 8. Customer Purchase Frequency

The dashboard compares the number of customers across different purchase frequency groups.

**Insight:** Customer purchasing frequency varies across weekly, monthly, quarterly and other purchasing intervals. Understanding these patterns can help the business plan targeted marketing campaigns.

### 9. Customer Loyalty Analysis

The analysis explores the relationship between customers' previous purchase counts and their current purchase amounts.

**Insight:** Previous purchase history can help the business explore customer spending patterns and identify potential loyal customer segments.

## 9. Business Recommendations

Based on the analysis, the following recommendations can be considered:

1. **Product Strategy:** Maintain sufficient inventory for Clothing, the highest revenue-generating category, and explore strategies to improve Outerwear sales.

2. **Seasonal Planning:** Maintain inventory across all seasons and introduce targeted promotional campaigns during Summer.

3. **Customer Segmentation:** Develop targeted marketing campaigns for Adult and Senior customer segments while exploring opportunities to increase engagement among Young customers.

4. **Shipping Strategy:** Evaluate the performance and cost of Free Shipping offers to understand their contribution to customer purchases.

5. **Payment Options:** Continue supporting popular payment methods and investigate ways to improve adoption of other payment options.

6. **Discount Strategy:** Evaluate discount campaigns based on profitability and customer response rather than revenue alone.

7. **Customer Satisfaction:** Monitor customer feedback and identify opportunities to improve product quality and customer experience.

8. **Customer Retention:** Use previous purchase information to identify customer segments for personalized marketing and retention campaigns.

## 10. Limitations

- The dataset contains one record per customer rather than individual historical transaction records.
- Previous Purchases represents the customer's past purchase count, not a complete transaction history.
- The dataset does not contain purchase dates, so monthly or date-based sales trends cannot be analyzed.
- Revenue figures represent purchase amounts and do not account for product costs, discounts as expenses, or profit margins.

## 11. Conclusion

This project demonstrates how Microsoft Excel can be used to clean, preprocess, analyze and visualize customer purchase behavior.

Through PivotTables, PivotCharts and interactive slicers, the analysis identifies important revenue patterns, customer segments, seasonal trends, shipping preferences and payment methods.

The dashboard provides a clear overview of retail customer behavior and supports data-driven business decision-making.

## 12. Skills Demonstrated

- Microsoft Excel
- Data Cleaning and Preprocessing
- Data Analysis
- PivotTables and PivotCharts
- Dashboard Development
- Data Visualization
- Customer Segmentation
- Business Insights
- Analytical Thinking

---

**Project:** Customer Purchase Behavior Analysis | Retail Fashion

**Tool Used:** Microsoft Excel

**Author:** [C.DIVYA SRI]
