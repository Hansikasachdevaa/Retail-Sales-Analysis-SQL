# Retail-Sales-Analysis-SQL
 
# Retail Sales Analysis with SQL

This project analyzes a retail sales dataset using SQL queries. It covers:

- Total sales per category and gender
- Customer insights: top customers, multi-category buyers, increasing spenders
- Time-based trends: best-selling months, weekdays, shifts, month-over-month growth
- Category/Product insights: profit margins, high COGS/low margin, declining categories
- Pareto analysis: top 20% customers contributing to 80% revenue
- Age group contributions

## Dataset

- Columns: `transaction_id`, `sale_date`, `sale_time`, `customer_id`, `gender`, `age`, `category`, `quantity`, `price_per_unit`, `cogs`, `total_sale`
- Sample size: 2000 rows 

## Queries

All SQL queries are in [`retail_sales.sql`](retail_sales.sql)

## Key Insights

- **Highest profit margin category:**
Beauty -79.71%

- **Low profit margin but high COGS:**
- Electronics- 79.58%

- **Top 5 customers by sales:**
customer_id   Total_sales
3 	           38440
1	             30750
5	             30405
2              25295
4	             23580
  
- **Age group contributing most to revenue:**
- 41-60 age group with 384295 Total_sales

## Screenshots

![Total Sales per category] <img width="481" height="143" alt="Total_sales_per_category" src="https://github.com/user-attachments/assets/2664e7c8-85b8-411e-b051-f14d8e02fbf1" />

![Top Customers]<img width="1096" height="316" alt="image" src="https://github.com/user-attachments/assets/034055d9-86e2-49af-8690-8c4aec496d1e" />
)  
![Profit Margin](<img width="787" height="182" alt="image" src="https://github.com/user-attachments/assets/c1832fc2-b642-49fd-a1cd-d1071453d222" />
)

## How to Run

1. Import `retail_sales` dataset into MySQL.  
2. Run queries from `retail_sales.sql` sequentially to reproduce insights.  

---

*Project by Hansika Sachdeva*
