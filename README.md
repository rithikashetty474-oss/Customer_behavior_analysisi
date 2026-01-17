# Customer Shopping Behavior Analysis 📊

## Overview
This project analyzes customer shopping behavior for a retail business to uncover trends, understand purchasing patterns, and generate actionable business insights. The analysis focuses on how factors such as demographics, discounts, product categories, reviews, and payment methods influence customer decisions and repeat purchases.

The project demonstrates an end-to-end **Data Analytics workflow** using Python, SQL, and Power BI, and presents insights through a dashboard, report, and presentation.

---

## Dataset
- Customer shopping behavior dataset containing:
  - Customer demographics (age, gender, location)
  - Product details (category, item purchased)
  - Purchase information (amount, discounts, frequency)
  - Reviews and ratings
  - Payment and subscription details
- Source: Provided retail consumer behavior dataset (CSV format)

---

## Tools & Technologies
- **Python**: Data loading, cleaning, and exploratory data analysis (EDA)
- **Pandas, NumPy, Matplotlib, Seaborn**: Data manipulation and visualization
- **SQL**: Business analysis queries  
  - PostgreSQL / MySQL / SQL Server
- **Power BI**: Interactive dashboard creation
---

## Project Workflow
1. **Data Loading**
   - Imported raw CSV data into Python using Pandas.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed distributions, trends, and relationships.
   - Identified missing values and inconsistencies.

3. **Data Cleaning & Transformation**
   - Handled missing data and data type issues.
   - Created new features such as customer segments and age groups.

4. **SQL Analysis**
   - Loaded cleaned data into a relational database.
   - Wrote SQL queries to answer business questions such as:
     - Revenue by gender
     - High-value discounted purchases
     - Top products by category
     - Customer segmentation (New, Returning, Loyal)

5. **Power BI Dashboard**
   - Built interactive visuals to track:
     - Revenue trends
     - Customer segments
     - Product performance
     - Discount impact


---

## Dashboard
The Power BI dashboard provides:
- Customer segmentation overview
- Sales and revenue trends
- Top-performing products and categories
- Impact of discounts and reviews on purchasing behavior

📌 *Dashboard file included in the repository.*

---

## Key Insights & Results
- Identified high-value customer segments contributing the most revenue.
- Found products and categories with the highest demand.
- Analyzed the effectiveness of discounts on purchase behavior.
- Highlighted patterns in repeat purchases and customer loyalty.

---

## How to Run the Project

### 1. Python Analysis
```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
---
-Open the Jupyter Notebook and run all cells:
customer_shopping_behavior_analysis.ipynb
### 2. SQL Analysis
Load the cleaned dataset into PostgreSQL / MySQL / SQL Server.

-Execute queries from:
customer_behavior_sql_queries.sql
###3. Power BI
-Open the .pbix file in Power BI Desktop.

-Refresh the data connection if required.

###Project Structure

Customer-Shopping-Behavior-Analysis/
│── data/
│   └── customer_shopping_behavior.csv
│── notebooks/
│   └── customer_shopping_behavior_analysis.ipynb
│── sql/
│   └── customer_behavior_sql_queries.sql
│── powerbi/
│   └── customer_behavior_dashboard.pbix

