# SalesVision — Sales & Profitability Analytics System

## Project Overview

SalesVision is a data analytics project designed to analyze retail sales, profitability, customer segments, product categories, discounts, and regional performance. It uses Python, SQL, and Power BI to turn raw sales data into actionable business insights.

## Objectives

* Analyze overall sales and profit performance.
* Identify the most profitable product categories.
* Compare sales and profit across regions.
* Identify loss-making sub-categories.
* Understand customer segment performance.
* Build an interactive Power BI dashboard.

## Tools & Technologies

* Python
* Pandas and NumPy
* Matplotlib
* SQL
* Power BI
* Jupyter Notebook

## Key Performance Indicators

* Total Sales: 2,326,534.35
* Total Profit: 292,296.81
* Total Orders: 5,111
* Overall Profit Margin: 12.56%

*Note: Currency is not specified because the dataset's currency unit has not been verified.*

## Key Business Insights

1. Technology generated the highest sales and profit among the three categories.
2. Furniture had a relatively low profit margin of approximately 2.61%, despite substantial sales.
3. The West region recorded the highest sales and total profit.
4. Tables was the largest loss-making sub-category, followed by Bookcases and Supplies.
5. Consumer customers contributed the highest sales and total profit among customer segments.
6. Higher-discount groups showed negative aggregate profit in several discount bands; this is an association and does not by itself establish causation.

## Dashboard

The Power BI dashboard includes:

* Sales, profit, order, and profit-margin KPI cards
* Sales by Category
* Profit Contribution by Region
* Profit by Sub-Category
* Monthly Sales Trend
* Maximum and Minimum Sales cards

## Project Structure

```text
SalesVision/
├── data/
│   ├── raw/
│   └── notebooks/
├── sql/
├── powerbi/
│   └── SalesVision_Dashboard.pbix
├── reports/
├── README.md
└── requirements.txt
```

## How to Run

1. Open the Jupyter Notebook.
2. Install the required Python libraries.
3. Load and explore the dataset.
4. Run the SQL analysis queries.
5. Open `powerbi/SalesVision_Dashboard.pbix` in Power BI Desktop.

## Dataset

This project uses a sample retail Superstore dataset for learning and analytical demonstration. Findings describe the provided dataset and should not be interpreted as actual company performance.

## Author

B.Tech Data Science Student
