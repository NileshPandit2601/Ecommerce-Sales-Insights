# Ecommerce Sales Analysis Project

## Project Overview

Analyze ecommerce sales data to uncover business insights using SQL and Python. The project focuses on identifying top products, customer behavior, time-based trends, and operational anomalies.

## Tools Used

* **MySQL**: Data querying
* **Python**: `pandas`, `matplotlib`, `seaborn`
* **Jupyter Notebook**: Interactive analysis

##  Key Insights

### SQL Analysis

* Customers with more than 5 orders and spend > ₹10,000
* Top 5 revenue-generating products
* Month with the highest number of orders
* Product with the highest return rate
* Day of the week with highest average sales volume
* Products with unusually high quantity sold in a single order

### Advanced SQL

* **CTEs**: Monthly revenue trend
* **Window Functions**: Product ranking using `RANK()`
* **Subqueries & Joins**: Customer cohort analysis and category comparisons

### Python Visualizations

* Bar chart: Quantity sold by product and category
* Line chart: Monthly revenue trend
* Bar + line overlay: Top products with return rates
* Bar chart: Return count for every product

## Project Structure

```text
├── sales.sql                          # SQL queries for insights and trends
├── Build Week2.ipynb                  # Jupyter Notebook with Python analysis
├── ER Diagram to 3NF                  
```

##  How to Run

1. Import dataset into MySQL and name the table `ecommerce`
2. Run SQL queries from `sales.sql` using MySQL Workbench or similar
3. Open `Build Week2.ipynb` in Jupyter Notebook
4. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn
   ```
5. Run each notebook cell to view insights and plots

##  Outcomes

* Identified high-value customers and products
* Visualized sales patterns by time and category
* Flagged anomalies and return-heavy products

