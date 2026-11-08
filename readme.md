# E-Commerce Customer Analytics & RFM Segmentation

**An end-to-end Data Analytics project using SQL, Python, and Power BI to analyze customer behavior, sales performance, customer value, and retention opportunities.**

---

## Project Overview

This project focuses on analyzing transactional data from an e-commerce business to understand customer purchasing behavior, identify high-value customers, evaluate sales performance, and uncover customer retention opportunities.

The project follows a real-world data analytics workflow, starting with raw transactional data and transforming it into meaningful business insights through SQL, Python, and Power BI.

The primary objective is to help businesses make data-driven decisions by understanding customer value, purchasing patterns, revenue distribution, and customer churn.

## Business Problem

E-commerce businesses generate large amounts of transactional data, but raw data alone does not provide meaningful insights into customer behavior or business performance.

Businesses need to understand:

- Which customers contribute the most to overall revenue?
- Which customer segments are most valuable?
- Which customers are at risk of becoming inactive?
- How do purchasing patterns and revenue change over time?
- Which countries or markets generate the highest revenue?
- What strategies can improve customer retention and lifetime value?

This project addresses these questions through data analysis, customer segmentation, and interactive business intelligence dashboards.

## Project Objectives

- Perform data cleaning and transformation using SQL.
- Conduct Exploratory Data Analysis (EDA) using Python.
- Analyze customer purchasing behavior and transaction patterns.
- Implement RFM (Recency, Frequency, Monetary) analysis.
- Segment customers based on their purchasing behavior.
- Identify inactive and potentially churned customers.
- Analyze revenue trends and customer performance.
- Develop an interactive Power BI dashboard.
- Generate actionable business recommendations.

## Dataset

**Dataset:** Online Retail II

**Source:** UCI Machine Learning Repository

The dataset contains real-world transactional records from a UK-based online retail business selling giftware and other products.

| Attribute | Details |
|---|---|
| Dataset | Online Retail II |
| Source | UCI Machine Learning Repository |
| Time Period | December 2009 – December 2011 |
| Raw Records | Approximately 1.06 million |
| Business Domain | E-commerce / Retail |
| Data Type | Transactional Data |

**Dataset Source:** https://archive.ics.uci.edu/dataset/502/online+retail+ii

The dataset includes invoice numbers, product descriptions, quantities, invoice dates, unit prices, customer identifiers, and country information.

## Technology Stack

| Technology | Purpose |
|---|---|
| SQL Server | Data cleaning, transformation, deduplication, and querying |
| Python | Data analysis, customer segmentation, and calculations |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib / Seaborn | Exploratory data visualization |
| Jupyter Notebook | Interactive analysis and development |
| Power BI | Interactive dashboards and business reporting |
| DAX | Calculated measures and business KPIs |
| Excel | Data inspection and validation |

## Project Workflow

### 1. Business Understanding
- Identify business objectives and analytical requirements.
- Define key performance indicators (KPIs).
- Establish business questions and expected outcomes.
- Understand customer retention and revenue analysis requirements.

### 2. SQL – Data Cleaning & Exploration
- Import raw transactional data into SQL Server.
- Combine data from multiple sheets.
- Handle missing and invalid values.
- Resolve inconsistent date formats and data types.
- Identify and remove duplicate records.
- Validate transaction records and perform exploratory SQL queries.
- Prepare a structured dataset for further analysis.

**SQL concepts covered:**
- SELECT, WHERE, ORDER BY
- GROUP BY and HAVING
- Aggregate Functions
- CASE Statements
- Joins and Subqueries
- CTEs
- Window Functions
- TRY_CONVERT and Data Type Handling

### 3. Python – Exploratory Data Analysis & RFM Analysis

Use Python to investigate customer behavior and identify meaningful patterns in transactional data.

**Exploratory Data Analysis:**
- Analyze transaction and customer distributions.
- Identify top-performing products.
- Explore revenue trends over time.
- Analyze country-wise sales performance.
- Examine customer purchasing frequency.
- Identify outliers and unusual transaction patterns.

**RFM Analysis:**

RFM analysis evaluates customers using three important metrics:

| Metric | Description |
|---|---|
| Recency | How recently a customer made a purchase |
| Frequency | How frequently a customer purchases |
| Monetary | How much a customer spends |

Customers are scored based on these three metrics and grouped into meaningful customer segments.

**Customer Segments:**
- Champions
- Loyal Customers
- At Risk
- New Customers
- Needs Attention
- Lost Customers

### 4. Power BI – Interactive Dashboard

Develop an interactive Power BI dashboard to transform analytical results into business insights.

**Dashboard Components:**

**Page 1 – Home**
- Project overview
- Dashboard navigation
- KPI definitions and business glossary

**Page 2 – Business Overview**
- Total Customers
- Total Revenue
- Customer Churn Percentage
- Average Customer Value
- Revenue trends
- Customer segment distribution
- Country-wise performance
- Monthly, quarterly, and yearly analysis

**Page 3 – RFM Analysis**
- Customer segment performance
- Customer count by segment
- Revenue contribution by segment
- Average RFM scores
- Customer value comparison
- Churn analysis and trends

**Power BI Features:**
- Interactive slicers and filters
- DAX measures
- Drill-down analysis
- Bookmark-based navigation
- Dynamic KPI calculations
- Interactive visualizations

## Key Business Metrics

| KPI | Description |
|---|---|
| Total Revenue | Overall revenue generated from transactions |
| Total Customers | Number of unique customers |
| Average Customer Value | Average revenue generated per customer |
| Customer Churn Rate | Percentage of customers classified as inactive |
| Purchase Frequency | Average number of purchases per customer |
| Revenue Contribution | Revenue generated by individual customer segments |

*Final KPI values and analytical findings will be documented after completing and validating the analysis.*

## Expected Business Outcomes

The analysis aims to help businesses:

- Identify high-value customers and prioritize retention strategies.
- Understand customer purchasing patterns.
- Identify customers requiring re-engagement campaigns.
- Monitor revenue performance and seasonal trends.
- Evaluate customer segment profitability.
- Make informed decisions using interactive business intelligence reports.

## Repository Structure

```text
Ecommerce-Customer-Analytics-RFM-Segmentation/
│
├── 01_SQL/
│   ├── data_import.sql
│   ├── data_cleaning.sql
│   └── exploratory_analysis.sql
│
├── 02_Python/
│   ├── exploratory_data_analysis.ipynb
│   └── rfm_customer_segmentation.ipynb
│
├── 03_PowerBI/
│   └── customer_analytics_dashboard.pbix
│
├── 04_Dataset/
│   └── README.md
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

## How to Run the Project

1. Download the Online Retail II dataset from the UCI Machine Learning Repository.
2. Import the dataset into SQL Server.
3. Execute the SQL scripts in the `01_SQL` folder sequentially.
4. Export the cleaned dataset for Python analysis.
5. Run the Jupyter notebooks in the `02_Python` folder.
6. Perform RFM calculations and generate customer segments.
7. Import the processed data into Power BI.
8. Open the Power BI dashboard and refresh the data source.
9. Explore customer behavior, revenue trends, and business insights.

## Learning Outcomes

Through this project, I aim to strengthen my practical understanding of:

- Real-world data cleaning and preprocessing.
- Writing analytical SQL queries.
- Exploratory Data Analysis using Python.
- Customer segmentation and RFM modeling.
- Business KPI development.
- Power BI dashboard development.
- Translating raw data into actionable business insights.

## Acknowledgements & Credits

- **Dataset:** [Online Retail II – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)


This project is developed for educational and portfolio purposes, using the above project as a learning reference. The implementation, analysis, visualizations, and additional modifications will be documented as the project evolves.

## Disclaimer

This project uses publicly available, anonymized transactional data for educational and analytical purposes. IKEA Gifting is a fictional business concept and is not affiliated with or endorsed by the real IKEA corporation.

---

**Developed by Shivam Singh**

 SQL | Python | Power BI | Data Analytics

GitHub: https://github.com/shivamsingh-itds