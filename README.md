# 📊 Regional Sales Analysis

## 🧩 Problem Statement
Sales teams often lack a clear, data-driven understanding of regional performance, making it difficult to identify growth opportunities and optimize resources.  
This project aims to analyze and visualize regional sales data to uncover trends, evaluate profitability, and support strategic decision-making.

---

## 💼 Business Challenge
**Issues Identified:**
- Inconsistent revenue and profit performance across U.S. regions  
- Lack of visibility into seasonal swings, top SKUs, and channel profitability  

**Goal:**  
Leverage 5 years of historical data to pinpoint growth levers and optimize sales strategy.

---


## ⚙️ Project Workflow
1. Data cleaning and preprocessing in **Python**  
2. Exploratory data analysis (EDA) and transformation  
3. Creation of **interactive Power BI dashboards**  
4. Visualization of regional trends, profitability, and SKU performance  
5. Strategic recommendations derived from insights

---
## 📖 What’s Inside
This repository includes a PDF version of the Power BI report hosted on the Power BI Service. Use the link below for a quick preview.

[Dashboard As PDF](https://github.com/anushka28mishra/regional-sales-analysis-python-powerbi-eda/blob/9876a4df0011948d0a65460e1ef92315e4629c73/Regional%20Sales%20Analysis%20dashboard.pdf)

---

## 🧰 Tech Stack
| Category | Tools Used |
|-----------|-------------|
| **Data Visualization** | Power BI |
| **Data Analysis** | Power BI, Python |
| **Development Tools** | Jupyter Notebook, Power BI Desktop, Power BI Service, Canva |

---
## 🧾 Regional Sales Dataset

This dataset contains detailed regional sales information, including order details, customers, products, and sales performance across different regions. It can be used for sales analytics, forecasting, and business intelligence applications.

### 📊 Dataset Overview

- **File Name:** `Regional Sales Dataset.xlsx`  
- **Total Rows:** 64,104  
- **Total Columns:** 12  
- **Sheets Included:**  
  - `Sales Orders` (main dataset)  
  - `Customers`  
  - `Regions`  
  - `State Regions`  
  - `Products`  
  - `2017 Budgets`

### 🧩 Main Sheet: `Sales Orders`

| Column Name | Description | Example |
|--------------|-------------|----------|
| `OrderNumber` | Unique identifier for each sales order | 20170123 |
| `OrderDate` | Date when the order was placed | 2017-03-15 |
| `Customer Name Index` | Reference ID for the customer placing the order | CUST-032 |
| `Channel` | Sales channel used (e.g., Online, Retail, Wholesale) | Online |
| `Currency Code` | ISO currency code for transaction | USD |
| `Warehouse Code` | Identifier for warehouse fulfilling the order | WH-001 |
| `Delivery Region Index` | Reference ID for delivery region | REG-02 |
| `Product Description Index` | Reference ID for product details | PROD-054 |
| `Order Quantity` | Quantity of product units ordered | 15 |
| `Unit Price` | Price per unit of product | 19.99 |
| `Line Total` | Total sales amount for the line item | 299.85 |
| `Total Unit Cost` | Total cost incurred for the line item | 210.00 |

### 📁 Related Sheets

- **`Customers`** — Contains customer details and identifiers.  
- **`Regions`** — Defines geographic sales regions.  
- **`State Regions`** — Maps states to their respective regions.  
- **`Products`** — Product catalog with descriptions and IDs.  
- **`2017 Budgets`** — Budget allocations for 2017 sales.

### 💡 Usage

This dataset is ideal for:
- Sales trend analysis and forecasting  
- Regional performance comparison  
- Customer segmentation  
- Profitability and cost efficiency analysis

---

## 📈 Dashboard Previews

Below are visual previews of the interactive dashboards built from this dataset.

### 🧮 Executive Overview and Trends
![Executive Overview and Trends](https://github.com/anushka28mishra/regional-sales-analysis-python-powerbi-eda/blob/b0d7d386df4ebc19db24565fa2e6cc5cab9850be/Executive%20Overview%20and%20Trends.png) 
*Tracks total sales, revenue growth, and profit margins across regions and channels.*

---

### 🌍 Product and Channel Performance
![Product and Channel Performance](https://github.com/anushka28mishra/regional-sales-analysis-python-powerbi-eda/blob/b0a08d7216ba2819ca6e474ff267fb31a78b7027/Product%20and%20Channel%20Performance.png)
*Displays sales distribution, regional trends, and top-performing territories.*

---

### 🧑‍💼 [Geographic and Customer Insights
![Geographic and Customer Insights](https://github.com/anushka28mishra/regional-sales-analysis-python-powerbi-eda/blob/b539914f804e0b39d240ded347fa5d291763d1c8/Geographic%20and%20Customer%20Insights.png)
*Analyzes customer segmentation, top-selling products, and order frequency patterns.

---


## 🧠 Key Insights
- **Pronounced Seasonality:** January revenues average **$124 M**, dipping to **$95 M** in April.  
- **SKU Concentration:** Products **26 & 25** together drive ~**25 %** of total sales.  
- **Channel Trade-Off:** Wholesale captures **54 %** of volume; Export leads with **~38 %** average margin.  
- **Geographic Dominance:** **California** alone logs **7.6K orders ($230 M)**; the **West** region shows the largest swings.  
- **Top Customers:** *Aibox Company* and *State Ltd* are the most valuable customers in terms of revenue.

---

## 💡 Recommendations
- **Seasonal Promotions:** Launch recovery campaigns in April and amplify January offers to smooth revenue swings.  
- **SKU Optimization:** Focus on top-performing products 26 & 25 and phase out low-margin SKUs.  
- **Channel Expansion:** Incentivize Export partnerships for higher margins and introduce volume deals in Wholesale.  
- **Regional Investment:** Replicate California’s success in other regions and strengthen marketing in the Northeast & Midwest.  
- **Margin Monitoring:** Flag orders below 80 % margin and analyze cost drivers to uplift underperforming segments.

---

## 🧩 Conclusion
Completed end-to-end exploratory data analysis (EDA) and an interactive **Power BI dashboard** highlighting seasonality, SKU, channel, and regional insights.  
Findings guide sales strategy, resource planning, and marketing focus across regions.  
Stakeholders can now **self-serve real-time analysis** and integrate new datasets for additional use cases.

---

## 🔗 Live Dashboard
👉 [Live Dashboard](https://app.powerbi.com/groups/705547bc-6f8b-430d-8191-b659ef4abec9/reports/a7fbebe9-fb4e-44dc-bea8-12597a069b17/1e5b9cc3a0ece80ddd60?experience=power-bi)

---

## 👩‍💻 Author
**Anushka Mishra**  
[LinkedIn](https://www.linkedin.com/in/anushka-mishra-a084121b4/)
