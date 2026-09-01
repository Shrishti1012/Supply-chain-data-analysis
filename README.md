# 🚚 Supply Chain Analytics – Data-Driven Business Optimization

## 📌 Project Overview

This project focuses on analyzing supply chain data to identify key operational challenges and provide data-driven business solutions.

The analysis covers major supply chain areas, including:

- Delivery delays
- Inventory imbalance
- Demand forecasting
- Backorders and stockout risk
- Operational costs
- Profit and loss

The project follows an end-to-end data analytics workflow, starting from understanding business requirements and raw data to performing analysis and presenting actionable insights through a Power BI dashboard.

---

## 🎯 Business Problem

The company was facing several end-to-end supply chain inefficiencies, including:

- Delayed deliveries
- Inventory imbalance
- Poor demand forecasting
- High operational costs
- Business losses

The goal of this project was to identify the root causes of these problems through data analysis and provide practical, data-driven recommendations.

---

## 🎯 Project Objectives

### 1. Minimize Delivery Delays

Analyze shipping times across warehouses and locations to identify areas with slower delivery performance.

### 2. Enhance Inventory Management

Identify overstocked and understocked warehouses and analyze backorders to improve inventory distribution.

### 3. Improve Demand Forecasting

Analyze demand forecasts, backorders, and stockout risks to identify forecasting gaps.

### 4. Maximize Profit Margins

Analyze sales and different cost components to identify the major drivers of business losses.

---

## 🛠️ Tools & Technologies Used

### 🐍 Python

- Data cleaning
- Data validation
- Exploratory Data Analysis (EDA)
- Identifying patterns and inconsistencies in the data

### 🗄️ SQL (MySQL)

- Objective-wise business analysis
- Data aggregation and filtering
- Warehouse and location-level analysis
- Creating analytical views

### 📊 Power BI

- Data visualization
- Dashboard development
- Presenting key business insights

---

## 📊 Dataset Overview

The dataset contains **500 records** and includes supply chain-related information such as:

- Warehouse ID
- Location
- Supplier ID
- Product category
- Current stock
- Demand forecast
- Lead time
- Shipping time
- Stockout risk
- Operational cost
- Monthly sales
- Order processing time
- Return rate
- Customer rating
- Warehouse capacity
- Storage cost
- Transportation cost
- Backorder quantity
- Damaged goods
- Employee count
- Stock difference
- Forecast accuracy
- Profit/Loss

---

# 🔍 Key Insights

## 🚚 Delivery Performance

- The average shipping time was approximately **3.95 days**.
- The maximum shipping time was **7 days**.
- Around **25% of warehouses** took up to 7 days for delivery.
- Locations such as Denver, New York, Miami, Chicago, and San Francisco showed higher average shipping times.

### 💡 Recommendation

Optimize delivery routes, improve logistics planning region-wise, and prioritize slow-performing warehouses.

---

## 📦 Inventory Management

- **218 warehouses** were identified as overstocked.
- **259 warehouses** were identified as understocked.
- **25% of warehouses** had more than 224 backorders.
- Miami and Atlanta were identified as the most understocked locations.

### 💡 Recommendation

Redistribute excess inventory from overstocked warehouses to understocked locations and use backorder quantity as an early indicator for inventory rebalancing.

---

## 📈 Demand Forecasting

- Demand forecasts showed high variation, indicating inconsistencies in forecasting.
- Warehouses with higher stockout risk also showed higher average backorders.
- Dallas, Los Angeles, Denver, and Miami had high average backorders.
- The Denver–Groceries combination showed the highest backorders.

### 💡 Recommendation

Implement location-level and product-level demand forecasting and continuously validate forecasts using backorders and stockout risk.

---

## 💰 Profitability Analysis

- The company was operating at a net loss of approximately **39.41M**.
- Los Angeles, Miami, and Seattle were among the highest loss-making locations.
- Apparel and Automotive were among the most loss-making product categories.
- Some high-revenue products were still generating losses, indicating that profitability issues were primarily cost-driven.

### 💡 Recommendation

Reduce operational, storage, and transportation costs while tracking profitability at the product-location level.

---

# 🔄 Project Workflow

Business Requirements

↓  

Raw Data Collection

↓  

Data Cleaning & Validation using Python

↓  

Exploratory Data Analysis

↓  

SQL-Based Business Analysis

↓  

Power BI Dashboard Development

↓  

Business Insights & Recommendations

---

# 📁 Repository Structure

- `Business_Requirements.pdf`  
  Original business requirements and project objectives.

- `Supply_Chain_Analytics_Presentation.pdf`  
  Final project presentation containing insights and recommendations.

- `Supply_Chain_EDA.ipynb`  
  Python-based data cleaning and exploratory data analysis.

- `Supply_Chain_SQL_Analysis.sql`  
  SQL queries for objective-wise business analysis.

- `Supply_Chain_Raw_Data.csv`  
  Raw supply chain dataset used for analysis.

- `Supply_Chain_Dashboard.pbix`  
  Interactive Power BI dashboard.

- `README.md`  
  Project documentation and overview.

---

# 💡 Business Recommendations

Based on the analysis, the following recommendations were proposed:

- Optimize delivery routes and focus on slow-performing warehouses.
- Redistribute inventory from overstocked to understocked warehouses.
- Prioritize inventory replenishment in high-shortage locations.
- Use backorder quantity and stockout risk as early warning indicators.
- Implement product-level and location-level demand forecasting.
- Reduce unnecessary operational and storage costs.
- Optimize transportation routes and vendors.
- Track profitability at the product-location level.

---

# 📌 Project Deliverables

This repository includes:

- Business requirements document
- Raw dataset
- Python EDA notebook
- SQL analysis
- Power BI dashboard
- Final project presentation

---

## 👩‍💻 Author

**Shrishti Ghildiyal**

Aspiring Data Analyst

**Skills:** Python | SQL | Power BI | Data Analysis | Data Visualization
