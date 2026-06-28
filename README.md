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
