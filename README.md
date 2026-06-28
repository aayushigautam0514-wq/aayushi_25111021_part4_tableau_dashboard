# Part 4: Executive Tableau Dashboard

## Business Problem Summary

The objective of this project is to build an executive Tableau dashboard that enables leadership to monitor sales performance, profitability, customer behavior, category performance, shipping efficiency, discount impact, and return patterns. The dashboard is designed to support business decision-making by presenting key performance indicators and interactive visualizations.

---

## Dataset Description

The dataset contains retail order-level information including customer details, geographic information, product categories, shipping details, sales, profit, discounts, customer ratings, and return information.

### Date Fields

* Order Date
* Ship Date

### Geographic Fields

* Region
* State
* City

### Categorical Fields

* Customer Segment
* Category
* Sub Category
* Product Name
* Ship Mode
* Campaign Channel

### Numerical Measures

* Sales
* Quantity
* Discount
* Profit
* Delivery Days
* Customer Rating

### Binary / Flag Field

* Return Flag

### Identifier Fields

* Order ID
* Customer ID

## Assumptions

* Order Date and Ship Date are recognized as Date fields in Tableau.
* Return Flag contains binary values indicating returned and non-returned orders.
* Sales and Profit are stored as numerical measures.
* Geographic fields are correctly recognized for mapping and regional analysis.

# Retail Executive Performance Dashboard

## Business Problem Summary

This project develops an interactive Tableau Executive Dashboard for a retail leadership team to monitor business performance and support data-driven decision-making. The dashboard helps analyze sales, profitability, customer segments, regional performance, shipping efficiency, discount impact, and product returns.

---

## Dataset Description

The dataset contains retail transaction information, including:

- Order Date
- Sales
- Profit
- Category
- Sub-Category
- Customer Segment
- Region
- State
- Ship Mode
- Delivery Days
- Discount
- Return Flag
- Customer Rating

The dashboard uses these fields to generate business insights and performance metrics.

---

## Tableau Workbook Description

The Tableau workbook contains an executive dashboard supported by multiple worksheets that provide different business perspectives, including sales trends, regional performance, profitability, shipping performance, customer segmentation, discount analysis, and return analysis.

---

## Calculated Fields Created

The following calculated fields were created in Tableau:

### Profit Margin
Formula:
Profit / Sales

Purpose:
Measures the percentage of sales retained as profit.

---

### Cost
Formula:
Sales - Profit

Purpose:
Calculates the estimated cost associated with each sale.

---

### Average Order Value

Formula:
Total Sales / Number of Orders

Purpose:
Measures the average revenue generated per customer order.

---

### Return Rate

Formula:
Returned Orders / Total Orders

Purpose:
Calculates the percentage of returned orders.

---

### Shipping Delay Bucket

Categories:
- Fast (0–2 Days)
- Medium (3–5 Days)
- Delayed (6+ Days)

Purpose:
Groups deliveries based on delivery speed for easier analysis.

---

## Dashboard Components

The dashboard includes:

- KPI Cards
  - Total Sales
  - Total Profit
  - Profit Margin

- Sales Trend
- Regional Performance
- Category Profitability
- Customer Segment Performance
- Shipping Performance
- Discount vs Profit Analysis
- Return Analysis

---

## Filters and Interactions Used

Interactive filters included:

- Region
- Category
- Customer Segment

Dashboard filter actions allow users to interact with visualizations and update related charts dynamically.

---

## Key Business Insights

The dashboard helps identify:

- Sales trends over time
- Best-performing regions
- Most profitable categories
- Customer segment performance
- Shipping efficiency
- Relationship between discount and profit
- Return patterns across categories

---

## Dashboard Story Summary

The dashboard provides leadership with a consolidated business performance view by combining KPIs and multiple visualizations into a single executive interface. It supports identifying opportunities, monitoring performance, and improving operational decision-making.

---

## Assumptions and Limitations

- Results depend on the quality and completeness of the source dataset.
- The dashboard summarizes historical performance only.
- Relationships shown are descriptive and should not be interpreted as proof of causation.

---

## Screenshots Included

- full_dashboard.png
- sales_trend_view.png
- regional_performance_view.png
- category_profitability_view.png
- filter_interaction_view.png
