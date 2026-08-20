# 🛒 E-Commerce Customer Intelligence & Sales Analytics

<p align="center">
  <img src="Screenshots/Dashboard.jpeg" alt="E-Commerce Sales Dashboard" width="100%">
</p>

<p align="center">
  <b>End-to-End Data Analysis Project using Python, Pandas, RFM Customer Segmentation & Tableau</b>
</p>

<p align="center">
  <a href="https://github.com/Unknowncoder3/E-Commerce-Customer-Intelligence-Sales-Analytics">
    <img src="https://img.shields.io/badge/GitHub-Repository-black?logo=github" alt="GitHub">
  </a>
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Tableau-Dashboard-E97627?logo=tableau" alt="Tableau">
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Status">
</p>

---

## 📌 Project Overview

**E-Commerce Customer Intelligence & Sales Analytics** is an end-to-end data analytics project built to transform raw online retail transaction data into meaningful business insights.

The project combines **Python-based data cleaning and exploratory analysis**, **RFM customer segmentation**, and an **interactive Tableau dashboard** to analyze sales performance, customer behavior, products, countries, and purchasing trends.

The goal is to answer practical business questions such as:

* How much revenue is being generated?
* Which countries contribute the most revenue?
* Which products generate the highest sales?
* Which customer segments are most valuable?
* How does revenue change throughout the year?
* Which quarters perform best?
* Which days of the week generate the most revenue?
* How can customers be segmented based on their purchasing behavior?

---

## 🎯 Business Objectives

The project focuses on four major analytical areas:

### 💰 Sales Performance

* Analyze total revenue and order volume
* Identify top-performing countries
* Analyze quarterly and monthly revenue trends
* Understand revenue distribution across weekdays

### 👥 Customer Intelligence

* Analyze customer purchasing behavior
* Calculate customer-level RFM metrics
* Segment customers based on Recency, Frequency and Monetary value
* Identify high-value and at-risk customer groups

### 📦 Product Analysis

* Identify top products by revenue
* Compare product-level performance
* Understand which products contribute most to overall sales

### 📊 Business Dashboard

* Build an interactive Tableau dashboard
* Add dynamic country and date filters
* Present KPIs and visual insights in a business-friendly format

---

# 🛠️ Tech Stack

| Technology          | Purpose                               |
| ------------------- | ------------------------------------- |
| 🐍 Python           | Data analysis and preprocessing       |
| 🐼 Pandas           | Data cleaning and manipulation        |
| 📓 Jupyter Notebook | Exploratory data analysis             |
| 📊 Tableau          | Interactive dashboard & visualization |
| 📗 Excel            | Source retail transaction dataset     |
| 🧮 RFM Analysis     | Customer segmentation                 |
| 🔧 Git & GitHub     | Version control and project hosting   |

---

# 📂 Project Structure

```text
E-Commerce-Customer-Intelligence-Sales-Analytics/
│
├── 📁 Datasets/
│   ├── Online Retail.xlsx
│   ├── rfm_customer_segmentation.csv
│   └── rfm_customer_segmentation_tableau.csv
│
├── 📁 notebook/
│   └── 01_data_cleaning.ipynb
│
├── 📁 Screenshots/
│   └── Dashboard.jpeg
│
├── 📁 Tableau/
│   └── Online Retail Sales Dashboard.twbx
│
├── 📄 .gitignore
└── 📄 README.md
```

---

# 🔄 Project Workflow

```text
Raw E-Commerce Data
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
RFM Analysis
        ↓
Customer Segmentation
        ↓
Sales Analysis
        ↓
Tableau Visualization
        ↓
Interactive Business Dashboard
```

---

# 🧹 1. Data Cleaning & Preprocessing

The raw **Online Retail** dataset contains transactional information including:

* Invoice Number
* Invoice Date
* Customer ID
* Country
* Stock Code
* Product Description
* Quantity
* Unit Price

The data cleaning process includes:

* Handling missing values
* Removing invalid transactions
* Handling cancelled/returned invoices
* Checking duplicate records
* Converting date columns into appropriate formats
* Creating calculated revenue values
* Preparing clean datasets for analysis

A cleaned dataset is then used for further analysis and visualization.

---

# 📊 2. Exploratory Data Analysis

The project analyzes multiple dimensions of the retail business.

### Key KPIs

* **Total Revenue:** 9.75M
* **Total Orders:** 22,061
* **Total Customers:** 4,372
* **Average Order Value:** 442

These metrics are dynamically affected by the dashboard filters.

---

# 👥 3. RFM Customer Segmentation

To understand customer behavior, the project implements **RFM Analysis**.

### R — Recency

Measures how recently a customer made a purchase.

### F — Frequency

Measures how frequently a customer makes purchases.

### M — Monetary

Measures how much revenue a customer generates.

The three metrics are combined to create an **RFM Score**, which is then used to classify customers into meaningful behavioral segments.

Example segments include:

* Champions
* Loyal Customers
* At Risk
* Potential Loyalists
* Lost Customers
* Others

This allows businesses to understand **who their most valuable customers are and which customers may require targeted retention strategies.**

---

# 📈 4. Sales Analysis

The project analyzes revenue across several dimensions.

### 🌍 Revenue by Country

Identifies the countries contributing the most revenue and highlights geographic sales concentration.

### 📅 Monthly Revenue Trend

Tracks revenue throughout the year to identify:

* Growth periods
* Seasonal patterns
* Revenue peaks
* Revenue declines

### 📦 Top 10 Products

Identifies the products generating the highest revenue.

### 👥 Customer Segment Revenue

Compares revenue generated by different customer segments.

### 📆 Revenue by Quarter

Analyzes business performance across:

* Q1
* Q2
* Q3
* Q4

### 🗓️ Revenue by Day of Week

Compares revenue generated from Sunday through Friday to identify stronger purchasing days.

---

# 📊 Interactive Tableau Dashboard

The final Tableau dashboard brings the analysis together into a single interactive business intelligence interface.

### Dashboard Features

* 📌 KPI cards
* 🌍 Country filter
* 📅 Invoice date filter
* 💰 Total revenue
* 👥 Total customers
* 🛒 Total orders
* 📦 Total quantity
* 💵 Average order value
* 🌎 Top 10 countries by revenue
* 📈 Monthly revenue trend
* 📦 Top 10 products by revenue
* 👥 Revenue by customer segment
* 📊 Revenue by quarter
* 📅 Revenue by day of week

### 🔗 View the Interactive Dashboard

[**Open Dashboard on Tableau Public →**](https://public.tableau.com/app/profile/snehasish.das4354/viz/OnlineRetailSalesDashboard_17869560125930/OnlineRetailSalesDashboard)

---

# 💡 Key Business Insights

The analysis provides several actionable insights:

### 1. Geographic concentration

Revenue is highly concentrated in a small number of countries, with the **United Kingdom** being the strongest contributor.

### 2. Customer segmentation

RFM analysis reveals clear differences between high-value customers, loyal customers, potential customers, and customers showing signs of churn.

### 3. Seasonal revenue behavior

Monthly analysis shows noticeable fluctuations in revenue throughout the year, helping identify periods of stronger and weaker business performance.

### 4. Product contribution

A relatively small group of products contributes significantly to overall revenue, making product-level analysis important for inventory and sales planning.

### 5. Quarterly performance

Quarterly analysis makes it easier to compare business performance and identify the strongest periods of the year.

---

# 🚀 How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/Unknowncoder3/E-Commerce-Customer-Intelligence-Sales-Analytics.git
```

## 2. Navigate to the Project

```bash
cd E-Commerce-Customer-Intelligence-Sales-Analytics
```

## 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

## 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebook/01_data_cleaning.ipynb
```

Run the notebook cells sequentially to reproduce the data cleaning and analysis workflow.

---

# 📊 Open the Tableau Dashboard

The Tableau workbook is available inside:

```text
Tableau/
```

Open the `.twbx` file using **Tableau Desktop** to explore and modify the dashboard.

The published interactive version is also available on Tableau Public.

---

# 📸 Dashboard Preview

<p align="center">
  <img src="Screenshots/Dashboard.jpeg" alt="Dashboard Preview" width="95%">
</p>

---

# 📁 Dataset

The project uses the **Online Retail** transactional dataset containing e-commerce purchase records.

The dataset includes information related to:

```text
Invoice
Product
Quantity
Invoice Date
Unit Price
Customer
Country
```

The project transforms this raw transactional data into analytical datasets suitable for customer intelligence and business reporting.

---

# 🔍 Skills Demonstrated

This project demonstrates practical experience with:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Customer Analytics
* RFM Analysis
* Customer Segmentation
* Business Intelligence
* Data Visualization
* Dashboard Development
* KPI Development
* Trend Analysis
* Git & GitHub
* Tableau

---

# 🧠 What I Learned

Through this project, I gained practical experience in taking a dataset from **raw transactional data to a complete business analytics solution**.

The project helped strengthen my understanding of:

* Turning raw data into business-ready datasets
* Identifying and handling data quality issues
* Performing customer-level analysis
* Applying RFM methodology
* Designing meaningful business KPIs
* Building interactive Tableau dashboards
* Communicating analytical findings visually
* Structuring and documenting a complete analytics project

---

# 🔮 Future Improvements

Potential improvements include:

* [ ] Add customer lifetime value analysis
* [ ] Add product profitability analysis
* [ ] Add customer retention/churn analysis
* [ ] Add sales forecasting
* [ ] Add automated data refresh
* [ ] Add advanced customer cohort analysis
* [ ] Deploy an interactive analytics application
* [ ] Add SQL-based data extraction and analysis

---

# 👨‍💻 Author

**Snehasish Das**

Aspiring Data Analyst | Data Scientist

Interested in:

**Data Analytics • Business Intelligence • Machine Learning • Data Visualization**

### Connect With Me

* 💻 [GitHub](https://github.com/Unknowncoder3)
* 📊 [Tableau Public](https://public.tableau.com/app/profile/snehasish.das4354)

---

## ⭐ If You Found This Project Useful

If you found this project interesting or useful, consider giving the repository a **⭐ star**.

It helps support the project and encourages me to build more data-driven projects.
