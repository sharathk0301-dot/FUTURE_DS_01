# 📊 Business Sales Performance Analytics
### Future Intern — Data Science & Analytics Internship | Task 1

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
![Internship](https://img.shields.io/badge/Future%20Intern-Task%201-blueviolet?style=flat)

---

## 📌 Project Overview

This project is the **first task** of the **Future Intern Data Science & Analytics Internship**.[web:34]  
It performs a complete **Exploratory Data Analysis (EDA)** on a custom Superstore Management System dataset to uncover actionable business insights related to:

- Sales and profitability trends  
- Category and regional performance  
- Customer segment behavior  
- Delivery and order fulfillment analysis  
- Inventory and supplier insights  

---

## 📁 Project Structure

```text
Business-Sales-Performance-Analytics/
│
├── EDA_superstone.ipynb                 # Main Jupyter Notebook (Full EDA)
├── Superstore_Management_System.csv     # Source dataset (custom)
├── superstore_analysis_results.csv      # Exported analysis summary results
└── README.md                            # Project documentation

```
## 📂 Dataset Description

**File:** `Sample_Superstore_cleaned.csv` *(Cleaned Superstore dataset)*  
**Source:** Classic Sample Superstore retail data with cleaning applied[file:65]  

| Column | Description |
|--------|-------------|
| Row ID | Unique row index for each record |
| Order ID | Unique identifier for each order group |
| Order Date | Date when the customer placed the order |
| Ship Date | Date when the order was shipped |
| Ship Mode | Shipping method used (e.g., Same Day, Second Class, Standard Class) |
| Customer ID | Unique identifier for each customer |
| Customer Name | Full name of the customer |
| Segment | Customer segment — Consumer, Corporate, Home Office |
| Country | Country of the customer (mostly United States) |
| City | City where the order was placed |
| State | State where the order was shipped |
| Postal Code | Postal/ZIP code of the shipping address |
| Region | Region — West, East, Central, South |
| Product ID | Unique identifier for each product |
| Category | High-level product category — Furniture, Office Supplies, Technology |
| Sub-Category | More detailed product type (e.g., Chairs, Phones, Storage, Binders) |
| Product Name | Full product description/name |
| Sales | Sales revenue for the line item |
| Quantity | Number of units sold in the line item |
| Discount | Discount rate applied to the line item (0–1) |
| Profit | Profit earned on the line item after discount and cost[file:65] |

---

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| 💰 Total Sales | $12,737,842.60 |
| 📈 Total Profit | $3,186,464.74 |
| 🛒 Total Orders | 1,000 |
| 📉 Avg. Profit Margin | 25.02% |
| 🏆 Top Category | Grocery ($846,039.25) |
| 🌍 Best Region | North |
| 👥 Best Customer Segment | Home Office |


---

## 🔍 Analysis Performed

- Sales & Profit Overview — Total revenue, profit, order count, and margin analysis on the cleaned Superstore dataset.  
- Category Performance — Comparison across Furniture, Office Supplies, and Technology.  
- Regional Analysis — Sales and profit breakdown by West, East, Central, and South regions.  
- Customer Segment Analysis — Revenue and profitability for Consumer, Corporate, and Home Office customers.  
- Delivery & Ship Mode Analysis — Distribution of Standard, Second Class, First Class, and Same Day shipments.  
- Time Series Analysis — Yearly and monthly sales trends across 2014–2017 based on order dates.  
- Discount Impact Analysis — Relationship between discount rates and profit for different categories.  
- Product & Sub-Category Insights — Identification of top and bottom performing sub-categories and products[file:65]  

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas — Data manipulation and analysis  
- NumPy — Numerical computations  
- Matplotlib — Data visualization  
- Seaborn — Statistical plots  
- Jupyter Notebook — Interactive development environment  

---

## 🙌 Acknowledgements

- **Future Intern** — For providing this internship opportunity.[web:34]  
- The dataset (`Sample_Superstore_cleaned.csv`) is a cleaned version of the popular Sample Superstore dataset, prepared specifically for this analysis.[file:65]

## Sample Superstore – first 20 rows

| Row ID | Order ID | Order Date | Ship Date | Ship Mode | Customer ID | Customer Name | Segment | Country | City | State | Postal Code | Region | Product ID | Category | Sub-Category | Product Name | Sales | Quantity | Discount | Profit |
| ...    | ...      | ...        | ...       | ...       | ...         | ...           | ...     | ...     | ...  | ...   | ...         | ...    | ...        | ...      | ...          | ...          | ...   | ...      | ...      | ...    |

Full dataset: [Sample_Superstore_cleaned.csv](Sample_Superstore_cleaned.csv)
