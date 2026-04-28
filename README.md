# Global Supply Chain & Profitability Analytics (Excel + Power BI)

## 📊 Project Objective
The objective of this project is to analyze global supply chain operations to identify inefficiencies in shipping performance and determine which product categories drive the highest profitability.

---

## 🧱 Data Structure (Excel Data Warehouse)

The dataset was structured using basic data modeling principles (normalization) into three tables:

### 1. Orders_Fact (Transactional Data)
- Order_ID
- Product_ID
- Customer_ID
- Order_Date
- Ship_Date
- Quantity
- Total Revenue (calculated using lookup functions)

### 2. Products_Dim (Product Catalog)
- Product_ID
- Product_Name
- Category
- Unit_Cost
- Unit_Price

### 3. Shipping_Logic
- Order_ID
- Days_to_Ship (calculated using business-day logic)

---

## 🛠 Tools & Skills Used

### Excel
- Data cleaning and structuring
- INDEX-MATCH / XLOOKUP for data retrieval
- Date functions (NETWORKDAYS)
- Basic data modeling (fact and dimension tables)

### Power BI
- Star schema data modeling
- Relationship creation (one-to-many)
- DAX measures:
  - Total Revenue
  - Total Cost
  - Profit Margin %
  - Year-over-Year (YoY) Sales
- Interactive dashboard design

---

## 📈 Key Features

- Revenue and cost analysis by product category
- Profitability insights across products
- Shipping performance tracking (Days to Ship)
- Year-over-Year sales comparison
- Interactive filtering by time and category

---

## 🔍 Key Insights

- The Electronics category generated the highest revenue but had lower profit margins compared to Office Supplies.
- Office Supplies showed approximately 15% higher profitability despite lower sales volume.
- Shipping delays were more frequent in certain product categories, indicating potential supply chain inefficiencies.

---

## 📷 Dashboard Preview


---

## 🚀 What I Learned

- How to structure raw data into a relational format
- Building a star schema for analysis
- Writing DAX measures for business KPIs
- Creating interactive dashboards for decision-making

---

## 📌 Project Files

- Excel Data Warehouse (.xlsx)
- Power BI Dashboard (.pbix)

---
