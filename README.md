# Sales Performance Analysis 📊

## Project Overview

This project analyzes retail sales data across multiple regions, products, customer segments, promotions, and sales teams to uncover business insights and support data-driven decision-making.

The analysis focuses on:

* Sales performance by region and product
* Customer purchasing behavior
* Promotion effectiveness
* Salesperson and regional manager performance
* Revenue and profitability trends
* Return behavior analysis
* Delivery and operational efficiency
* Interactive and static visualizations

---

## Business Problem

Organizations often struggle to identify:

* Which products generate the highest revenue
* Which regions contribute most to sales
* How promotions impact revenue
* Customer purchasing patterns
* Return-related risks
* Top-performing sales teams

This project addresses these challenges through comprehensive Exploratory Data Analysis (EDA), KPI generation, and visualization.

---

## Dataset Information

**Dataset Name:** Product Sales by Region Dataset

**Domain:** Retail & Wholesale Sales Analytics

**Source:** ExcelX Practice Data

**Records:** 1,500 Transactions

**Features:** 19 Columns

### Key Attributes

| Column         | Description          |
| -------------- | -------------------- |
| Date           | Order Date           |
| Region         | Sales Region         |
| Product        | Product Category     |
| Quantity       | Units Sold           |
| Unit Price     | Price Per Unit       |
| Discount       | Applied Discount     |
| Total Price    | Final Sales Value    |
| Customer Type  | Retail / Wholesale   |
| Payment Method | Mode of Payment      |
| Promotion      | Promotion Applied    |
| Shipping Cost  | Logistics Cost       |
| Salesperson    | Sales Representative |
| Region Manager | Regional Manager     |
| Returned       | Return Indicator     |

---

## Technology Stack

| Technology       | Purpose                      |
| ---------------- | ---------------------------- |
| Python           | Data Analysis                |
| Pandas           | Data Cleaning & Manipulation |
| NumPy            | Numerical Operations         |
| Matplotlib       | Data Visualization           |
| Seaborn          | Statistical Visualization    |
| Plotly           | Interactive Dashboards       |
| OpenPyXL         | Excel File Handling          |
| Jupyter Notebook | Development Environment      |

---

## Project Workflow

### 1️⃣ Data Collection

* Loaded Excel sales dataset
* Created a working copy of raw data

### 2️⃣ Data Cleaning

* Handled missing values
* Removed inconsistencies
* Standardized categorical values
* Checked duplicate records

### 3️⃣ Feature Engineering

Created new business metrics:

* Gross Sales
* Net Revenue
* Discount Amount
* Delivery Days
* Return Status
* Year
* Month
* Quarter

### 4️⃣ Exploratory Data Analysis (EDA)

#### Univariate Analysis

* Product Distribution
* Payment Method Distribution
* Total Price Distribution
* Delivery Days Distribution

#### Bivariate Analysis

* Region vs Sales
* Product vs Revenue
* Promotion vs Sales
* Customer Type vs Order Value

#### Multivariate Analysis

* Region-Product Revenue Analysis
* Year-Region Sales Trends
* Salesperson-Manager Performance
* Promotion Impact Analysis

---

## Key Insights

### Regional Performance

* North region generated the highest sales revenue.
* South region showed the lowest overall sales performance.
* North serves as the primary revenue contributor.

### Product Performance

* Electronics products contributed significantly to revenue.
* High-value products such as Laptops and Tablets dominated sales.

### Customer Behavior

* Retail and Wholesale customers showed distinct purchasing patterns.
* Wholesale orders generated larger transaction values.

### Promotion Analysis

* Promotional campaigns positively influenced revenue.
* FREE SHIP promotions produced strong customer engagement.

### Payment Preferences

* Online payments were the most preferred payment method.
* Digital payment adoption was consistently strong across regions.

### Operational Insights

* Average delivery time ranged between 4–8 days.
* Certain products exhibited higher return rates, indicating potential quality or expectation gaps.

### Sales Team Performance

* Significant differences existed among salesperson contributions.
* Regional manager performance influenced overall regional revenue outcomes.

---

## Visualizations Included

### Product & Revenue Analysis

* Product Frequency Count Plot
* Gross Sales vs Net Revenue
* Product Revenue Comparison

### Regional Analysis

* Total Sales by Region
* Region-wise Product Heatmap
* Region-Product Revenue Matrix

### Customer Analysis

* Customer Type Comparison
* Payment Method Distribution
* Order Value Distribution

### Promotion Analysis

* Promotion vs Total Sales
* Promotion vs Discount Amount

### Time Series Analysis

* Year-wise Sales Trends
* Region-wise Annual Performance

### Advanced Visualizations

* Correlation Heatmap
* Sales Treemap
* Interactive Plotly Charts
* Stacked Revenue Analysis

---

## Project Structure

```text
Sales-Performance-Analysis/
│
├── data/
│   └── Product-Sales-Region.xlsx
│
├── notebooks/
│   └── sales_performance.ipynb
│
├── images/
│   └── visualizations
│
├── README.md
│
└── requirements.txt
```

---

## Requirements

```text
pandas
numpy
matplotlib
seaborn
plotly
openpyxl
jupyter
```

---

## Business Value

This project helps organizations:

* Identify top-performing products
* Improve regional sales strategies
* Optimize promotional campaigns
* Reduce return-related losses
* Enhance sales team performance
* Support strategic decision-making through data

---

## Future Enhancements

* Sales Forecasting using Machine Learning
* Customer Segmentation
* Interactive Power BI Dashboard
* KPI Monitoring Dashboard
* Profitability Prediction Models

---

## Author

**Nivea K R**

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization

---

⭐ If you found this project useful, consider giving the repository a star on GitHub.

