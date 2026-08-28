# Amazon E-Commerce Sales & Customer Behavior Analysis

**Data Analyst Portfolio Project — MySQL**

This project analyzes **1,000,000 Amazon e-commerce transactions** to identify actionable insights across sales performance, product/category economics, customer behavior, seller quality, pricing/discount strategy, returns, delivery operations, and inventory risk.

## Project Snapshot

- **Transactions:** 1,000,000
- **Customers:** 603,815
- **Products:** 89,999
- **Sellers:** 9,000
- **Categories:** 5
- **Subcategories:** 16
- **Brands:** 12
- **Cities:** 5
- **Analysis period:** 2024-03-31 to 2026-03-31

## Tools & SQL Skills

- MySQL
- Common Table Expressions (CTEs)
- Window functions: `LAG()`, `DENSE_RANK()`
- `CASE WHEN` bucketing
- `GROUP BY` and aggregations
- `HAVING`
- Date-based analysis
- Return-rate analysis
- Seller quality analysis
- Business-focused KPI analysis

## Key Business Findings

1. Electronics generated **66.3% of revenue** while representing about **17.7% of orders**, driven primarily by much higher average order value.
2. Monthly realized revenue remained broadly stable around the **₹33.5–₹38.0 Cr** range in the report period.
3. Overall return rate was **11.60%**; the 5–7 day shipping group had a **14.39%** return rate.
4. The report identified a significant seller-quality gap: high-revenue sellers were not necessarily highly rated.
5. Customers averaged about **1.66 orders per customer**, indicating a broad-reach, relatively low-repeat marketplace.
6. The **40%+ discount band** had more orders but substantially lower revenue than the 10–19% band.
7. **39,659 products** were below the 20-unit stock threshold.

## Repository Structure

```text
Amazon-Ecommerce-Analysis/
│
├── README.md
├── report/
│   └── Amazon_Ecommerce_Analysis_MujahidKhan.pdf
│
└── sql/
    └── amazon_ecommerce_analysis_queries.sql
```

## Important Note

The PDF contains selected SQL examples rather than the complete 30+ query source set. The SQL file in this repository therefore contains the query logic visible in the report. If you have the original full `.sql` query set, replace/add it before presenting the repository as the complete 30+ query project.

The report also documents a data-quality issue involving `delivery_status` and `is_returned`. Revenue queries use `is_returned = FALSE`, while `delivery_status` is used for delivery-performance analysis.

## Portfolio Report

See the PDF report in the `report/` folder for the complete business analysis, outputs, insights, and recommendations.

## Author

**Mujahid Khan**  
Data Analyst

- LinkedIn: https://www.linkedin.com/in/mujahidkhan-data-analyst/
- GitHub: https://github.com/

