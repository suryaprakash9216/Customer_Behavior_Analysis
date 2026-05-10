# Customer Shopping Behavior Analysis

## Overview

This project presents an end-to-end data analytics workflow focused on understanding customer shopping behavior and purchasing patterns. The analysis was performed using Python, SQL, and Power BI to transform raw transactional data into meaningful business insights and interactive visualizations.

The project covers the complete analytics lifecycle, including data loading, preprocessing, exploratory data analysis (EDA), SQL-based querying, dashboard development, reporting, and presentation creation. The primary objective was to identify trends in customer purchasing behavior, discount usage, subscription patterns, product performance, and demographic-based spending.

# Dataset Information

The dataset contains customer transaction and behavioral information collected from a retail shopping environment. It includes various customer, product, and purchasing attributes such as:

* Customer demographics
* Product categories
* Purchase amounts
* Review ratings
* Subscription status
* Shipping preferences
* Discount usage
* Previous purchase history
* Payment methods
* Seasonal purchasing trends

The dataset was initially processed in Python and later integrated into SQL databases for advanced querying and business analysis.

# Tools & Technologies Used

## Programming & Data Analysis

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Database Technologies

* MySQL
* PostgreSQL
* SQL Server
* SQL Queries

## Data Visualization & BI

* Power BI

## Reporting & Presentation

* Microsoft PowerPoint
* Gamma AI

# Project Workflow

## 1. Data Loading

The dataset was imported into Jupyter Notebook using Pandas. Initial inspection was performed to understand the structure, columns, datatypes, and quality of the data.

## 2. Data Cleaning & Preprocessing

Several preprocessing techniques were applied to improve data quality and prepare the dataset for analysis:

* Handling missing values
* Renaming columns for SQL compatibility
* Correcting datatypes
* Removing inconsistencies
* Preparing categorical variables
* Creating custom groupings such as age segments

## 3. Exploratory Data Analysis (EDA)

Exploratory analysis was performed to identify customer behavior patterns and business insights. The analysis included:

* Revenue analysis
* Gender-based spending analysis
* Discount impact analysis
* Subscription behavior analysis
* Product category performance
* Customer segmentation
* Review rating analysis
* Age group contribution analysis

## 4. SQL Database Integration

The cleaned dataset was loaded into relational databases such as MySQL, PostgreSQL, and SQL Server. SQL queries were executed to extract business insights using:

* Aggregate functions
* Filtering and sorting
* GROUP BY operations
* CASE statements
* Subqueries
* Window functions
* Customer segmentation logic

## 5. Power BI Dashboard Development

An interactive Power BI dashboard was created to visualize customer purchasing behavior and business metrics. The dashboard allows users to explore insights dynamically through filters, KPIs, and charts.

### Dashboard Features

* Total Revenue KPI
* Average Review Rating
* Revenue by Gender
* Revenue by Age Group
* Product Category Analysis
* Subscription Status Insights
* Discount Usage Analysis
* Shipping Type Comparison
* Top Purchased Products
* Customer Purchase Trends

## 6. Reporting & Presentation

A detailed analytical report was prepared summarizing the methodology, analysis, findings, and business insights. Presentation slides were designed using Gamma AI and PowerPoint to effectively communicate the project outcomes.

# Key Business Insights

* Customers who used discounts still contributed significantly to total revenue.
* Subscription customers showed higher purchasing activity and spending behavior.
* Certain product categories generated consistently high sales and customer engagement.
* Middle-aged and adult customers contributed the largest share of overall revenue.
* Review ratings helped identify highly preferred products and categories.
* Seasonal purchasing patterns influenced customer buying behavior.

# How to Run the Project

## Step 1: Clone the Repository

```bash id="o6x2m4"
git clone <repository-link>
```

## Step 2: Install Required Libraries

```bash id="o6x2m5"
pip install pandas numpy sqlalchemy pymysql
```

## Step 3: Open the Jupyter Notebook

Run the notebook file:

```text id="o6x2m6"
Customer_Shopping_Behavior_Analysis_surya.ipynb
```

## Step 4: Configure Database Connection

* Create a database in MySQL/PostgreSQL/SQL Server
* Update database credentials in the notebook
* Execute the SQL integration cells

## Step 5: Open Power BI Dashboard

Open the Power BI dashboard file:

```text id="o6x2m7"
Customer_Behavior_Dashboard.pbix
```

to explore the interactive visualizations and business insights.

---

# Project Files

| File Name                                         | Description                                             |
| ------------------------------------------------- | ------------------------------------------------------- |
| `customer_shopping.csv`                           | Raw customer shopping dataset                           |
| `Customer_Shopping_Behavior_Analysis_surya.ipynb` | Python notebook containing analysis and SQL integration |
| `Customer_Behavior_Dashboard.pbix`                | Interactive Power BI dashboard                          |
| `README.md`                                       | Project documentation                                   |

---

# Conclusion

This project demonstrates practical data analytics and business intelligence skills by combining Python, SQL, and Power BI to analyze customer shopping behavior. The project highlights the complete workflow from raw data processing to dashboard visualization and insight generation. It showcases the ability to transform transactional data into actionable business decisions using modern analytical tools and techniques.
