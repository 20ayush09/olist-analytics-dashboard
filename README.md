Olist E-Commerce Analytics

An end-to-end **Power BI e-commerce analytics project** built using the Brazilian Olist marketplace dataset, focused on transforming raw transactional data into actionable insights across **sales, customers, sellers, products, delivery performance, customer reviews, and cohort behavior**.

📊 Project Overview

This project analyzes Olist's e-commerce operations to understand **revenue performance, customer behavior, product performance, seller activity, delivery efficiency, and customer satisfaction**.

The project goes beyond basic visualization by building a structured **star-schema data model**, developing reusable **DAX measures and calculated columns**, performing data transformation in **Power Query**, and designing interactive dashboards to answer real business questions.

 Key Business Metrics

11K+ Orders
16M+ Revenue
99K+ Customers
3K+ Sellers
Revenue trends across years
Product and category performance
Order-value and customer-spending analysis
Delivery performance and delays
Customer review and satisfaction analysis
Customer retention and cohort behavior

🧩 Data Modeling

A structured analytical model was developed by separating transactional and descriptive data into appropriate **fact and dimension tables.

The model incorporates data from:

* Orders
* Order Items
* Payments
* Customers
* Sellers
* Products
* Reviews
* Date and time dimensions
* Cohort analysis tables

Special attention was given to table grain, relationships, filter propagation, and dimensional modeling to ensure that the dashboard produces reliable results.

 🔄 Power Query

Power Query was used extensively for data cleaning, transformation, and feature engineering, including:

* Data type standardization
* Timestamp transformation
* Date/time extraction
* Time-of-day classification
* Weekday/weekend classification
* Product-category cleaning and grouping
* Creation of analytical columns
* Handling inconsistent/missing values
* Preparation of tables for the final data model

The date/time model was also structured to support analysis by **year, month, day, weekday/weekend, and time of day.

🧠 DAX & Analytical Logic

The project uses DAX for both straightforward KPIs and more advanced analytical logic.

Key concepts implemented include:

* CALCULATE
* VAR
* SELECTEDVALUE
* VALUES
* RELATED
* RELATEDTABLE
* Context transition
* Filter context
* Dynamic measures
* Customer segmentation
* Cohort analysis
* First-order identification
* Revenue and order-value calculations
* Delivery-delay classification

A custom delivery-performance framework was developed to distinguish between **early delivery, on-time delivery, and delayed delivery**, while allowing a **one-day flexibility window** for delivery expectations.

👥 Customer Analytics

Customer behavior was analyzed using:

* Customer spending-power segmentation
* Customer lifetime/cohort analysis
* First-order month identification
* Cohort month tracking
* Retention analysis
* Revenue contribution
* Order-value analysis

A dedicated cohort framework was developed to understand how customer groups behave after their first purchase rather than relying only on overall customer counts.

 🚚 Delivery & Operational Analytics

The project also analyzes the operational side of the marketplace, including:

* Expected vs actual delivery dates
* Delivery delays
* Early/on-time/late deliveries
* Supplier/seller-related delivery performance
* Time taken to reach customers
* Delivery trends over time

This allows the dashboard to move beyond **“how much did we sell?”** toward **“how efficiently did we fulfil those sales?”**

⭐ Customer Reviews

Customer reviews were incorporated to analyze the relationship between **customer satisfaction and e-commerce performance**.

The analysis considers review-related metrics alongside sales and operational performance to provide a more complete view of marketplace health.

📈 Dashboard Analysis

The final Power BI solution is organized into **three interactive dashboards**, covering the major dimensions of the business:

1. Sales & Marketplace Performance

* Revenue
* Orders
* Customers
* Sellers
* Revenue trends
* Top-performing products
* Order-value analysis
* Sales by time of day

2. Customer Analytics

* Customer spending segments
* Cohort analysis
* Customer behavior
* Retention patterns
* Customer contribution

3. Operations & Customer Experience

* Delivery performance
* Delivery delays
* Expected vs actual delivery
* Customer reviews
* Satisfaction trends
* Operational performance

🛠️ Tools & Technologies

Power BI | Power Query (M) | DAX | Data Modeling | Star Schema | Data Analytics | Business Intelligence

🎯 Key Objective

The objective of this project was not simply to create a visually appealing dashboard, but to build a complete analytical workflow.

Raw Data → Data Cleaning → Data Modeling → DAX → Business Logic → Interactive Dashboard → Business Insights.

This project demonstrates practical experience in turning complex, multi-table transactional data into a structured **business intelligence solution** capable of supporting data-driven decision making.
