# 🍕 Pizza Restaurant Sales Analysis

## 📊 Project Overview

This project is a **simulated data analysis project** designed to demonstrate practical data analytics skills using spreadsheet-based analysis.

The dataset represents sales transactions from a fictional pizza restaurant. It contains information about individual orders, including order dates and times, order types, menu items, product categories, quantities sold, pricing, discounts, gross sales, and net sales.

**Important:** All data in this project is **completely fictional and artificially generated**. It does not represent a real restaurant, real customers, or real business transactions. The dataset has been created **strictly for educational, practice, and portfolio purposes**.

The analysis is designed to simulate a real-world business request where a restaurant manager wants to understand sales performance and customer ordering behavior and use those insights to make better business decisions.

---

## 🎯 Business Objective

The primary objective of this analysis is to use sales data to identify meaningful patterns and trends that could help restaurant management:

- Understand overall sales performance
- Identify the restaurant's strongest and weakest products
- Understand when customers are most likely to place orders
- Identify high-performing days and time periods
- Compare different order types
- Evaluate product category performance
- Understand the impact of discounts on sales
- Identify opportunities to increase revenue
- Support better menu, promotional, and operational decisions

The project follows a **business-first approach**, where the analysis focuses not only on calculating metrics but also on translating those metrics into actionable business insights.

---

## 🗂️ Dataset

The dataset contains **4,947 sales transaction records** and includes the following fields:

| Column | Description |
|---|---|
| `Order_ID` | Unique identifier for each order |
| `Order_Date` | Date the order was placed |
| `Day_of_Week` | Day of the week the order was placed |
| `Order_Time` | Time the order was placed |
| `Time_Period` | Time period associated with the order |
| `Order_Type` | Type of order, such as dine-in, takeaway, or delivery |
| `Menu_Item` | Pizza or other menu item purchased |
| `Category` | Category of the menu item |
| `Quantity` | Number of units purchased |
| `Unit_Price` | Price per unit |
| `Gross_Sales` | Sales amount before discounts |
| `Discount` | Discount applied to the transaction |
| `Net_Sales` | Sales amount after discounts |

---

## ❓ Business Questions

The analysis will attempt to answer the following business questions.

### 1. Overall Sales Performance

- What are the restaurant's total gross sales and net sales?
- How many orders were placed during the analysis period?
- How many total items were sold?
- What is the average order value?
- How does sales performance change over time?
- Are there noticeable sales trends or fluctuations?

### 2. Product Performance

- Which menu items generate the most revenue?
- Which menu items sell the highest quantities?
- Which products are the strongest and weakest performers?
- Are some products popular by quantity but generate relatively low revenue?
- Which product categories contribute the most to overall sales?
- Which products or categories may require further investigation?

### 3. Customer Ordering Behavior

- What are the most common order types?
- How does sales performance differ between order types?
- Which order type generates the most revenue?
- Which order type has the highest average order value?
- Are customers purchasing different quantities depending on their order type?

### 4. Time-Based Sales Analysis

- Which days of the week generate the most sales?
- Which days have the highest number of orders?
- What time periods are busiest?
- When does the restaurant experience its highest sales activity?
- Are there identifiable peak periods that management should prepare for?
- Are there slower periods that could potentially benefit from promotions?

### 5. Discount Analysis

- How frequently are discounts being applied?
- How much revenue is being reduced through discounts?
- Which products or categories receive the most discounts?
- Are discounted orders associated with higher quantities or order values?
- What is the relationship between gross sales and net sales?

### 6. Revenue Opportunities

Based on the analysis:

- Which products should management consider promoting?
- Which products may need further evaluation?
- Are there opportunities to increase average order value?
- Could specific time periods benefit from targeted promotions?
- Could certain order types be encouraged to increase revenue?
- Are there opportunities to use product combinations or upselling strategies?
- What areas of the business appear to have the greatest potential for improvement?

---

## 📈 Key Metrics

The analysis will focus on several important sales KPIs, including:

- **Total Orders**
- **Total Items Sold**
- **Gross Sales**
- **Total Discounts**
- **Net Sales**
- **Average Order Value (AOV)**
- **Average Items per Order**
- **Sales by Day**
- **Sales by Time Period**
- **Sales by Order Type**
- **Sales by Category**
- **Sales by Menu Item**
- **Top-Selling Products**
- **Lowest-Selling Products**
- **Discount Rate**

These metrics will be used to move from basic descriptive statistics toward meaningful business insights.

---

## 🔎 Analysis Approach

The project will follow a structured data analysis process:

### 1. Data Understanding

Review the dataset structure, fields, data types, and business context.

### 2. Data Cleaning & Preparation

Check the data for:

- Missing values
- Duplicate records
- Inconsistent values
- Incorrect data types
- Calculation inconsistencies
- Outliers or unusual transactions

Where necessary, the data will be cleaned and transformed to make it suitable for analysis.

### 3. Exploratory Data Analysis

Analyze the data using spreadsheet techniques such as:

- Pivot tables
- Sorting and filtering
- Conditional calculations
- Aggregations
- Percentage calculations
- KPI calculations
- Charts and visualizations

### 4. Business Analysis

The results will be interpreted from a restaurant management perspective rather than simply presenting numbers.

The goal is to identify **what happened, why it may have happened, and what the business could potentially do about it.**

### 5. Recommendations

The final analysis will translate the findings into practical recommendations that could help management improve sales, product performance, promotions, and operational planning.

---

## 📊 Planned Analysis Areas

The project will examine sales from multiple perspectives:

**Sales Performance**
> Overall revenue, orders, average order value, and sales trends.

**Product Performance**
> Menu-item and category-level sales and quantity performance.

**Customer Behavior**
> Ordering patterns and differences between order types.

**Time Analysis**
> Daily, weekly, and time-period sales patterns.

**Discount Analysis**
> Discount usage and its relationship with gross and net sales.

**Business Opportunities**
> Potential areas for revenue growth and operational improvement.

---

## 💡 Expected Business Insights

The purpose of this project is not simply to produce charts or calculate totals.

The final analysis should help answer questions such as:

> **What is driving the restaurant's sales?**

> **Which products are customers buying most often?**

> **When is the restaurant busiest?**

> **Which order channels perform best?**

> **Where are potential opportunities to increase revenue?**

> **What recommendations can management make based on the data?**

The ultimate goal is to demonstrate how a data analyst can take **raw transactional data → analyze it → identify patterns → communicate insights → support business decisions.**

---

## 🛠️ Tools & Skills Demonstrated

This project is designed to demonstrate practical skills relevant to an entry-level data analyst role, including:

- Microsoft Excel / Spreadsheet Analysis
- Data Cleaning
- Data Validation
- Data Transformation
- Pivot Tables
- KPI Development
- Exploratory Data Analysis
- Aggregation & Calculations
- Data Visualization
- Trend Analysis
- Business Question Development
- Insight Generation
- Business Recommendations
- Data Storytelling

Future stages of the project may also involve using **SQL** to reproduce and extend the analysis.

---

## 📁 Project Structure

```text
pizza-restaurant-sales-analysis/
│
├── data/
│   └── fictional_pizza_restaurant_sales_raw.xlsx
│
├── analysis/
│   └── spreadsheet_analysis.xlsx
│
├── visualizations/
│   └── charts_and_dashboard.xlsx
│
├── README.md
│
└── ...
```

*The exact folder structure may evolve as the project develops.*

---

## ⚠️ Data Disclaimer

This project uses **100% fictional, artificially generated data**.

The restaurant, transactions, menu items, customers, sales figures, and other information contained within the dataset are **not based on an actual business or real-world customer data**.

This dataset was created solely to provide a realistic environment for practicing:

- Data analysis
- Spreadsheet skills
- SQL analysis
- Data visualization
- Business intelligence
- Portfolio development

No real customer or confidential business information is included.

---

## 🎓 Educational & Portfolio Purpose

This project was created as a **portfolio project to demonstrate data analysis capabilities to potential employers and recruiters**.

While the dataset is fictional, the analysis process is designed to replicate a realistic business scenario in which a data analyst receives transactional data and is expected to generate insights that can support management decision-making.

The emphasis of the project is therefore on demonstrating the **analytical process, technical skills, business reasoning, and communication of insights**, rather than representing actual restaurant performance.

---

## 🚀 Project Goal

The overall goal of this project is to demonstrate the ability to take a raw dataset and turn it into a structured, understandable, and actionable business analysis.

**Raw Data → Data Cleaning → Exploratory Analysis → KPIs → Visualizations → Insights → Recommendations**

This project represents one stage of a broader data analytics workflow, with the eventual goal of demonstrating the ability to perform the same analysis using multiple tools and techniques, including spreadsheets and SQL.
