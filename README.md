# 🏪 US Sales Performance Analytics (2018–2020)

📌 **An end-to-end Power BI project analyzing U.S. retail sales performance across regions, warehouses, stores, and sales teams, transforming transactional data into actionable business insights through interactive dashboards and advanced DAX analytics.**

---

# 📊 Project Overview

This project analyzes **U.S. retail sales data between 2018 and 2020** to evaluate business performance across multiple operational dimensions, including sales channels, warehouse operations, geographic markets, and sales team effectiveness.

The dashboard follows a **top-down analytical approach**, allowing stakeholders to begin with high-level KPIs before drilling into warehouse operations, geographic performance, and sales team effectiveness.

The goal is to uncover performance trends, identify operational inefficiencies, discover underserved markets, and support data-driven business decisions.

---

# ✨ Project Highlights

- Built an interactive **4-page Power BI dashboard** for executive reporting and operational analysis.
- Designed a **star schema** with one fact table and four dimension tables.
- Developed **30+ DAX measures** for KPIs, Year-over-Year analysis, rankings, and dynamic reporting.
- Implemented interactive slicers, tooltips, conditional formatting, and dynamic KPI cards.
- Applied data storytelling principles to guide users from executive insights to detailed operational analysis.

---

# 🌎 Why This Project Matters

Retail organizations generate vast amounts of transactional data, but turning that information into meaningful business decisions requires effective analytics.

This project demonstrates how Power BI can consolidate operational data into an interactive decision-support dashboard that enables executives and managers to monitor performance, identify growth opportunities, optimize warehouse operations, and improve sales effectiveness.

---

# 🎯 Business Objectives

This dashboard answers key business questions such as:

- Which regions and states generate the highest revenue?
- Which warehouses are underperforming?
- How has sales performance changed over time?
- Which sales channels perform best?
- Which sales representatives generate the most revenue?
- Which geographic markets present opportunities for expansion?

---

# 📁 Dataset

**Source:** Data Analysis Course Project (SQL Database)

The dataset consists of **7,991 sales transactions** stored across **five related tables**.

### Tables

- Fact Sales Order
- Dim Date
- Dim Region
- Dim Sales Store
- Dim Sales Team

### Primary Business Entities

- Orders
- Sales Channels
- Warehouses
- Sales Teams
- Customers
- Stores
- Products
- States
- Regions
- Household Income

---

# 🧹 Data Preparation

The data was previously cleaned and transformed in SQL before being imported into Power BI.

Preparation steps included:

- Imported cleaned tables from SQL Server
- Verified data types
- Created a dedicated Date dimension
- Established table relationships
- Configured the star schema
- Optimized the model for reporting
- Developed business measures using DAX

---

# 🧠 Data Model

A **Star Schema** was implemented to improve performance, simplify relationships, and support efficient DAX calculations.

### Fact Table

- Fact Sales Order

### Dimension Tables

- Dim Date
- Dim Region
- Dim Sales Store
- Dim Sales Team

The model uses **one-to-many relationships** between the fact table and each dimension table, creating an efficient and scalable reporting model.

---

# 📈 Key Metrics

### Core KPIs

- Revenue
- Profit
- Profit Margin
- Total Orders
- Order Quantity
- Average Order Value

### Comparative KPIs

- Previous Year Revenue
- Previous Year Profit
- Previous Year Profit Margin
- Previous Year Orders
- Previous Year Quantity
- Previous Year Average Order Value

### Year-over-Year Metrics

- Revenue YoY %
- Profit YoY %
- Profit Margin YoY %
- Orders YoY %
- Quantity YoY %
- Average Order Value YoY %

### Ranking Metrics

- Warehouse Revenue Rank
- Sales Team Revenue Rank
- Highest Revenue
- Highest Profit Margin
- Highest Order Volume

### Supporting Metrics

- Revenue per Store
- Average Discount
- Total Discount Given
- Total Products
- Total Stores
- Number of Team Members

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview

### Purpose

Provide an executive summary of overall business performance.

### Visuals

- KPI Cards
- Monthly Revenue Trend
- Revenue & Profit by Sales Channel
- Interactive Slicers

### Business Questions Answered

- How has overall business performance changed?
- Which sales channel generates the most revenue?
- Which months perform best?

---

## 2️⃣ Operations Analysis

### Purpose

Evaluate warehouse efficiency and store performance.

### Visuals

- Warehouse Efficiency Scatter Plot
- Warehouse Performance Table
- Top Stores by Revenue
- Interactive Slicers

### Business Questions Answered

- Which warehouses perform best?
- Which stores generate the highest revenue?
- How efficiently are warehouses operating?

---

## 3️⃣ Geography Analysis

### Purpose

Analyze regional performance and identify underserved markets.

### Visuals

- Revenue by State Map
- Revenue vs Household Income Scatter Plot
- Revenue Distribution by Region
- Interactive Slicers

### Business Questions Answered

- Which regions generate the highest revenue?
- Are high-income markets fully captured?
- Where should future expansion occur?

---

## 4️⃣ Sales Team Analysis

### Purpose

Evaluate sales representative performance.

### Visuals

- Revenue vs Average Discount Scatter Plot
- Sales Performance Table
- Top Performer KPI Cards
- Interactive Slicers

### Business Questions Answered

- Which sales representatives perform best?
- Does discounting improve sales?
- Which team members require additional coaching?

---

# 🔍 Key Insights

## Executive Performance

- Revenue increased to **$28.19M (+1.2%)**, while profit increased to **$8.20M (+0.2%)**, indicating stable profitability.
- Order volume increased by **3.1%**, while Average Order Value declined slightly, suggesting customers placed more frequent but lower-value orders.
- The **In-Store** sales channel generated over **$39M** in revenue, significantly outperforming Online, Distributor, and Wholesale channels.
- Revenue shows strong seasonality, peaking in **November**.

## Warehouse Performance

- **WARE-NMK1003** generated the highest overall revenue due to servicing the largest number of stores.
- **WARE-NBV1002** achieved the highest revenue per store, demonstrating exceptional operational efficiency.
- Warehouse performance depends on operational efficiency, not just the number of stores served.

## Geographic Performance

- The **West Region** contributes the highest share of revenue, with **California** leading all states.
- Higher household income generally aligns with stronger sales performance, although several high-income states remain underserved.
- Revenue is concentrated within relatively few states, highlighting opportunities for market expansion.

## Sales Team Performance

- Higher discounts do not consistently generate higher revenue.
- Top-performing representatives maintain strong revenue while offering moderate discounts.
- **Donald Reynolds** generated the highest revenue.
- **Patrick Graham** recorded the highest profit margin.
- **Todd Roberts** processed the highest order volume.

---

# 💼 Business Impact

This dashboard enables management to:

- Monitor sales performance across multiple business levels.
- Identify high-performing and underperforming regions.
- Evaluate warehouse operational efficiency.
- Measure sales channel effectiveness.
- Discover underserved markets.
- Track Year-over-Year business performance.
- Support strategic decision-making with interactive analytics.

---

# 💡 Business Recommendations

- Increase marketing investment in underperforming Northeast markets.
- Expand the store network serviced by **WARE-NBV1002** due to its operational efficiency.
- Investigate lower-performing warehouses to identify improvement opportunities.
- Continue prioritizing the In-Store sales channel while strengthening Online and Distributor channels.
- Encourage top-performing sales representatives to mentor lower-performing colleagues.
- Avoid excessive discounting, as moderate discounts achieve stronger profitability.
- Target high-income, low-revenue states with localized expansion strategies.
- Consider household income alongside sales performance when selecting future store locations.

---

# 🛠 Tools & Technologies

### Tools

- Power BI Desktop
- Power Query
- DAX
- MySQL

### Skills Demonstrated

- Data Cleaning
- Data Modeling
- Star Schema Design
- DAX Calculations
- KPI Development
- Business Intelligence
- Data Visualization
- Dashboard Design
- Data Storytelling

---

# 📷 Dashboard Preview

## Executive Overview

![Executive Overview](images/overview.png)

---

## Operations Analysis

![Operations](images/operations.png)

---

## Geography Analysis

![Geography](images/geography.png)

---

## Sales Team Analysis

![Sales Team](images/sales-team.png)

---

# 🚀 How to Use

1. Download the **.pbix** file from this repository.
2. Open the report in **Power BI Desktop**.
3. Filter the report using the slicers for:
   - Year
   - Region
   - Sales Channel
4. Navigate between pages using the report navigation buttons.
5. Hover over visuals to view additional tooltips.
6. Click charts to cross-filter related visuals for deeper analysis.

---

# 📚 What I Learned

This project strengthened my ability to:

- Build advanced DAX measures using time intelligence.
- Develop dynamic KPI reporting with Year-over-Year comparisons.
- Design dashboards using structured storytelling principles.
- Create intuitive report layouts through wireframing.
- Select visuals that effectively communicate operational relationships.

---

# 💡 Future Improvements

Future enhancements could include:

- Sales Forecasting
- Customer Segmentation
- RFM Analysis
- Market Basket Analysis
- Inventory Analytics
- Geographic Heat Maps
- Power BI Service Deployment
- Automated Data Refresh
- Row-Level Security (RLS)

---

# 📂 Repository Contents

```
📦 US Sales Performance Analytics
│
├── 📄 README.md
├── 📊 US Sales Performance Analytics.pbix
├── 📁 Dataset
├── 📁 Images
│   ├── overview.png
│   ├── operations.png
│   ├── geography.png
│   └── sales-team.png
└── 📄 LICENSE
```

---

# 👤 Author

**Andrew Udokang**

**Data Analyst | Power BI | SQL | Excel | Python**

- **LinkedIn:** https://www.linkedin.com/in/andrewudokang
- **GitHub:** https://github.com/andrewudokang

---

⭐ If you found this project helpful or interesting, consider giving it a **star** and feel free to connect with me on LinkedIn!
