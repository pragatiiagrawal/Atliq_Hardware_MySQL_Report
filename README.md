# Atliq_Hardware_MySQL_Report
# 📊 AtliQ Hardware Ad-Hoc SQL Analytics Report

## 📄 About the Project

The **AtliQ Hardware Ad-Hoc SQL Analytics Report** is a data-driven project focused on analyzing sales and forecast data for **AtliQ Hardware**, a fictional computer hardware company. The primary objective was to generate actionable insights by leveraging SQL techniques to process and visualize over **1.43 million records**. This project explores sales performance, forecast accuracy, and customer trends — combining technical expertise with business intelligence.

## 📄 Project Overview

- Created the **AtliQ Hardware Ad-Hoc SQL Analytics Report** (_Atliq_Hardware_Ad-Hoc_SQL_Analytics_Report.pdf_)
- Analyzed sales and forecast data to uncover key business insights
- Focused on forecast accuracy comparisons across fiscal years

## 📂 Tables Used

- [x] **dim_customer** — Customer details (name, market, etc.)
- [x] **dim_product** — Product information (product code, variant, etc.)
- [x] **fact_sales_monthly** — Monthly sales data for products and customers
- [x] **fact_gross_price** — Product prices per fiscal year
- [x] **fact_pre_invoice_deductions** — Pre-invoice deductions for customers
- [x] **fact_post_invoice_deductions** — Post-invoice deductions for customers
- [x] **fact_actual_estimate** — Merged sales and forecast data to calculate forecast accuracy
- [x] **net_sales** — View summarizing net sales after post-invoice deductions
- [x] **sales_preinv_discount** — View capturing pre-invoice discount data
- [x] **sales_postinv_discount** — View combining pre-invoice and post-invoice discounts

_Additional temporary tables like_ **forecast_accuracy_2020** _and_ **forecast_accuracy_2021** _were used for comparative forecast accuracy analysis._

**Total Database Records:** 1,425,706 (approximately **1.43 million records**)

## 🛠️ Technical Skills Gained

- **SQL Queries:** Mastered complex SQL queries with multiple joins, subqueries, and aggregations to extract, manipulate, and analyze large datasets.
- **Data Extraction:** Efficiently extracted key data points from multiple tables using SQL queries, enabling accurate business insights.
- **User-Defined Functions (UDFs):** Created custom functions like `get_fiscal_year` and `get_fiscal_quarter` to dynamically compute fiscal year and quarter data.
- **Stored Procedures:** Automated repetitive tasks with stored procedures, including:
  - `get_monthly_gross_sales_for_customer`: Generates monthly gross sales reports for any customer.
  - `get_market_badge`: Assigns market badges (Gold/Silver) based on sales turnover.
- **Database Views:** Built and utilized views such as `sales_preinv_discount`, `sales_postinv_discount`, and `net_sales` for efficient data retrieval and future reuse.
- **CTEs and Window Functions:** Used Common Table Expressions (CTEs) and window functions (`DENSE_RANK()`, `SUM() OVER()`) for advanced data manipulation, including calculating net sales contribution and ranking top-performing products.
- **Forecast Accuracy Analysis:** Developed helper tables (`fact_actual_estimate`) and temporary tables (`forecast_accuracy_2020`, `forecast_accuracy_2021`) to track and compare forecast accuracy across fiscal years.

## 🎯 Soft Skills Gained

- **Business Requirement Translation:** Translated business needs — like tracking forecast accuracy and sales performance — into optimized SQL logic and queries.
- **Data Storytelling:** Presented data insights clearly by exporting SQL query results to Excel and creating impactful visualizations.

---

This project not only honed my technical SQL skills but also enhanced my analytical mindset, giving me a solid foundation in data-driven decision-making.

#DataAnalytics #SQL #MySQL #AtliQHardware #BusinessIntelligence #ForecastAccuracy #DataDriven
