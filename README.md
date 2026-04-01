# ByteBloom Customer Transaction Analysis

## Project Overview

This project performs an **end-to-end analysis of customer transaction data** for **ByteBloom**, a fictional mid-sized e-commerce company specializing in consumer electronics, smart home devices, and tech accessories.

The objective of this project is to analyze transaction data to:

- Uncover patterns in customer behavior  
- Identify churn risks  
- Evaluate product performance  
- Generate actionable insights  

These insights can help the company **improve customer retention and drive business growth**.

The dataset consists of **30 columns containing transactional and customer-related information**, analyzed using Python-based data analysis tools.

---

# Company Background

**ByteBloom** is a growing e-commerce retailer that focuses on selling:

- Innovative gadgets  
- Smart home devices  
- Tech accessories  

The company primarily targets **millennials and Gen Z consumers**.

Founded five years ago, ByteBloom initially experienced strong revenue growth due to:

- Curated product offerings  
- Strong digital presence through its **website and mobile app**

However, the company is now facing **increasing competition** from:

- Large online marketplaces  
- Direct-to-consumer technology brands

---

# Business Problem

Over the past two quarters, **ByteBloom’s revenue growth has stagnated**, raising concerns among the executive leadership team.

Although **customer acquisition remains stable**, early reports indicate:

- Customer retention is declining  
- Marketing campaigns are becoming less effective  

Additional challenges include:

- Increasing **customer acquisition costs**
- **Diminishing returns** from marketing campaigns
- **Limited understanding of customer behavior patterns**

Management believes that deeper insights from transaction data can help **understand evolving customer behavior and design better marketing strategies**.

As a **Data Analyst**, the task is to analyze ByteBloom’s transaction dataset and extract insights that can guide **strategic business decisions**.

---

# Project Objectives

The analysis was conducted to address the following business objectives.

## Identify Valuable Customer Segments

Determine which customers contribute the most to revenue based on:

- Purchase frequency  
- Spending patterns

## Analyze Purchasing Patterns

Identify:

- Popular products  
- Purchasing trends  
- Sales patterns over time  

This helps improve **inventory planning and marketing strategies**.

## Evaluate Sales Channels & Payment Methods

Analyze purchasing behavior across:

- Devices (**Desktop vs Mobile**)  
- Payment methods  

## Identify Churn Risk

Detect customers who may have **stopped engaging with the platform** and identify behavioral patterns associated with churn.

---

# Tools & Technologies

## Programming Language

- **Python**

## Libraries Used

- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

# Data Analysis Process

The project follows a **structured Data Analysis Lifecycle**.

---

## 1. Data Cleaning

Initial preprocessing was performed to prepare the dataset for analysis.

Key steps included:

- Handling missing values  
- Correcting incorrect data types  
- Removing duplicate records  
- Standardizing categorical values  
- Formatting date and time columns  

---

## 2. Feature Engineering

Additional features were created from existing columns to improve analytical insights.

Examples include:

- Customer tenure groups  
- Days since last login  
- Transaction value metrics  
- Customer activity indicators  

These engineered features enabled **deeper behavioral analysis**.

---

## 3. Exploratory Data Analysis (EDA)

Exploratory analysis was conducted using **statistical summaries and visualizations** to uncover patterns in the data.

Key areas analyzed include:

- Customer spending behavior  
- Product category performance  
- Refund rates  
- Store performance  
- Discount effectiveness  
- Customer tenure behavior  

Visualizations were created using **Matplotlib and Seaborn**.

---

## 4. Advanced Analysis

Advanced analytical techniques were applied to evaluate customer behavior and business performance, including:

- Churn risk identification  
- Customer tenure segmentation  
- Discount impact analysis  
- Refund rate analysis  
- Revenue distribution analysis  

---

# Key Insights

## Customer Churn Risk

- **93 unique customers** were identified as being at risk of churning.
- These customers had an **average of 210.70 days since their last login**.

The churn threshold was calculated using the **75th percentile** of the `days_since_last_login` metric:

- **Churn Threshold:** 72.25 days

---

## High Refund Categories

Certain product categories show **higher refund rates**:

| Category | Refund Rate |
|--------|--------|
| Home Goods | 27.27% |
| Electronics | 26.83% |
| Beauty | 26.63% |

These high return rates may indicate:

- Product quality issues  
- Mismatch between product expectations and reality  
- Inaccurate product descriptions  

---

## Customer Age vs Product Category

The analysis found **no strong relationship between customer age and product categories purchased**.

Customer age distributions were **relatively similar across product categories**.

---

## Top Revenue Store

**STORE-002** generated the highest revenue in the dataset.

**Total Revenue:** `$95,288.12`

---

## Discount Impact on Sales Quantity

The correlation between **discount percentage and quantity purchased** is extremely weak.

**Pearson Correlation Coefficient:** `0.03`

This suggests:

- Discounts do **not significantly increase purchase volume**
- Promotions may **not be the primary driver of purchases**

---

## Customer Tenure & Spending Patterns

Customer tenure analysis revealed interesting spending behavior:

| Customer Segment | Average Transaction Value |
|-----------------|--------------------------|
| Developing Customers | $1429.77 |
| Established Customers | $1419.49 |
| Loyal Customers | $1140.72 |

Key Insights:

- **Mid-tenure customers spend the most**
- **Long-term loyal customers show lower average spending**

---

# Business Recommendations

Based on the insights generated, the following recommendations can help ByteBloom improve performance.

## Investigate High Refund Categories

ByteBloom should investigate the causes of high refund rates in:

- Home Goods  
- Electronics  
- Beauty  

This can help reduce **operational costs** and improve **customer satisfaction**.

---

## Re-engage Loyal Customers

Lower spending among long-term customers indicates an opportunity to introduce:

- Personalized promotions  
- Loyalty rewards  
- Exclusive offers

---

## Optimize Marketing Strategies

Since discounts show **minimal impact on purchase volume**, the company should focus on:

- Targeted promotions  
- Personalized product recommendations  
- Customer segmentation strategies  

---

## Focus on Mid-Tenure Customers

Customers in the **Developing and Established tenure groups** represent the **highest spending segment**.

Strategies should focus on:

- Retention campaigns  
- Upselling opportunities  
- Personalized engagement  

---

# Author

**Aman Paliwal**

Data Analyst | Data Science Enthusiast
