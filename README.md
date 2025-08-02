# Retail-Sales-Project-

## 📂 Project Structure
### 📌 Data Cleaning
- Identified and removed rows with `NULL` values in critical fields like `transaction_id`, `sale_date`, `sale_time`, `gender`, `category`, etc.

### 📌 Data Exploration
- Total number of sales
- Number of unique customers
- Available product categories

### 📌 Business Questions Answered

| Query No. | Description |
|-----------|-------------|
| Q1 | Retrieve all sales made on a specific date (`2022-11-05`) |
| Q2 | Filter sales for 'Clothing' category with quantity > 4 in Nov 2022 |
| Q3 | Calculate total sales and order count per category |
| Q4 | Average age of customers who purchased 'Beauty' products |
| Q5 | List all transactions where `total_sale > 1000` |
| Q6 | Count transactions by gender and category |
| Q7 | Find the best-selling month in each year by average sales |
| Q8 | Top 5 customers by total sales |
| Q9 | Unique customers per category |
| Q10 | Classify orders by time of day (Morning, Afternoon, Evening) |

---

## 🧮 Tools & Concepts Used

- SQL (PostgreSQL / standard SQL)
- Window functions (`RANK() OVER`)
- `EXTRACT()`, `TO_CHAR()` for date manipulation
- Common Table Expressions (CTEs)
- Aggregations and grouping
- Data cleaning techniques using `IS NULL`, `DELETE`

---

## 📊 Use Cases

- Identify high-performing categories and shifts
- Understand customer demographics
- Help retailers optimize operations and marketing based on data insights

---

## 🚀 Getting Started

To run the analysis:
1. Create the database:
   ```sql
   CREATE DATABASE sql_project_p2;
