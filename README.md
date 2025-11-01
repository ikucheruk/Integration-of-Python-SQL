# Integration-of-Python-SQL
Analysis of sales data from the Classicmodels database using Python and SQL — including revenue breakdowns, product performance insights, and data visualization in Python.

🧩 Project: Integration of Python & SQL — Data Analysis on the Classicmodels Database

🎯 Goal  
Demonstrate how to integrate Python and SQL for data extraction, analysis, and visualization using the Classicmodels sample database.

⚙️ Tools & Technologies  
Python: pandas, SQLAlchemy, matplotlib, seaborn  
MySQL (via Docker container)  
.env configuration for secure connection parameters  


📊 Key Steps  
- Established a database connection via SQLAlchemy with connection pooling.  
- Retrieved and analyzed data using pandas.read_sql().  
- Built analytical SQL queries with JOINs, CTEs, and window functions.  
- Visualized results with Python — bar charts and pie charts for revenue analysis.  
- Conducted business-oriented analytics, including:  
    - Top products by total revenue  
    - Revenue distribution by country and product line  
    - Pareto analysis (80/20 principle)  
    - Product segmentation into Top performers and Low performers  



💡 Key Insights
- The Top-1 product generates over 10× more revenue than the 10th product.  
- The Top-2 product lines contribute over 60% of total sales.  
- Around 20% of products drive 80% of the total revenue.  
- The “Top vs. Low performers” classification helps quickly identify optimization opportunities.


