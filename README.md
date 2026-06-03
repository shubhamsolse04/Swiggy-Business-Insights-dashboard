# Swiggy Business Insights Dashboard

## Project Overview

This project analyzes Swiggy order data using MySQL and Power BI to uncover insights related to revenue, customer preferences, restaurant performance, and location-wise demand.

The project demonstrates an end-to-end analytics workflow, starting from data cleaning and SQL analysis to building interactive dashboards for business decision-making.

---

## Tools and Technologies

- MySQL
- Power BI
- DAX
- Excel

---

## Dataset Summary

- Total Orders: 197,240
- Total Revenue: 53.01M
- Restaurants: 993
- Cities: 28
- Dates: 243

---

## Project Workflow

### 1. Data Understanding

- Explored the dataset and relationships among tables.
- Studied orders, restaurants, dishes, locations, and dates.

### 2. Data Cleaning

- Corrected inconsistent date formats.
- Handled missing values and rating count anomalies.
- Standardized location information.
- Created derived columns for improved analysis.
- Added an `is_recommended` flag for recommended dishes.

### 3. SQL Analysis

Performed analytical queries to answer business questions related to:

- Revenue trends
- Restaurant performance
- Dish performance
- Order density
- Location-wise demand
- Customer ratings
- Growth opportunities

### 4. Power BI Dashboard Development

Created interactive dashboard pages to visualize KPIs and business insights.

---

## SQL Concepts Used

- Joins
- Aggregate Functions
- CASE Statements
- GROUP BY and HAVING
- Subqueries
- Window Functions
- Common Table Expressions (CTEs)

---

## Business Questions Solved

- Which restaurants generate the highest revenue?
- Which dishes contribute most to sales?
- Which locations have the highest order density?
- Which cities show growing demand over time?
- Which restaurants should be promoted more?
- Are expensive dishes rated higher?
- Which dishes require improvement?
- How would you segment restaurants based on performance?

---

## Dashboard Pages

### Overview Dashboard

- Revenue KPIs
- Orders and Ratings
- State-wise performance
- Category analysis

### Restaurant Analysis

- Top restaurants by revenue
- Average daily orders
- Restaurant ratings
- Average order value

### Dish Analysis

- Top dishes by revenue
- Category performance
- Daily demand patterns
- Average order value

### City and Trend Analysis

- Revenue by city and state
- Order density
- Monthly revenue trends
- Seasonal demand analysis

---

## Key Insights

- Identified top-performing restaurants and dishes.
- Discovered high-demand locations and cities.
- Analyzed customer ordering behavior and ratings.
- Examined monthly revenue trends and demand patterns.
- Generated actionable insights for business optimization.

---

## Repository Structure

```
swiggy-business-insights-dashboard
│
├── Dashboard Screenshots
│     ├── Overview Dashboard.png
│     ├── Restaurant Analysis.png
│     ├── Dish Analysis.png
│     └── City and Trend Analysis.png
│
├── SQL Queries.sql
├── Swiggy Business Insights Presentation.pptx
├── Dataset
└── README.md
```

---

## Business Impact

This project demonstrates how MySQL and Power BI can be used together to transform raw transactional data into meaningful business insights. The analysis helps identify revenue drivers, customer preferences, high-demand areas, and opportunities for improving restaurant and dish performance.

---

## Author

**Shubham Solse**

LinkedIn: <Your LinkedIn Profile URL>

GitHub: <Your GitHub Profile URL>
