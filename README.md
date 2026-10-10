# 🛒 E-commerce Sales & Customer Analytics Dashboard

**End-to-End Business Intelligence Project | Power BI • DAX • Data Analytics**

An interactive Power BI dashboard designed to analyze e-commerce sales performance, customer behavior, product trends, regional performance, and shipping cost optimization scenarios.

---

## 📌 Project Overview

This project presents an interactive business intelligence solution for exploring e-commerce sales, customer distribution, product performance, geographic trends, and shipping costs.

The dashboard transforms transactional data into business insights through four analytical pages: Executive Overview, Customer Analytics, Product & Sales Analytics, and What-if Analysis.

The objective is to help stakeholders monitor key performance indicators, identify patterns in sales and customer behavior, and evaluate potential operational improvements through scenario-based analysis.

---

## 🎯 Business Context

E-commerce businesses need clear visibility into sales performance, customer value, product demand, and operational costs.

Key business questions include:

- Which product categories contribute most to total sales?
- How does sales performance vary across regions and states?
- Which customers and products are the largest contributors to sales?
- How does average revenue per customer differ by region?
- How do sales change over time?
- How could a shipping cost scenario affect estimated costs?

This project provides an interactive reporting framework to explore these questions and support data-informed commercial decisions.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** → Interactive dashboards and business reporting
- **DAX** → KPI calculations and analytical measures
- **Data Modeling** → Organizing data for cross-dimensional analysis
- **Power BI Slicers** → Interactive filtering by available dimensions
- **What-if Parameters** → Scenario-based shipping cost analysis

---

## 🔄 Analytical Workflow

### 1. KPI Reporting
- Consolidated core sales and customer indicators
- Presented executive-level performance metrics
- Enabled interactive exploration through report filters

### 2. Customer & Regional Analysis
- Compared customer counts across regions and states
- Analyzed average revenue per customer
- Identified top customers and geographic contributors

### 3. Product & Sales Analysis
- Compared sales across product categories
- Examined top-performing products
- Analyzed sales and quantity patterns
- Reviewed shipping cost indicators

### 4. Scenario Analysis
- Compared baseline shipping costs with scenario-adjusted costs
- Evaluated modeled cost differences
- Examined potential cost impacts by product and over time

---

## 📊 Dashboard & Analysis

### 🔹 1. Executive Summary

Provides a consolidated view of overall sales performance, customer metrics, invoice indicators, and regional and product category trends.

**Key KPIs:**
- Total Sales: $1.55M
- Customers: 3,141
- Total Invoices: 24,404
- Avg Revenue per Customer: $391
- Number of Products: 20

**Analysis Highlights:**
- Sales by product category
- Sales by state and region
- Monthly sales trends
- High-level performance monitoring

**Business Value:**
- Provides a quick overview of business performance
- Highlights leading categories and regions
- Supports further investigation of sales trends

---

### 🔹 2. Customer Analytics

Focuses on customer distribution, customer value, and major sales contributors.

**Key KPIs:**
- Customers: 3,141
- Avg Revenue per Customer: $391
- Number of Unique Invoices: 11,427

**Analysis Highlights:**
- Customer distribution by region
- Average revenue per customer by region
- Top 10 states by customer count
- Top 10 customers by sales
- Top 10 states by total sales

**Key Insights:**
- The East region has the highest customer count, with 1,387 customers.
- The East region generates approximately $548K in sales.
- West has the highest average revenue per customer among the East, Central, and West regions, at approximately $405.

**Business Value:**
- Supports customer and regional performance comparisons
- Helps identify major sales contributors
- Provides a basis for targeted customer engagement and regional growth analysis

---

### 🔹 3. Product & Sales Analytics

Examines product category performance, sales quantity patterns, and shipping-related indicators.

**Key KPIs:**
- Total Sales: $1.55M
- Total Shipping Cost: $178,317
- Number of Products: 20

**Analysis Highlights:**
- Sales by category
- Top 10 products by sales
- Sales distribution by quantity
- Sales versus quantity by category
- Average quantity by product description
- Regional sales and shipping cost indicators

**Key Insights:**
- Food generates approximately $0.54M in sales.
- Disposables generates approximately $0.43M in sales.
- These categories are major contributors to total sales in the current dashboard view.

**Business Value:**
- Helps identify leading product categories
- Supports comparisons between sales and quantity
- Highlights products and categories for further demand and cost analysis

---

### 🔹 4. What-if Analysis

Uses scenario modeling to compare baseline shipping costs with the results of a configured shipping scenario.

**Key Metrics:**

| Metric | Value |
|---|---:|
| Baseline Shipping Cost | $385,150 |
| What-if Shipping Cost | $326,055 |
| Modeled Cost Reduction | $59,095 |
| Displayed Shipping Cost Savings | 15% |

The displayed baseline and scenario values imply a modeled reduction of approximately 15.3%.

**Analysis Highlights:**
- Baseline versus scenario shipping costs
- Product-level shipping cost comparisons
- Monthly cumulative shipping cost trends
- Estimated cost differences under the selected scenario

**Business Value:**
- Demonstrates the use of What-if parameters in business analysis
- Helps quantify potential cost reductions
- Supports evaluation of operational scenarios before implementation

**Important Consideration:**
These results represent a modeled scenario, not verified real-world savings. The outcome depends on the parameter settings and assumptions defined in the report.

---

## 📈 Key Business Insights

### Product Category Performance
Food and Disposables are the largest categories by sales in the current report view, contributing approximately $0.54M and $0.43M, respectively.

**Potential action:** Monitor demand and availability in major categories while investigating opportunities in smaller categories.

### Regional Sales and Customer Value
The East region leads total sales at approximately $548K and has the largest customer count. However, West has the highest average revenue per customer among the East, Central, and West regions.

**Potential action:** Compare customer counts, product mix, and purchasing patterns to understand regional differences.

### Shipping Cost Optimization
The configured What-if scenario reduces modeled shipping costs by $59,095, approximately 15.3% of the baseline amount.

**Potential action:** Validate the scenario assumptions and compare projected savings with actual shipping costs before making operational changes.

---

## 🧩 Key Analytical Capabilities

- Executive KPI reporting
- Customer and regional segmentation
- Product category and sales performance analysis
- Geographic comparisons
- Time-series trend analysis
- Baseline versus scenario comparison
- What-if parameter analysis
- Business insight communication

---

## 💼 Business Value

This project demonstrates the ability to:

- Translate transactional data into business-focused reporting
- Build interactive dashboards for multiple analytical perspectives
- Compare customer, product, and regional performance
- Use DAX measures to calculate and present KPIs
- Apply scenario analysis to operational cost questions
- Turn observed patterns into actionable recommendations for further investigation

---

## 📁 Project Structure

```text
powerbi-ecommerce-analytics/
├── README.md
├── Ecommerce-Analytics.pbix
└── screenshots/
    ├──Executive Summary.png
    ├── customer-analytics.png
    ├── product-sales-analytics.png
    └── what-if-analysis.png
```

*Update the PBIX filename and screenshot paths if your actual repository uses different names.*

---

## 📊 Dashboard Preview

### 🔹 Executive Summary
High-level KPIs and sales performance monitoring.

![Executive Summary](images/Executive%20Summary.PNG)

---

### 🔹 Customer Analytics
Customer distribution, regional value, and top customer analysis.

![Customer Analytics](images/Customer%20Analytics.PNG)

---

### 🔹 Product & Sales Analytics
Product category performance, sales quantity patterns, and shipping indicators.

![Product & Sales Analytics](images/Product%20%26%20Sales%20Analytics.PNG)

---

### 🔹 What-if Analysis
Scenario-based shipping cost comparison and modeled savings.

![What-if Analysis](images/What-if%20Analysis.PNG)

---

## ⚠️ Notes & Limitations

- KPI values reflect the current dashboard view and may change when filters are applied.
- Sales and revenue do not, by themselves, measure profitability.
- Observed patterns do not establish causation.
- What-if results depend on the configured scenario assumptions.
- All monetary values are expressed in USD.

---
## 📊 Data Source

The dataset used in this project was provided by **DataCamp** as part of a practical data analytics learning project.

The dataset was used to explore sales performance, customer behavior, product categories, regional trends, and shipping cost scenarios.

## 🧹 Data Preparation

Before building the dashboard, the data was prepared for analysis in Power BI. The workflow focused on organizing the data, creating relevant measures with DAX, and preparing the metrics and dimensions needed for interactive reporting.
## 👩‍💻 Author

**Fatemeh Khosravi**

Data Analytics | Business Intelligence | Power BI
