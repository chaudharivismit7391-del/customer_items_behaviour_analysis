Customer Shopping Behavior Analysis
An end-to-end data analytics project that turns customer shopping data into clear, useful business insights. The workflow covers data preparation in Python, SQL analysis, an interactive Power BI dashboard, and a written report with a presentation.
Overview
This project explores how customers shop, what they purchase, and how customer and purchase characteristics relate to sales. It uses Python for data preparation and exploratory data analysis (EDA), SQL for structured analysis, and Power BI to present key measures and trends.
Dataset
The project uses customer_shopping_behavior.csv, a customer shopping dataset with fields such as:
- Customer demographics: age, gender, and location
- Purchase details: item, category, purchase amount, season, and size
- Customer behavior: subscription status, previous purchases, and purchase frequency
- Order details: discount and promo code usage, payment method, and shipping type
- Feedback: review rating
Place the CSV in the project folder before running the notebook. Confirm you have permission to share the dataset before publishing it.

Tools
- Python: Pandas for loading, cleaning, transforming, and exploring the data
- Jupyter Notebook: Analysis workflow and documentation
- SQL: PostgreSQL for database storage and querying; queries can be adapted for MySQL or SQL Server
- SQLAlchemy: Python-to-database connection and table loading
- Power BI: Interactive dashboard and visual analysis

  
Steps
1. Load the CSV into Python with Pandas.
2. Inspect data types, missing values, duplicates, and category values.
3. Clean and prepare fields, including consistent column names and derived customer or purchase features.
4. Perform EDA to understand distributions, customer segments, purchase patterns, and sales measures.
5. Load the prepared DataFrame into a PostgreSQL table using SQLAlchemy.
6. Query the data with SQL to compare customer segments, product categories, discount usage, purchase frequency, and age groups.
7. Connect Power BI to the database and build an interactive dashboard.
8. Summarize the process and findings in a report, then create a presentation in Gamma.

Dashboard
The Power BI dashboard is designed to explore:
- Customer count, average purchase amount, and average review rating
- Subscription status and customer segments
- Revenue and sales by product category
- Revenue and sales by age group
- Discount usage, shipping type, gender, and other customer filters


Results
The analysis provides a reusable view of customer and sales performance. It helps compare category revenue, sales volume, customer segments, subscription patterns, discount usage, and purchase frequency. The dashboard makes these measures easier to filter and review, while the report and presentation communicate the main findings.
