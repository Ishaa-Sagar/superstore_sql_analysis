# superstore_sql_analysis

This project analyzes real-world retail data from the Superstore dataset using SQL only. The analysis was performed in SQL Server Management Studio (SSMS) and focuses on extracting business insights across customer segments, product trends, regional sales performance, and shipping efficiency.

## Tools Used
- SQL Server Management Studio (SSMS)
- T-SQL (Transact-SQL)

## Topics Covered
- Monthly and regional sales trends
- Top products and customers by sales
- Category and sub-category performance
- Shipping mode and delivery time analysis
- Core business KPIs such as total revenue, average order value, and customer count
- Set Operations: `UNION`, `INTERSECT`, and `EXCEPT` examples
- Trigger: Automatically logs new order inserts in an audit table
- View: A reusable summary of sales by state and segment


## Insights
- California generated the highest sales among all states
- Chairs and Phones were the top-performing product categories
- Corporate customers had higher average order values compared to consumers
- States with high-value orders or corporate customer presence can be targeted for strategic marketing and premium services.
- INTERSECT and EXCEPT helped detect category overlaps and isolated product strengths
- The insert trigger acts as a basic audit system for tracking new orders — a useful feature in real-world retail databases
- A reusable reporting view was created for segment-level sales and profit summaries
