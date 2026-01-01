# Sales & Customer Performance Dashboard (Power BI)

## Project Overview
This project analyzes **sales, product, customer, and regional performance** using the Classic Models dataset.  
The objective is to deliver **executive-level insights** through interactive Power BI dashboards focusing on revenue, profitability, customer concentration, and sales rep performance.

The dashboard is designed for **business decision-makers** to quickly identify top-performing products, customers, regions, and potential risk areas.

---

## Dataset Description
The project uses the **Classic Models** relational dataset consisting of the following tables:

- **customers** – customer details, country, sales rep  
- **orders** – order dates and order metadata  
- **order_details** – product-level sales, quantity, profit  
- **products** – product information and product lines  
- **productlines** – product line categorization  
- **employees** – sales representatives  
- **offices** – office locations  
- **payments** – customer payments  
- **Date (Custom Calendar Table)** – year, month, month number for time analysis  

All tables are connected using a **star schema** for optimal performance.

---

## Key Metrics (KPIs)
- Total Revenue  
- Total Profit  
- Profit Margin %  
- Total Orders  
- Total Customers  
- Average Order Value  
- YoY Growth %  
- Top Selling Product  
- Top Customer  

---

## Dashboard Pages & Insights

### 1. Overview
**Purpose:** High-level business snapshot

**Insights:**
- Revenue and profit are heavily driven by Classic Cars
- Sales peak in specific months, indicating seasonal demand
- Growth is strong YoY but depends on a limited set of products and regions

---

### 2. Product & Sales Analysis
**Purpose:** Product performance and profitability

**Insights:**
- Classic Cars dominate revenue and profit
- Vintage Cars generate strong margins despite lower volume
- Sales are concentrated in a few top products
- Product lines like Trains and Ships show consistently low demand
  
**Features:**
- Tooltips showing top products per product line
- Quantity sold vs profit analysis
- Revenue contribution breakdown

---

### 3.Customer & Regional Analysis
**Purpose:** Customer dependency and regional reach
**Insights:**
- USA holds the largest customer base
- Euro+ Shopping Channel is the top customer by orders
- Top customers contribute a disproportionate share of revenue
- Sales rep performance varies significantly
**Features:**
- Top customers by orders
- Revenue by sales representatives
- Country-wise customer distribution
- Interactive filters for country and employee

---

## Key DAX Measures
- Total Sales  
- Total Profit  
- Profit Margin %  
- YoY Growth %  
- Average Order Value  
- Top Customer  
- Top Selling Product  

DAX measures are optimized using **context-aware calculations** without creating unnecessary physical tables.

---

## Tools & Technologies
- **Power BI Desktop**
- **DAX**
- **Data Modeling (Star Schema)**
- **Power Query**
- **Interactive Tooltips & Slicers**

---

## Business Value
- Identifies revenue concentration risk
- Highlights high-margin product lines
- Helps prioritize key customers and regions
- Supports data-driven sales and marketing decisions

---

## Conclusion
This project demonstrates the ability to:
- Build clean data models  
- Write efficient DAX measures  
- Design executive-friendly dashboards  
- Translate raw data into **actionable business insights**

---

## Author
**Payal**  
MCA | Data Analytics & Power BI  
