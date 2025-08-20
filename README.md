# Executive Sales Overview Dashboard

## Introduction
This project provides an executive-level sales summary designed in **Power BI** using a public sample dataset.  
The dashboard consolidates sales metrics across categories, reseller business types, channels, and geographies.  
It is intended for decision-makers who need to quickly identify performance drivers, risks, and opportunities.

---

## Dataset
- **Source**: Public sample e-commerce dataset (non-confidential)  
- **Period**: July 2017 – June 2021  
- **Scope**: Products, sales orders, categories, reseller business types, channels, and customer details  

---

## Objectives
- Provide executives with a high-level snapshot of sales KPIs  
- Analyze sales distribution across categories, business types, and channels  
- Identify top-performing and underperforming regions  
- Detect over-reliance on specific product lines or markets  

---

## Dashboard Features and Graph Analysis

### 1. KPI Tiles
- **Products**: 295  
- **Orders**: 31.46K  
- **Channels**: 2  
- **Unit Price**: $56.40M  
- **Customers**: 18.49K  
- These KPIs provide a quick operational summary, showing business scale and reach.

### 2. Waterfall Chart – Sales by Category and Business Type
- Shows incremental contributions of reseller business types to overall sales.  
- **Specialty Bike Shops and Value Added Resellers** drive the largest increases.  
- Other reseller types contribute little, with some appearing flat.  
- **Business implication**: Reliance on a few key business types suggests a need to diversify partnerships.

### 3. Tables – Unit Price by Category and Country
- **By Category**: Bikes dominate ($21.9M), followed by Components. Clothing and Accessories remain marginal.  
- **By Country**: The U.S. leads ($18.03M), followed by Canada and the U.K. Smaller markets such as Germany and Australia lag behind.  
- **Insight**: Both category and geography show concentration risk.

### 4. Sankey Diagram – Sales by Order Quantity and Business Type
- Visualizes how orders flow across business types.  
- **Warehouses handle 52% of orders**, **Value Added Resellers 37%**, while **Specialty Bike Shops** capture 10%.  
- **Business implication**: Heavy dependency on Warehouses may limit flexibility in distribution strategy.

### 5. Sales Amount by Category and Channel
- Line chart showing category contributions through reseller channels.  
- **Bikes dominate** while other categories decline sharply.  
- **Business implication**: A product portfolio that leans heavily on one category poses strategic risk.

### 6. Sales Amount by Country
- Compares sales distribution across regions.  
- The **United States** accounts for the bulk of revenue, followed by Canada and France.  
- Germany and Australia contribute little.  
- **Business implication**: Growth opportunities exist in underdeveloped regions.

---

## Results
- **Over-reliance on Bikes (64% share)** exposes the company to product risk.  
- **Warehouses (52% of orders)** dominate distribution, limiting resilience.  
- **U.S. and Canada** drive the majority of sales, highlighting geographic imbalance.  
- Clothing and Accessories are underperforming categories that could be targeted for growth initiatives.  

---

## Real-World Application
This type of executive sales dashboard is widely used in:  
- **Retail and E-commerce**: Monitoring product category sales and reseller contributions  
- **Wholesale and Distribution**: Understanding order flows across business partners  
- **Consumer Goods and Manufacturing**: Balancing product portfolios and planning market expansion  

**Example Business Problem Solved:**  
A consumer goods company notices flat revenue growth despite strong bike sales. Using this dashboard, executives can:  
- See that **other categories (Clothing, Accessories)** are not contributing significantly  
- Recognize **dependence on U.S. and warehouse channels**  
- Make informed decisions to diversify categories, strengthen underperforming regions, and expand distribution beyond warehouses  

---

## File Structure
/dashboard-overview-executive-sales
├── executive_sales_overview.png # Dashboard screenshot
└── README.md # Project documentation



---

## Preview
[Executive Sales Overview]
<img width="2355" height="1184" alt="Sales report" src="https://github.com/user-attachments/assets/5ad78121-f30f-4f7a-85bc-7e5ff461dfe6" />
