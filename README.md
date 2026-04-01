## ByteBloom Customer Transaction Analysis

### Project Overview

This project performs an end-to-end analysis of customer transaction data for ByteBloom, a fictional mid-sized e-commerce company specializing in consumer electronics, smart home devices, and tech accessories.

The objective of this project is to analyze transaction data to uncover patterns in customer behavior, identify churn risks, evaluate product performance, and generate actionable insights that can help the company improve customer retention and drive business growth.

The dataset consists of 30 columns containing transactional and customer-related information, which were processed using Python-based data analysis tools.

### Company Background

ByteBloom is a growing e-commerce retailer that focuses on selling innovative gadgets, smart home devices, and tech accessories targeted primarily at millennials and Gen Z consumers.

Founded five years ago, ByteBloom initially experienced strong revenue growth due to its curated product offerings and strong digital presence through its website and mobile app.

However, the company is now facing increasing competition from large marketplaces and direct-to-consumer technology brands.

### Business Problem

Over the past two quarters, ByteBloom’s revenue growth has stagnated, raising concerns among the executive leadership team.

Although customer acquisition remains stable, early reports indicate that customer retention is declining, and marketing campaigns are becoming less effective.

Additionally:

Customer acquisition costs are increasing.
Marketing campaigns are producing diminishing returns.
Customer behavior patterns are not well understood.

Management believes that deeper insights from transaction data could help them understand evolving customer behavior and design more targeted marketing strategies.

As a data analyst, the task is to analyze ByteBloom’s raw transaction dataset and extract insights that can guide strategic decisions.

### Project Objectives

The analysis was conducted to address the following business objectives:

**Identify Valuable Customer Segments**

Determine which customers contribute the most to revenue based on purchase frequency and spending patterns.

**Analyze Purchasing Patterns**

Identify popular products, purchasing trends, and sales patterns over time to help improve inventory planning and marketing strategies.

**Evaluate Sales Channels & Payment Methods**

Analyze how purchasing behavior differs across devices (Desktop vs Mobile) and payment methods.

**Identify Churn Risk**

Detect customers who may have stopped engaging with the platform and identify behavioral patterns associated with churn.

### Tools & Technologies

**Programming Language**

Python

**Libraries Used:**

NumPy
Pandas
Matplotlib
Seaborn
Data Analysis Process

The project follows a structured Data Analysis Lifecycle.

**1. Data Cleaning**

Initial preprocessing was performed to prepare the dataset for analysis.

Steps included:

Handling missing values
Correcting incorrect data types
Removing duplicate records
Standardizing categorical values
Formatting date and time columns

**2. Feature Engineering**

Additional features were created from existing columns to improve analytical insights.

Examples include:

Customer tenure groups
Days since last login
Transaction value metrics
Customer activity indicators

These engineered features helped enable deeper behavioral analysis.

**3. Exploratory Data Analysis (EDA)**

Exploratory analysis was conducted using statistical summaries and visualizations to uncover patterns in the data.

Areas analyzed include:

Customer spending behavior
Product category performance
Refund rates
Store performance
Discount effectiveness
Customer tenure behavior

Visualizations were created using Matplotlib and Seaborn.

**4. Advanced Analysis**

Advanced analysis techniques were used to evaluate customer behavior and business performance, including:

Churn risk identification
Customer tenure segmentation
Discount impact analysis
Refund rate analysis
Revenue distribution analysis

### Key Insights

**Customer Churn Risk**

Approximately 93 unique customers were identified as being at risk of churning.

These customers had an average of 210.70 days since their last login, significantly exceeding the churn threshold of 72.25 days, which was calculated using the 75th percentile of the days_since_last_login metric.

**High Refund Categories**

Certain product categories exhibit higher refund rates:

Home Goods: 27.27%
Electronics: 26.83%
Beauty: 26.63%

These high return rates may indicate issues with product quality, customer expectations, or product descriptions.

**Customer Age vs Product Category**

The analysis found no strong relationship between customer age and the product categories purchased.

Customer age distributions were relatively similar across product categories.

**Top Revenue Store**

STORE-002 generated the highest revenue, totaling $95,288.12, making it the top-performing store location in the dataset.

**Discount Impact on Sales Quantity**

The correlation between discount percentage and quantity purchased is extremely weak.

Pearson Correlation Coefficient: 0.03

This suggests that discounts do not significantly increase purchase volume, indicating that promotions may not be the primary driver of customer purchases.

**Customer Tenure & Spending Patterns**

Customer tenure analysis revealed interesting spending behavior:

Most transactions come from newer customers with lower tenure.
Mid-tenure customers show the highest average transaction value:
Developing customers: ~$1429.77
Established customers: ~$1419.49
Loyal customers (longest tenure) have the lowest average transaction value at $1140.72.
Business Recommendations

Based on the insights generated from the analysis, the following recommendations can help ByteBloom improve performance.

**Investigate High Refund Categories**

ByteBloom should examine the causes of high refund rates in Home Goods, Electronics, and Beauty categories to reduce operational costs and improve customer satisfaction.

**Re-engage Loyal Customers**

The lower spending levels among long-term customers suggest an opportunity to introduce personalized promotions or loyalty incentives.

**Optimize Marketing Strategies**

Since discounts show little effect on purchase volume, ByteBloom should focus on targeted promotions and personalized recommendations rather than broad discount campaigns.

**Focus on Mid-Tenure Customers**

Customers in the Developing and Established tenure groups represent the highest spending segment and should be targeted with retention and upselling strategies.

**Author**

Aman Paliwal

Data Analyst | Data Science Enthusiast

