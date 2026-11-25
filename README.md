
# 📊 RetailPulse – Superstore Sales & Profit Intelligence

### An Interactive Retail Business Intelligence & Analytics Dashboard Using Microsoft Power BI

<p align="center">
  <b>Turning Retail Data into Actionable Business Insights</b>
</p>

---

## 📌 Project Overview

**RetailPulse – Superstore Sales & Profit Intelligence** is an interactive Business Intelligence and Data Analytics project developed using **Microsoft Power BI**.

The project analyzes the Sample Superstore dataset (2014–2017) to understand retail business performance across multiple dimensions, including sales, profitability, customers, products, geographical distribution, discounts, and product returns.

The main objective is to transform raw retail transaction data into meaningful business insights through interactive dashboards, KPI indicators, data visualization, and analytical reporting.

RetailPulse helps business managers and decision-makers identify profitable products, understand customer purchasing patterns, monitor regional performance, evaluate discount strategies, and discover factors affecting overall profitability.

The project demonstrates practical applications of data analysis, business intelligence, data modeling, DAX calculations, KPI development, and interactive dashboard design.

---

## 🎯 Project Objectives

- Analyze overall sales, profit, and business performance.
- Understand product portfolio distribution across categories and sub-categories.
- Analyze customer distribution by segment and geographical location.
- Identify top-performing states and cities based on sales.
- Evaluate profitability across different regions and product categories.
- Monitor yearly sales and profit growth.
- Analyze product returns and their impact on sales.
- Compare actual sales against predefined annual sales targets.
- Identify the impact of discounts on profit margins.
- Generate actionable business recommendations using data-driven insights.

---

## 🛠️ Technologies & Tools Used

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Interactive dashboard development and data visualization |
| Power Query | Data preparation and transformation |
| DAX | Calculated measures, KPIs, and business metrics |
| Microsoft Excel | Dataset storage and source data |
| Git & GitHub | Project version control and documentation |

---

## 📂 Dataset Description

The project uses the **Sample Superstore Dataset**, containing retail transaction information from 2014 to 2017.

The original Excel workbook contains three worksheets:

### 1. Orders
Contains 9,994 records and 21 columns.

Important attributes include:

- Row ID
- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Postal Code
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

### 2. Returns

Contains information about returned orders, including:

- Returned status
- Order ID

### 3. People

Contains regional management information:

- Regional Manager
- Region

### Dataset Summary

| Attribute | Value |
|---|---|
| Dataset | Sample Superstore |
| Time Period | 2014–2017 |
| Order Records | 9,994 |
| Unique Orders | 5,009 |
| Unique Customers | 793 |
| Unique Products | 1,862 |
| Product Categories | 3 |
| Product Sub-Categories | 17 |
| Returned Order IDs | 296 |
| Geography | United States |

---

## ⚙️ Project Development Workflow

The project was developed through the following analytical workflow:

### Step 1: Data Collection and Import

- Collected the Sample Superstore Excel dataset.
- Imported the workbook into Microsoft Power BI Desktop.
- Loaded the Orders, Returns, and People worksheets for analysis.

### Step 2: Data Preparation

- Reviewed the dataset structure and columns.
- Examined data types and numerical fields.
- Prepared order dates, sales, profit, discount, and quantity fields for analysis.
- Organized the source tables for business reporting.

### Step 3: Data Modeling

- Organized the imported tables for analytical reporting.
- Used order-related information to connect sales and returns analysis.
- Prepared relationships to support regional and business-level analysis.

### Step 4: DAX and KPI Development

Used Power BI calculations and business metrics to analyze:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Products
- Profit Margin
- Return Rate
- Successful Order Percentage
- Yearly Sales Growth
- Yearly Profit Growth
- Sales Target Performance

### Step 5: Dashboard Development

Developed interactive report pages containing KPI cards, charts, tables, geographical analysis, filters, and slicers.

### Step 6: Business Insights

Interpreted the dashboard results to identify sales trends, profitability issues, discount-related losses, and opportunities for business improvement.

---

## 📊 Dashboard Modules & Analysis

### 1. Product Portfolio Analysis

**Business Question:** How broad is the product range, and which categories contain the most products?

Analysis includes:

- Total unique products.
- Product count by category.
- Product count by sub-category.
- Product details table.
- Category and sub-category slicers.

**Key Insights:**
- 1,862 unique products.
- 3 product categories.
- 17 product sub-categories.
- Office Supplies has the largest portfolio with 1,083 products.

### 2. Customer Base Analysis

**Business Question:** Who are our customers, and how widely are they distributed geographically?

Analysis includes:

- Total unique customers.
- Customer distribution by segment.
- Country, state, and city analysis.
- Postal code distribution.
- Customer details table.

**Key Insights:**
- 793 unique customers.
- Consumer is the largest segment with 409 customers.
- Corporate has 236 customers.
- Home Office has 148 customers.
- Customers are distributed across 41 states and 252 cities in the customer table.

### 3. Sales Performance Analysis

**Business Question:** How much revenue does the business generate, and how do sales change over time?

Analysis includes:

- Total sales KPI.
- Yearly sales performance.
- Sales by customer segment.
- Category-based sales analysis.
- Top five states by sales.
- Top five cities by sales.

**Key Insights:**
- Total sales are approximately $2.30 million.
- 2017 sales reached approximately $0.73 million.
- Sales increased by approximately 51% between 2014 and 2017.
- Consumer contributes approximately 51% of total sales.

### 4. Profit Analysis

**Business Question:** How much profit does the business generate, and which locations contribute the most?

Analysis includes:

- Total profit KPI.
- Profit by state.
- Profit by city.
- Profit by customer segment.
- Category-based profitability.

**Key Insights:**
- Total profit is approximately $286.4K.
- Overall profit margin is approximately 12.5%.
- California and New York are leading profit-generating states.
- New York City is the leading city by profit.

### 5. Profit by Year and Customer Segment

**Business Question:** Is profitability increasing each year, and which customer segment generates the highest profit?

Analysis includes:

- Yearly profit comparison.
- Profit trend visualization.
- Profit by customer segment.
- Trend line analysis.

**Key Insights:**
- Profit increased from approximately $49.5K in 2014 to $93.4K in 2017.
- Profit grew approximately 89% over the period.
- Consumer generates the highest profit, followed by Corporate and Home Office.

### 6. Sales and Profit Trend Analysis

**Business Question:** Are sales and profit growing consistently over time?

Analysis includes:

- Yearly sales trends.
- Yearly profit trends.
- Trend line visualization.
- Category and sub-category slicers.
- Profit margin analysis.

**Key Insights:**
- Sales declined approximately 2.8% in 2015.
- Sales increased approximately 29% in 2016.
- Sales increased approximately 20% in 2017.
- Profit increased every year.
- Profit margin improved from approximately 10.2% to 12.7%.

### 7. Returns Analysis

**Business Question:** What percentage of orders are returned, and how healthy is order fulfillment?

Analysis includes:

- Total order lines.
- Returned orders.
- Successful orders.
- Return percentage.
- Successful order percentage.
- Returned sales value analysis.

**Key Insights:**
- 296 returned Order IDs.
- Return rate is approximately 2.96%.
- Successful order percentage is approximately 97.04%.
- Returned orders correspond to approximately 800 order lines worth $180.5K in sales.

### 8. Sales vs Target Analysis

**Business Question:** Did the business achieve its annual sales target?

Analysis includes:

- Actual sales KPI.
- Annual sales target.
- Sales variance.
- Target achievement comparison.
- Year slicer for annual performance monitoring.

**Key Insights:**
- 2014 actual sales were approximately $484.25K.
- The sales target was $500K.
- The business missed its target by approximately 3.15%.
- The sales shortfall was approximately $15.8K.

---

## 📈 Advanced Business Insights

The analysis identifies several important business opportunities.

### 1. Furniture Profitability Challenge

- Furniture profit margin is approximately 2.5%.
- Office Supplies profit margin is approximately 17.0%.
- Technology profit margin is approximately 17.4%.
- Tables and Bookcases are major loss-making sub-categories.

**Recommendation:** Review Furniture pricing, supplier costs, and discount strategies.

### 2. Discount Impact on Profitability

The analysis shows a strong relationship between higher discounts and declining profit margins.

| Discount Band | Profit Margin |
|---|---:|
| No Discount | 29.5% |
| Up to 10% | 16.6% |
| 10–20% | 11.6% |
| 20–30% | -10.0% |
| 30–50% | -24.8% |
| Over 50% | -119.2% |

**Recommendation:** Introduce stricter discount policies and evaluate discounts above 20%.

### 3. Loss-Making Sub-Categories

The analysis identifies three major loss-making sub-categories:

- Tables: -$17.7K
- Bookcases: -$3.5K
- Supplies: -$1.2K

**Recommendation:** Reconsider pricing, purchasing costs, and promotional strategies for these products.

### 4. Regional Profitability

Several states generate negative profit:

- Texas: -$25.7K
- Ohio: -$17.0K
- Pennsylvania: -$15.6K
- Illinois: -$12.6K

**Recommendation:** Investigate regional discounting, product mix, and operating performance.

### 5. High-Margin Product Opportunities

Some sub-categories generate attractive profit margins:

- Copiers: 37%
- Paper: 43%
- Labels: 44%
- Envelopes: 42%

**Recommendation:** Focus on promoting high-margin products through strategic marketing and product bundling.

### 6. Returns Monitoring

Although the return rate is approximately 2.96% by returned Order IDs, returned order lines account for approximately $180.5K in sales.

**Recommendation:** Monitor returns by sales value instead of relying only on return counts.

---

## 📁 Repository Structure

```text
Retail-Pulse-Superstore-Sales-Profit-Intelligence/
│
├── Analysis/
│   └── Analytical project materials
│
├── clean_data/
│   └── Prepared dataset files
│
├── raw_data/
│   └── Original source dataset
│
├── result/
│   └── Project outputs and results
│
└── README.md
```

---

## 💡 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Sales | $2.30M |
| Total Profit | $286.4K |
| Profit Margin | 12.5% |
| Unique Customers | 793 |
| Unique Products | 1,862 |
| Unique Orders | 5,009 |
| Returned Order IDs | 296 |
| Return Rate | 2.96% |

*Values are approximate and based on the project analysis.*

---

## 🚀 Key Features

- Interactive Power BI dashboards.
- Dynamic KPI cards and performance indicators.
- Product and customer segmentation.
- Sales and profitability analysis.
- Geographical performance visualization.
- Yearly sales and profit trend analysis.
- Discount impact analysis.
- Return rate monitoring.
- Sales target comparison.
- Business recommendations based on analytical findings.

---

## 📚 Skills Demonstrated

Through this project, the following technical and analytical skills are demonstrated:

- Business Intelligence
- Data Analytics
- Microsoft Power BI
- Power Query
- DAX Calculations
- Data Preparation
- Data Modeling
- KPI Development
- Data Visualization
- Business Performance Analysis
- Retail Analytics
- Analytical Reporting
- Data-Driven Decision Making

---

## 🔮 Future Enhancements

Potential improvements for future versions include:

- Adding advanced time-intelligence calculations.
- Developing more detailed customer profitability analysis.
- Creating interactive drill-through reports.
- Adding advanced geographical visualizations.
- Developing automated data refresh workflows.
- Introducing forecasting and predictive analytics.
- Improving dashboard navigation and user experience.

---

## 🏁 Conclusion

RetailPulse – Superstore Sales & Profit Intelligence demonstrates how Microsoft Power BI can transform raw retail transaction data into meaningful business insights.

By analyzing sales, profit, customers, products, geographical performance, discounts, and returns, the project provides a comprehensive understanding of retail business performance.

The findings highlight opportunities to improve profitability, optimize discount strategies, strengthen product performance, monitor regional losses, and make better business decisions.

This project represents a practical application of Business Intelligence and Data Analytics in the retail industry.

---

## 👩‍💻 Author

**Disha Singh**

GitHub: [@singh06disha-cmd](https://github.com/singh06disha-cmd)

Project Repository: [RetailPulse – Superstore Sales & Profit Intelligence](https://github.com/singh06disha-cmd/Retail-Pulse-Superstore-Sales-Profit-Intelligence)

---

<p align="center">
  <b>⭐ If you find this project useful, consider giving this repository a star!</b>
</p>
