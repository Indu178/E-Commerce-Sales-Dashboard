# 📊 Online Retail Sales Analysis Dashboard (2009–2011)

## 📌 Project Overview

This project is part of a **real-world Data Analytics Internship task**, where the goal is to analyze historical e-commerce sales data from a **UK-based online retail company** and present meaningful business insights using an **interactive Power BI dashboard**.

The analysis focuses on understanding:

* 🏆 Best-selling products
* 📅 Sales trends across months and years
* 🌍 Revenue contribution by country
* 👥 Customer purchasing behavior

The dataset reflects real transactional data, making this project highly relevant for **business decision-making scenarios**.

---

## 🎯 Project Objectives

* Clean and prepare raw transactional sales data
* Analyze product, customer, and country-wise performance
* Identify seasonal trends and revenue drivers
* Create an interactive Power BI dashboard for business insights

---

## 📁 Dataset Description

**Dataset Name:** Online Retail II
**Time Period:** 2009 – 2011
**Source:** Kaggle (UK-based online retailer)

### 📄 Files Used

* `online_retail_II.xlsx`
* `Year 2009-2010.csv`
* `Year 2010-2011.csv`

### 📊 Key Columns

| Column Name | Description                  |
| ----------- | ---------------------------- |
| InvoiceNo   | Unique invoice number        |
| StockCode   | Product/item code            |
| Description | Product name                 |
| Quantity    | Number of items purchased    |
| InvoiceDate | Date and time of transaction |
| UnitPrice   | Price per unit               |
| CustomerID  | Unique customer identifier   |
| Country     | Customer’s country           |

---

## 🧰 Tools & Technologies Used

* **Power BI Desktop** – Data modeling, DAX, dashboard creation
* **Microsoft Excel** – Initial data cleaning and formatting
* **DAX (Data Analysis Expressions)** – KPIs and calculated measures
* **Optional:** SQL – Advanced preprocessing (optional)

---

## 🔄 Data Cleaning & Preparation

The following steps were performed:

* Removed cancelled transactions (negative quantities)
* Handled missing values in `CustomerID`
* Converted `InvoiceDate` to proper date format
* Created calculated fields:

  * Total Sales = Quantity × UnitPrice
  * Month & Year for trend analysis
* Merged datasets from multiple years into one model

---

## 📊 Dashboard Features

* 📈 **Monthly & Yearly Sales Trends**
* 🏆 **Top 10 Best-Selling Products**
* 🌍 **Country-wise Revenue Contribution**
* 👥 **Customer Purchase Frequency**
* 💰 **Key KPIs**

  * Total Revenue
  * Total Orders
  * Total Customers
  * Average Order Value

🎛️ Interactive slicers:

* Year
* Month
* Country
* Product

---

## 📌 Key Insights (Sample)

* Sales peak during **November and December**, indicating strong holiday demand
* A small percentage of products generate the majority of revenue
* The **United Kingdom** contributes the highest share of sales
* Repeat customers significantly impact overall revenue

---

## 💡 Business Recommendations

* Increase inventory for high-demand products during peak seasons
* Target repeat customers with loyalty programs
* Expand marketing efforts in high-performing countries
* Reduce losses by monitoring cancelled and low-margin orders

---

## 🎓 Skills Gained

* ✔ Real-world data cleaning & preprocessing
* ✔ Time-series sales analysis
* ✔ DAX measures & KPIs
* ✔ Business-focused data storytelling
* ✔ Interactive dashboard design using Power BI

---


## 🚀 How to Run the Project

1. Download **Power BI Desktop** (Free)
2. Clone this GitHub repository
3. Open the `.pbix` file
4. Refresh the dataset if prompted
5. Explore the dashboard using filters and visuals

---

## 📺 Learning Reference

Tutorial followed for guidance:
**YouTube:** *Build E-Commerce Sales Dashboard in Power BI (Beginner Friendly)*

---

## 🙋‍♀️ Author

**Indrani S**
*Data Analytics Intern*
📍 India

---

## ⭐ Acknowledgements

* Kaggle for providing the Online Retail II dataset
* Power BI Community & Documentation
* Internship mentors and learning resources

---


