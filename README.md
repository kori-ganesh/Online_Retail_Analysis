# 📊 Online Retail Analytics: Strategic EDA & Customer Insights

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=seaborn&logoColor=white)

## 📌 Project Executive Summary
This project involves a deep-dive Exploratory Data Analysis (EDA) of online retail transactions. Developed in **Google Colab**, the analysis moves beyond basic data cleaning to provide actionable business intelligence regarding customer retention, geographical market dependency, and seasonal inventory planning.

## 🗂️ Dataset Information
The analysis is performed on the **Online Retail Dataset**, which contains all transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based, non-store online retail business.

* **Data Source:** [UCI Machine Learning Repository - Online Retail](https://archive.ics.uci.edu/ml/datasets/online+retail)
* **Key Columns:**
    * `InvoiceNo`: 6-digit integral number uniquely assigned to each transaction.
    * `StockCode`: 5-digit integral number uniquely assigned to each distinct product.
    * `Description`: Product (item) name.
    * `Quantity`: The quantities of each product per transaction.
    * `InvoiceDate`: The day and time when each transaction was generated.
    * `UnitPrice`: Product price per unit in sterling.
    * `CustomerID`: 5-digit integral number uniquely assigned to each customer.
    * `Country`: The name of the country where each customer resides.

---

## 📈 Business Insights & Visualizations

### 1. Customer Churn & Retention Analysis
Understanding when a customer is "at risk" is vital for retention marketing.
* **Analysis:** Used a **Histogram** to visualize the distribution of customer recency.
* **Metric:** Established a **Churn Threshold of 90 days**.
* **Action:** A vertical blue dashed line (`axvline`) identifies customers who haven't purchased in 3+ months, marking them as targets for re-engagement campaigns.

> **[Space for Screenshot: Customer Churn Histogram]**

---

### 2. Product Portfolio Contribution
Is the business over-reliant on a single "hero" product?
* **Analysis:** Top 5 products by percentage contribution using a **Horizontal Bar Chart**.
* **Insight:** The analysis indicates that sales are not dependent on a single product but are distributed across most products. This indicates a **healthy product mix** and low risk of revenue loss if one item goes out of stock.

> **[Space for Screenshot: Top 5 Products Bar Chart]**

---

### 3. Geographical Market Risk Assessment
Identifying revenue concentration and market vulnerability.
* **Analysis:** Top 5 countries by percentage contribution using a **Horizontal Bar Chart**.
* **Critical Insight:** Sales are heavily dependent on the **United Kingdom (84.6%)**.
* **Recommendation:** This concentration represents a potential risk. The retailer should offer special discounts and loyalty programs to retain the UK base while diversifying into other international markets to avoid heavy losses if the local market faces a downturn.

> **[Space for Screenshot: Top 5 Countries Bar Chart]**

---

### 4. Temporal Sales Trends & Inventory Planning
When should the business scale its operations?
* **Analysis:** Monthly sales trends visualized via a **Line Chart**.
* **Observation:** Sales show a steady increase starting in **August** and reach a **peak in November**.
* **Business Logic:** This surge is likely due to the holiday/festival season. The business must complete inventory management and stock-up by Q3 to meet this year-end demand.

> **[Space for Screenshot: Monthly Sales Line Chart]**

---

## 🛠️ Technical Implementation
* **IDE:** Google Colab
* **Language:** Python
* **Libraries:** Pandas, Matplotlib, Seaborn, NumPy, Openpyxl
* **Data Cleaning:** Handled missing values in `CustomerID`, removed negative `Quantity` and `UnitPrice` values, and managed outliers using quantile-based filtering.

## 🚀 Conclusion
The analysis reveals a business with a strong, diverse product line and a powerful seasonal peak. By monitoring the 90-day churn threshold and diversifying the geographical market beyond the UK, the retailer can ensure long-term stability and growth.

---

## 👤 Contact Me
**Kori Ganesh**
* **Role:** Data Analyst
* **Email:** [gldnganesh@gmail.com](mailto:gldnganesh@gmail.com)
* **LinkedIn:** [Your LinkedIn Profile Link]
* **GitHub:** [Your GitHub Profile Link]
