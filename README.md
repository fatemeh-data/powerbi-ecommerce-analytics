# E-commerce Sales & Customer Analytics
### Interactive Power BI Dashboard | Business Intelligence & Decision Support

## Executive Summary

This project presents an interactive Power BI dashboard designed to analyze e-commerce sales performance, customer behavior, product demand, regional performance, and shipping cost optimization opportunities.

The dashboard brings together four analytical perspectives: Executive Overview, Customer Analytics, Product & Sales Analytics, and What-if Analysis. It enables users to move from high-level performance monitoring to detailed customer, product, geographic, and operational analysis.

The analysis combines KPI reporting, comparative visualizations, time-series trends, customer-level analysis, and scenario modeling to support data-informed commercial decisions.

## Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Sales | $1.55M |
| Customers | 3,141 |
| Total Invoices | 24,404 |
| Avg Revenue per Customer | $391 |
| Number of Products | 20 |
| Total Shipping Cost | $178,317 |
| Number of Unique Invoices | 11,427 |
| Average Order Value | $136 |

All monetary values are expressed in USD. KPI values reflect the current dashboard view and selected filters.

## Business Questions

- Which product categories contribute most to total sales?
- How does sales performance differ across regions and states?
- How are customers distributed geographically?
- Which customers and products contribute most to sales?
- How does average revenue per customer vary by region?
- How do sales change over time?
- How could a user-defined shipping scenario affect estimated shipping costs?
- Which products may warrant further investigation for shipping cost optimization?

## Dashboard Pages

### 1. Executive Overview

Provides a high-level view of business performance through sales, customer, invoice, and average revenue per customer KPIs.

Key analyses:
- Sales by product category
- Sales by state
- Monthly sales trends
- Sales by region

Business value:
Helps stakeholders monitor overall performance, identify leading categories and regions, and recognize periods that may require further investigation.

### 2. Customer Analytics

Focuses on customer distribution, customer value, and major revenue contributors.

Key analyses:
- Number of customers by region
- Average revenue per customer by region
- Top 10 states by customer count
- Top 10 customers by sales
- Top 10 states by total sales

Business value:
Supports customer and regional comparisons, helps identify high-value customers, and provides a starting point for targeted customer engagement and regional growth analysis.

### 3. Product & Sales Analytics

Examines product and category performance alongside sales, quantity, and shipping-related indicators.

Key analyses:
- Sales by category
- Top 10 products by sales
- Sales by region
- Sales distribution by quantity
- Sales versus quantity by category
- Average quantity by product description
- Shipping cost indicators

Business value:
Helps identify major revenue contributors, compare sales and quantity patterns, and investigate differences in product demand and shipping-related costs.

### 4. What-if Analysis

Introduces scenario-based analysis to compare baseline shipping costs with user-defined scenario results.

| Metric | Value |
|---|---:|
| Baseline Shipping Cost | $385,150 |
| What-if Shipping Cost | $326,055 |
| Modeled Cost Reduction | $59,095 |
| Displayed Shipping Cost Savings | 15% |

The displayed baseline and scenario totals imply a cost reduction of approximately 15.3%.

Business value:
Demonstrates how interactive scenario modeling can quantify potential cost reductions, compare product-level cost impacts, and support operational planning.

These results represent a modeled scenario, not verified real-world savings. The assumptions and parameter logic should be validated before drawing operational conclusions.

## Key Business Insights

### Product Category Concentration

Food and Disposables are the largest categories by sales in the current report view, contributing approximately $0.54M and $0.43M, respectively.

**Potential action:** Monitor demand and product availability in these categories and investigate opportunities in smaller categories.

### Regional Performance

The East region leads total sales at approximately $548K and has the largest customer count, with 1,387 customers.

However, West has the highest average revenue per customer among the East, Central, and West regions, at approximately $405.

**Potential action:** Compare customer counts, purchasing patterns, and product mix to understand the differences between total sales and average customer value.

### Product-Level Performance

The product and sales page highlights top-performing products and differences in sales and quantity across categories.

**Potential action:** Use product-level results to prioritize further analysis of demand, assortment, and operational costs rather than assuming that high sales automatically mean high profitability.

### Shipping Cost Scenario

The What-if page shows a modeled reduction of $59,095 from a baseline of $385,150, equivalent to approximately 15.3%.

**Potential action:** Validate the scenario assumptions and compare projected savings with actual shipping costs before implementing changes.

## Tools & Skills Demonstrated

- Power BI Desktop
- DAX measures and KPI calculations
- Interactive slicers and report navigation
- Sales and customer analytics
- Product and category performance analysis
- Geographic and regional comparisons
- Time-series analysis
- What-if parameter and scenario analysis
- Data visualization and business insight communication

## Analytical Approach

1. Consolidate business KPIs into an executive reporting view.
2. Compare sales and customer performance across categories and regions.
3. Examine customer-level and product-level contributors.
4. Analyze changes in sales over time.
5. Compare baseline and scenario-based shipping costs.
6. Translate observed patterns into recommendations for further investigation.

## Limitations & Considerations

- Findings reflect the current report filters and available dataset.
- Observed relationships do not establish causation.
- Sales and revenue metrics do not, by themselves, measure profitability.
- What-if results depend on the assumptions and calculations defined in the model.
- KPI values may change when report filters are applied.

## Repository Contents

- `README.md` — Project overview, analytical scope, and business insights
- `Ecommerce-Analytics.pbix` — Power BI report file
- `screenshots/` — Dashboard page previews

## How to Explore the Dashboard

Open the Power BI report in Power BI Desktop and use the available slicers to explore results by year, category, region, and other available dimensions.

The What-if Analysis page allows users to explore the impact of the configured shipping scenario.

## Author

Fatemeh Khosravi

Data Analytics | Business Intelligence | Power BI
