# Retail Revenue Analysis; Diagnosing Growth Stagnation in a Retail Business

## Table of Content 

1. [Project Overview](#project-overview)
2. [Dataset Source and Description](#dataset-source-and-description)
3. [Tools Used](#tools-used)
4. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
5. [Key Metrics Measured](#key-metrics-measured)
6. [Dashboard Overview](#dashboard-overview)
7. [Key Insight and Findings](#key-insight-and-findings) 
8. [Business Implications](#business-implications)
9. [Recommendation](#recommendation)


### Project Overview 

This project analyzes multi-year retail transaction data to understand why a large retail business experienced revenue stagnation despite consistent sales activity. Using Excel (Power Query, Pivot Tables, and dashboarding), the analysis integrates multiple dimension tables (customers, time, items, stores, suppliers) into a unified fact table and evaluates revenue trends across years, months, products, stores, suppliers, countries, and transaction types.
The analysis reveals that while total revenue remained relatively stable over time, the business showed limited growth momentum, driven by a narrow set of high-revenue products and minimal variation in pricing and demand. The dashboard highlights key performance indicators such as total revenue, quantity sold, average unit price, store coverage, customer base, and geographic performance, enabling stakeholders to quickly identify structural growth limitations rather than short-term fluctuations.
This project demonstrates an end-to-end analytical workflow — from data cleaning and modeling to visualization and business insight generation — with a focus on translating data findings into strategic business implications.

### Dataset Source and Description 

Reatail Sales Data: The primary datasets used for this analysis was obtained from Kaggale, the The dataset consists of multiple related tables representing a retail business operating across different locations and countries.
Key data elements include:
- Transaction data (quantity sold, unit price, total price)
- Customer information
- Store information
- Product and supplier details
- Time dimension (year, month, date)
- Country and transaction type
The data spans 2014–2021, with 2021 excluded from year-over-year analysis due to incomplete records (January only).

### Tools Used 

I used Excel for all this process that include;
- Data Cleaning & Preparation Techniques
- Exploratory Data Analysis (EDA)
- Dashboards


### Data Cleaning and Preparation 

The following steps were performed to prepare the data for analysis:
1. Imported six datasets (fact and dimension tables) into Excel
2. Checked for missing values, blanks, and inconsistencies
3. Standardized text fields (e.g., naming and casing inconsistencies)
4. Corrected and structured date fields using year, month, and day components
5. Ensured numeric fields (quantity, unit price, total price) were correctly formatted
6. Enriched the fact table by bringing in customer, product, store, supplier, country, and time attributes using lookups
Validated data consistency before analysis.

These steps ensured the data was reliable and analysis-ready.


### Key Metrics Measured 

The dashboard tracks the following key business metrics:
1. Total Revenue
2. Quantity Sold
3. Average Unit Price
4. Number of Stores
5. Number of Customers
6. Revenue by Year and Month
7. Revenue by Product
8. Revenue by Store
9. Revenue by Supplier
10. Revenue by Country
11. Top Customers by Revenue


### Dashboard Overview

The dashboard provides a high-level view of business performance and answers key questions such as:

1. Is the business growing or stagnating over time?
2. Which products contribute most to revenue?
3. Are sales driven by volume or pricing?
4. How concentrated is revenue across customers and suppliers?
5. Do stores and countries perform evenly or unevenly?

The dashboard is designed for executive readability, prioritizing clarity over technical detail.


### Key Insight and Findings

1. Revenue remained largely flat between 2014 and 2020, fluctuating within a narrow range, indicating stagnation rather than growth
2. Monthly revenue shows mild seasonality, but no strong peaks capable of driving annual growth
3. A small number of products generate a disproportionate share of total revenue
4. Only a few products appear in both top revenue and top quantity sold lists, indicating pricing-driven revenue rather than volume-driven growth
5. Revenue is concentrated among a small number of high-value customers, creating dependency risk
6. Geographic reach exists across multiple countries, but expansion has not translated into revenue growth

### Business Implications 

1. The business is stable but not scaling
2. Growth limitations are structural, not seasonal
3. Revenue dependence on a narrow product set increases risk
4. Pricing and product mix strategies appear static
5. Customer concentration exposes the business to revenue volatility if key customers are lost

Overall, the data suggests a growth strategy gap rather than an operational failure.

### Recommendation 
Based on the analysis, the following actions are recommended:

1. Introduce cost data to enable margin and profitability analysis
2. Review product portfolio to reduce dependency on a small number of SKUs
3. Implement customer segmentation strategies for retention and upselling
4. Explore pricing, bundling, or promotional strategies to stimulate growth
5. Investigate underperforming regions and stores for optimization opportunities


![Screenshot 2025-12-22 at 9 29 19 PM](https://github.com/user-attachments/assets/b6adc2b0-2424-4cfa-b379-699ee85d1c58)

![Screenshot 2025-12-22 at 9 29 27 PM](https://github.com/user-attachments/assets/674cf18c-b6f5-4529-94d5-71e80bbb43ae)
