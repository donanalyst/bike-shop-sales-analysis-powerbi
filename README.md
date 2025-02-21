# Adventure Works Bike Shop Sales Report

**Discovering Product Trends, Tracking KPIs, and Analyzing Sales Performance**

# Introduction & Background

This analysis provides a comprehensive sales performance report for executives and stakeholders to support data-driven decision-making. It also explores hypothetical price adjustments to achieve monthly order and profit targets for Adventure Works Bike Shop.

Additionally, this project demonstrates my expertise in **data transformation (Power Query), data modeling (DAX), and data visualization** to help end-users gain valuable insights from the report.

# Business Objectives

This dashboard aims to answer the following key stakeholder questions:

- How does the current month's revenue compare to the previous month?  
- What is the overall revenue and profit trend? Is the business growing or declining
- What is the overall return rate, and is it improving or worsening?
- What is the breakdown of orders and revenue by product category (accessories, bikes, clothing)?
- Which category has the highest return rate?
- What are the top 10 selling products by orders, revenue, and return rate?  
- Which product type is ordered most often? Which is returned most often?  
- For a selected product (e.g., Water Bottle - 30 oz.), how have orders, revenue, and profit trended over time?
- How many unique customers does Adventure Works have?  
- What is the average revenue per customer?  
- How is revenue distributed across different customer income levels and occupations?  
- Who are the top 100 customers by revenue?  
- Who is the top customer by revenue, and what is their purchase history?

# Data Source & Methodology

**Data Source:**
The datasets were sourced from Microsoft’s official Power BI learning resources. Originally in BAK file format, the data was imported into a **Microsoft SQL Server** for database management. SQL queries were then used to extract relevant data, which was exported as CSV files for analysis in Power BI.

**Data Cleaning & Transformation:**
- Imported all datasets into Power BI; sales data was first separated by year, then compiled into a single folder before import.
- Used Power Query to transform and **append** the three separate CSV files containing the same structure.
- Identified and corrected **blank values, typographical errors, and data type inconsistencies** across datasets.
- Created a **rolling calendar** table with additional columns for advanced time intelligence analysis.
- Added a **discount price column** by calculating **90% of the product price** for promotional analysis.
- Used **data profiling tools** to detect and fix anomalies.
- Standardized data types for **consistency and readability.**

  
**Data Model:**
The dataset follows a **snowflake schema,** which introduces some complexity in data relationships. Careful structuring and observation were applied to **eliminate data ambiguity** and prevent potential calculation errors.

**Analysis Approach:**
- Created a **date dimension table** using **DAX** for advanced time intelligence calculations.
- Developed **hypothetical price adjustment measures** for scenario analysis.
- Created **product and customer selection measures** to enable interactivity in the dashboard.
- **Hidden unnecessary columns** (e.g., customer_key, product_key) to streamline the data model and improve usability.


# Dashboard Features & Key Performance Indicators (KPIs)

**Executive Dashboard:**
- Total Revenue
- Total Profit
- Total Orders
- Return Rate
- Monthly Revenue
- Monthly Orders
- Monthly Returns
  
**Product Details:**
- Monthly Orders vs. Targets
- Monthly Revenue vs. Targets
- Monthly Profit vs. Targets
  
**Customer Details:**
- Top Customer
- Unique Customers
- Average Revenue per Customer
  
**Visualizations**

- **Clustered Bar Chart** – Compares total orders across product categories.
- **Matrix Table – Displays** the **top 10 products** by **orders**, **revenue, and return rate.**
- **Card Visuals** – Show **key metrics** such as **total revenue and total profit.**
- **KPI Card** – Highlights monthly KPIs like **revenue trends and profit goals.**
- **Line Graph** – Visualizes **revenue trends over time.**
- **Map Visualization** – Shows revenue and profit **distribution by country and region.**
- **Pie Chart** – Illustrates the **proportion of total orders by income level.**


# Conclusion & Recommendations

**Summary:**
- The **total revenue** of Adventure Works Bike Shop is **$24.9M,** demonstrating strong sales across multiple regions.
- **Total profit** stands at **$10.5M,** with **25.2K total orders** and a **low return rate of 2.17%.**
- **Current month orders (2,146) and revenue ($1.83M)** are lower than the previous month’s figures, indicating a potential slowdown.
- Accessories had the **highest sales volume (17K orders, $906K revenue),** while **Bikes** generated the most **revenue ($23.6M) and 13.9K orders.**
  
- The **USA ($7.9M revenue, $3.36M profit)** and **Australia ($7.4M revenue, $3.08M profit)** are the top-performing markets.
  
- **Top Customer: Maurice Shan – $12,408 in total revenue** with **six total orders.**
- **17.4K unique customers** contributed an **average revenue of $1.4K per customer,** showing a strong customer base.
  
**Recommendations:**

**1. Expand High-Performing Product Categories for Increased Revenue**
- **Bikes** generate the most revenue ($23.6M); consider expanding high-demand models, offering premium versions, and adding customization options.
- **Accessories** have the highest order volume (17K). Implement **bundled deals, upselling strategies, and tiered loyalty discounts** to increase order value.
- Conduct **market segmentation analysis** to identify demand trends and tailor product offerings accordingly.
  
**2. Optimize Return Rate to Maximize Profitability**
- While the **2.17% return rate** is low, further reductions could improve margins.
- Conduct an **in-depth return analysis** to determine the main reasons for returns (e.g., defective products, sizing issues).
- Improve **product descriptions, high-quality images, and size charts** to reduce incorrect purchases.
- Introduce **AI-driven recommendations** to help customers choose the right products before purchasing.
  
**3. Boost Monthly Sales Performance and Address Seasonal Trends**
- **Current month sales ($1.83M) and orders (2,146)** are lower than in previous months.
- Implement **seasonal discounts, promotional campaigns, and referral programs** to drive order volume.
- Use **targeted email marketing and remarketing ads** to re-engage past customers.
- Leverage **historical sales trends** to predict low-performing months and proactively launch marketing initiatives.


# Dashboard
![image](https://github.com/user-attachments/assets/f8703790-135e-466f-9890-fd2139ae0ad9)

![image](https://github.com/user-attachments/assets/9c8d9446-534d-44eb-82ce-ccf0661cb0c9)

![image](https://github.com/user-attachments/assets/e66c3030-795a-4b6d-808b-b700343ebcf6)

![image](https://github.com/user-attachments/assets/4ead8467-f383-4c39-b177-3b4c9f356aa9)





