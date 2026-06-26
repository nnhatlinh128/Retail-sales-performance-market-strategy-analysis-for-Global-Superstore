# 📊 Retail Sales Performance & Market Strategy Analysis for Global Superstore | Power BI

**Author:** Nguyễn Nhật Linh

**Date:** 2025-01

**Tools Used:** Power BI, Power Query, DAX

---

# 📑 Table of Contents

* [📌 Background & Overview](#-background--overview)
* [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)
* [🧠 Design Thinking Process](#-design-thinking-process)
* [⚒️ Dashboard Development Process](#️-dashboard-development-process)
* [📊 Key Insights & Visualizations](#-key-insights--visualizations)
* [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

---

# 📌 Background & Overview

## 📖 What is this project about?

This project analyzes global retail sales data and develops an interactive Power BI dashboard to evaluate business performance across markets, product categories, and customer segments. The dashboard provides strategic insights into sales growth, profitability, customer behavior, and operational risks to support data-driven business decisions.

## 🎯 Project Objectives

The objectives of this project are to:

* ✔️ Monitor overall sales, profit, and business growth.
* ✔️ Compare market performance across different geographic regions.
* ✔️ Evaluate product portfolio profitability and revenue contribution.
* ✔️ Analyze customer acquisition, retention, and return behavior.
* ✔️ Identify operational risks affecting business performance.
* ✔️ Provide strategic recommendations for market expansion and product optimization.

---

## 👤 Who is this project for?

This dashboard is designed for:

* ✔️ Business Executives and Senior Managers to monitor overall business performance.
* ✔️ Regional Managers to compare sales and profitability across markets.
* ✔️ Product Managers to evaluate product portfolio performance.
* ✔️ Business Intelligence Analysts and Data Analysts to support strategic decision-making.
* ✔️ Stakeholders who require executive-level performance reporting.

---

# 📂 Dataset Description & Data Structure

## 📌 Data Source

| Item | Description |
|------|-------------|
| Dataset | Global Superstore Sales Dataset |
| Format | CSV |
| Visualization Tool | Power BI |
| Data Transformation | Power Query |
| Calculation | DAX |

---

## 📊 Dataset Overview

The project utilizes three business tables.

| Table | Description |
|--------|-------------|
| Orders | Sales transaction records |
| Returns | Returned orders information |
| People | Regional manager information |

---

## 📑 Data Dictionary

### Fact Table

* `Orders`

### Dimension Tables

* `Returns`
* `People`

### Main Measures

* Total Sales
* Total Profit
* Profit Margin
* Total Orders
* Return Rate
* Average Order Value (AOV)

### Main Dimensions

* Market
* Country
* Region
* Category
* Sub-Category
* Segment
* Customer Type
* Ship Mode
* Order Date

### Data Dictionary

<img width="489" height="466" alt="Screenshot 2026-05-08 at 01 29 42" src="https://github.com/user-attachments/assets/473943bf-a07f-4d17-be37-04f60d62c9fd" />

<img width="600" height="234" alt="Screenshot 2026-06-26 at 16 52 10" src="https://github.com/user-attachments/assets/0998ebe3-9b03-4ab8-919c-9b08dcf49008" />

---

## 📊 Data Model

The dashboard follows a **Star Schema** design consisting of one fact table and two dimension tables. This structure improves report performance, simplifies DAX calculations, and enables scalable business analysis.

<img width="383" height="217" alt="Data model" src="https://github.com/user-attachments/assets/854917b7-41d0-4ba6-8c5c-1a705c8e60b8" />

---

# 🧠 Design Thinking Process

The dashboard was designed following the Design Thinking methodology to ensure alignment between stakeholder needs and strategic business objectives.

---

## 1️⃣ Empathize

Understand stakeholder challenges.

* Executives need a high-level overview of business growth and profitability.
* Regional managers require market-level performance comparisons.
* Product managers need insights into product profitability and portfolio performance.
* Analysts need an efficient way to identify operational risks and growth opportunities.

<img width="892" height="539" alt="Screenshot 2026-05-08 at 01 31 45" src="https://github.com/user-attachments/assets/dc98e993-98d9-4a83-bced-ebc31865e1ae" />

---

## 2️⃣ Define

Translate business challenges into analytical questions.

Key business questions include:

* Which markets generate the highest sustainable profitability?
* Which product categories contribute most to revenue and profit?
* Which markets should be prioritized for future expansion?
* Which products and regions present higher operational risks?
* How has business performance evolved over time?
* How do customer acquisition and retention differ across markets?

<img width="892" height="367" alt="Screenshot 2026-05-08 at 01 31 54" src="https://github.com/user-attachments/assets/1b6ec2cd-e889-43f0-a440-3157ba5d8001" />

---

## 3️⃣ Ideate

Design an executive dashboard capable of answering strategic business questions from multiple analytical perspectives.

Dashboard pages include:

* Executive Overview
* Market Analysis
* Product Analysis
* Product-Market Database
* Business Insights & Recommendations

<img width="892" height="559" alt="Screenshot 2026-05-08 at 01 32 02" src="https://github.com/user-attachments/assets/22b1972d-2690-42e3-8d3f-185604541e5d" />

---

## 4️⃣ Prototype

<img width="584" height="81" alt="Screenshot 2026-05-08 at 00 25 37" src="https://github.com/user-attachments/assets/f943f9f9-fde7-4229-8819-e1ae3a0673ce" />

---

## 5️⃣ Review

<img width="584" height="25" alt="Screenshot 2026-05-08 at 00 25 44" src="https://github.com/user-attachments/assets/f969f109-d34f-46bf-8717-113fc1589f3d" />

---

# ⚒️ Dashboard Development Process

## 1️⃣ Data Preparation

Power Query was used to clean and transform the raw dataset before visualization.

Main transformation steps:

* Removed duplicate records
* Standardized data types
* Handled missing values
* Renamed columns
* Created date hierarchy
* Built relationships between business tables

---

## 2️⃣ Data Modeling

Implemented a **Star Schema** consisting of:

* 1 Fact Table
* 2 Dimension Tables

Benefits:

* Improved report performance
* Simplified DAX calculations
* Better scalability and maintainability

---

## 3️⃣ DAX Measures

Key business measures include:

* Total Sales
* Total Profit
* Profit Margin
* Total Orders
* Return Rate
* Average Order Value (AOV)
* Profit Growth
* Sales Growth

DAX functions applied:

* `CALCULATE()`
* `SUM()`
* `DIVIDE()`
* `DISTINCTCOUNT()`
* `TOTALYTD()`
* `DATEADD()`

---

## 4️⃣ Dashboard Development

The dashboard was developed with interactive visualizations, including:

* KPI Cards
* Sales & Profit Trend Analysis
* Market Performance Comparison
* Product Portfolio Matrix
* Customer Analysis
* Geographic Performance Analysis
* Risk Monitoring Dashboard
* Drill-through Database
* Interactive Slicers

# 📊 Key Insights & Visualizations

# 🔍 Dashboard Preview

## I. Executive Overview

<img width="865" height="491" alt="Sales - Overview" src="https://github.com/user-attachments/assets/03c43dc6-0b28-4c94-a694-17607e147bf6" />

### 📌 Key Findings

#### 1. Business Performance Grew Strongly

* Total Sales reached **$12.64M**, generating **$1.47M** in Total Profit from **25K orders**.
* Compared with the previous year, Sales, Profit, and Orders increased by more than **50%**, while Profit Margin remained stable at **11.61%**.

→ The business achieved strong growth while maintaining overall profitability.

---

#### 2. Profit Continued to Increase Over Time

* Total Profit increased steadily from **$0.25M (2011)** to **$0.50M (2014)**.
* Profit Growth peaked in **2013** before slowing slightly in 2014.

→ Although profitability continues to improve, growth has begun to stabilize.

---

#### 3. APAC Generates the Largest Revenue

* APAC recorded the highest Total Sales and Total Profit among all markets.
* Canada generated the lowest revenue but achieved the highest Profit Margin.

→ Revenue scale and profitability differ across markets, requiring different business strategies.

---

#### 4. Technology Is the Largest Profit Contributor

* Technology contributed **45.23%** of total profit, followed by Office Supplies (**35.33%**) and Furniture (**19.44%**).

→ Technology remains the company's strongest product category in terms of profitability.

---

#### 5. Return Rate Remains Stable

* Overall Return Rate was **4.68%**, remaining relatively unchanged from the previous year.

→ Business expansion has not significantly increased product return risk.

---

## II. Market Analysis

<img width="862" height="485" alt="Sales - Market" src="https://github.com/user-attachments/assets/efc3fdc4-92c3-4f61-94c5-782a906919f1" />

### 📌 Key Findings

#### 1. Canada Has the Highest Profit Margin

* Canada achieved a Profit Margin of approximately **26.6%**, the highest among all markets despite relatively low sales volume.
* APAC generated the highest revenue but maintained a lower Profit Margin.

→ High-revenue markets are not necessarily the most profitable.

---

#### 2. APAC Leads Order Volume

* APAC processed the largest number of orders, followed closely by LATAM and the US.

→ These markets represent the company's largest customer base and revenue source.

---

#### 3. Customer Mix Differs Across Markets

* Returning customers account for the majority of customers across most markets.
* EMEA and Africa have noticeably higher proportions of new customers compared with other regions.

→ Customer acquisition and retention strategies should be tailored to each market.

---

#### 4. Positive Growth Across All Markets

* Every market achieved positive year-over-year sales growth.
* Growth rates remained consistently strong across regions.

→ Business growth is broadly distributed rather than concentrated in a single market.

---

#### 5. Return Rates Differ Between Markets

* Return Rate varies across markets, with some regions showing consistently higher return levels.

→ Monitoring regional return performance can help identify operational improvement opportunities.

---

## III. Product Analysis

<img width="865" height="491" alt="Sales - Product" src="https://github.com/user-attachments/assets/146c4d26-1dfe-4d92-bd35-f290addec2e3" />

### 📌 Key Findings

#### 1. Phones and Copiers Generate the Highest Revenue

* Phones and Copiers generated the highest Total Sales, followed by Chairs and Bookcases.

→ These products represent the company's primary revenue drivers.

---

#### 2. Product Performance Varies Across Revenue and Profitability

* The Strategic Portfolio Matrix shows that products differ considerably in both revenue contribution and profitability.

→ Product evaluation should consider both financial performance and strategic value.

---

#### 3. Returning Customers Dominate Product Sales

* Returning customers contribute the majority of purchases across nearly every product category.

→ Customer retention plays an important role in sustaining long-term sales.

---

#### 4. Product Demand Differs Across Markets

* Product performance varies substantially between geographic markets.

→ Product strategies should be adapted according to regional customer demand.

---

#### 5. Revenue Is Concentrated in a Small Number of Products

* The Top 10 Products account for a significant proportion of total sales.

→ Prioritizing high-performing products can maximize business impact.

---

## IV. Product–Market Database

<img width="865" height="487" alt="Sales - Database" src="https://github.com/user-attachments/assets/3e0e6e9c-324b-4972-8fab-b78378697d07" />

### 📌 Key Findings

#### 1. Product Performance Can Be Evaluated at Market Level

* The dashboard enables detailed comparison of Sales, Profit, Orders, Profit per Order, and Return Rate across every product-market combination.

→ Product and regional performance can be evaluated simultaneously to support business decisions.

---

#### 2. Profitability Differs Between Products

* Some products generate high sales but relatively low Profit per Order.
* Others generate lower sales while maintaining stronger profitability.

→ Revenue alone is insufficient for evaluating product performance.

---

#### 3. Return Rates Vary Across Product Categories

* Return Rates differ considerably between products and markets.

→ High-return products should be reviewed to identify opportunities for operational improvement.

---

# 🔎 Final Conclusion & Recommendations

| Strategy                           | Key Insight                                                                                                                          | Recommendation                                                                                                                 |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| 🌍 Market Expansion                | APAC generates the highest revenue, while Canada achieves the strongest Profit Margin despite lower sales volume.                    | Expand revenue in high-growth markets while adopting successful profitability practices from high-margin regions.              |
| 📦 Product Portfolio Optimization  | Technology contributes the largest share of total profit, while Phones and Copiers remain the strongest revenue-generating products. | Prioritize investment in high-performing categories and continuously evaluate lower-performing products for optimization.      |
| 👥 Customer Strategy               | Returning customers account for the majority of purchases across products and markets.                                               | Strengthen customer retention programs while tailoring acquisition strategies to regional market characteristics.              |
| ⚙️ Operational Performance         | Profitability and Return Rates vary across markets and product categories.                                                           | Monitor operational KPIs regularly and investigate high-return products or underperforming markets to improve profitability.   |
| 📈 Business Performance Management | Sales, Profit, and Orders have grown consistently while maintaining a stable Profit Margin.                                          | Continue tracking executive KPIs through interactive dashboards to support strategic planning and data-driven decision-making. |
