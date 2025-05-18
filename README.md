Ecommerce Sales Analysis Project

Project Overview

This project focuses on analyzing ecommerce sales data to uncover meaningful business insights. We used SQL for querying and Python for visualization and data storytelling. The goal is to understand customer behavior, product performance, and time-based trends.

Tools Used

MySQL for querying data

Python libraries including pandas, matplotlib, and seaborn

Jupyter Notebook for exploratory analysis and plotting

Key Analyses and Visualizations

SQL Insights:

Identified customers who placed more than five orders and spent over 10,000

Found the top five revenue-generating products

Determined the month with the highest number of orders

Highlighted the product with the highest return rate

Identified the day of the week with the highest average sales volume

Detected products with unusually high quantities in a single order to flag potential fraud

Advanced SQL Techniques:

Used common table expressions (CTEs) to calculate monthly revenue trends

Applied window functions like RANK to rank products by revenue

Performed customer cohort analysis by tracking cumulative monthly spend

Compared product-level revenue with average category revenue using subqueries and joins

Python Visualizations:

Bar charts showing quantity sold by product and category

Line chart for monthly revenue trends

Combination of bar and line chart to show top products with return rate overlay

Bar chart displaying return counts for each product

File Structure

sales.sql: Contains all SQL queries used in the project

Build Week2.ipynb: Jupyter Notebook with Python analysis and visualizations

Ecommerce_Data_Storytelling_Presentation.pptx: Presentation summarizing insights

How to Run This Project

Load your dataset into a MySQL database and name the table 'ecommerce'

Run the SQL queries in MySQL Workbench or another SQL IDE

Open the Jupyter Notebook file 'Build Week2.ipynb'

Make sure you have installed the required Python libraries: pandas, matplotlib, and seaborn

Run the notebook cells to generate insights and visualizations

Outcomes

Identified valuable customers and high-performing products

Gained insights into how sales vary over time and by category

Detected anomalies such as excessive returns and potential fraud
