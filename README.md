# 📊 Retail Sales Analysis Dashboard using Power BI

An interactive **Retail Sales Analysis Dashboard** built using Microsoft Power BI to explore sales performance, profitability, product categories, and regional trends. This project demonstrates data cleaning, data modeling, and interactive data visualization using a Star Schema approach.

## 📌 Project Overview

The objective of this project is to transform retail sales data into meaningful insights through an interactive dashboard. It helps users explore key performance indicators (KPIs), analyze sales trends, compare product categories, and investigate regional performance.

This project was developed as part of my data analytics learning journey at **Lovely Professional University (LPU)**.

## 🎯 Key Features

* **Sales Overview:** Monitor total sales, total profit, total orders, and total quantity.
* **Sales Trend Analysis:** Explore yearly sales trends.
* **Category Analysis:** Compare sales and profit across product categories.
* **Sub-Category Analysis:** Examine sales performance across product sub-categories.
* **Regional Analysis:** Compare sales across different regions.
* **Interactive Filtering:** Use slicers to filter dashboard visuals by region and category.
* **Data Modeling:** Organize data into a fact table and dimension tables using a Star Schema approach.

## 🛠️ Tools & Technologies

* **Microsoft Power BI** — Dashboard development and visualization
* **Power Query** — Data preparation and cleaning
* **DAX** — Measures and calculations
* **Data Modeling** — Relationships between fact and dimension tables
* **Star Schema** — Structured analytical data model

## 📂 Dataset

This project uses the **Sample Superstore** retail sales dataset.

* **Records:** 9,994 rows
* **Columns:** 21
* **Data type:** Historical retail transaction data
* **Geographic scope:** United States

The dataset contains information about orders, customers, products, shipping modes, sales, discounts, and profits.

> Note: This is a historical sample dataset, not live sales data.

## 🧹 Data Cleaning & Preparation

The data preparation process included:

* Removing unnecessary leading and trailing spaces from text fields.
* Standardizing date formats.
* Setting appropriate data types for identifiers, dates, and numerical fields.
* Checking for duplicate records and duplicate Row IDs.
* Checking for missing values and invalid dates.

The cleaned dataset retains all **9,994 original records**.

## 🗂️ Data Model — Star Schema

The Power BI data model contains one fact table and four dimension tables.

### Fact Table

* `FactSales` — Contains sales transactions and numerical measures such as Sales, Profit, Quantity, and Discount.

### Dimension Tables

* `DimCustomers` — Customer details and customer segments.
* `DimProduct` — Product details, categories, and sub-categories.
* `DimDate` — Unique order dates.
* `DimShipMode` — Shipping modes.

### Relationships

The dimension tables connect to `FactSales` through one-to-many relationships, allowing interactive filtering and analysis.

## 📈 Dashboard Insights

The dashboard supports exploration of:

* Overall sales and profit performance.
* Order volume and product quantity.
* Yearly sales trends.
* Sales and profit by product category.
* Sales performance by sub-category.
* Regional sales comparisons.

The dashboard is designed to help users explore the data interactively rather than relying only on static reports.

## 🚀 How to Use

1. Download or clone this repository.
2. Ensure that Microsoft Power BI Desktop is installed.
3. Open `Retail_Sales_Analysis.pbix` in Power BI Desktop.
4. If prompted, update the dataset file path to the location of `Sample_Superstore.csv`.
5. Refresh the data if necessary.
6. Use the dashboard slicers to explore sales by region and category.

## 📸 Dashboard Preview

Screenshots of the dashboard and data model can be added here.

Suggested files:

* `screenshots/dashboard.png`
* `screenshots/data-model.png`

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Preparing and cleaning datasets.
* Building a dimensional data model.
* Creating relationships between fact and dimension tables.
* Developing interactive Power BI dashboards.
* Using DAX for analytical calculations.
* Presenting data through meaningful visualizations.

## 🙏 Acknowledgements

Developed as part of my learning journey.

Thanks to my teacher for the guidance and support throughout the learning process.

## 👤 Author

**Vivek Sharma**

B.Tech — Information Technology

---

⭐ If you find this project useful, feel free to explore the repository and share feedback.
