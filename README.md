# 📊 Enterprise Sales Data Analysis (SQL Server + Power BI)

## 🎯 Project Overview
This project demonstrates an end-to-end data analytics workflow designed for enterprise-level operations. Using the official Microsoft **AdventureWorks2022** database, I leveraged the power of **SQL Server** to manage and optimize data queries, which were then seamlessly connected to **Power BI** to build an interactive, high-impact business intelligence dashboard.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Database Management:** SQL Server (SSMS), SQL Server Developer Edition.
* **Data Extraction & Manipulation:** Advanced SQL Queries (SELECT, WHERE, TOP, ORDER BY, JOINS).
* **Business Intelligence Tool:** Power BI Desktop.
* **Data Modeling:** Built an optimized **Star Schema** relationship map connecting Fact and Dimension tables (1:* Cardinality).
* **Dashboard Design:** Implemented interactive charts, KPI cards, and custom data sorting for enhanced executive decision-making.

---

## 💻 SQL Codes Implemented (Code Examples)
Inside the project, I optimized data retrieval using precise queries. For example, to identify the **Top 3 Sales Performers** exceeding \$1M in sales, I used the following code:

```sql
SELECT TOP 3 BusinessEntityID, SalesYTD, SalesLastYear
FROM Sales.SalesPerson
WHERE SalesYTD > 1000000
ORDER BY SalesYTD DESC;
```

---

## 📈 Dashboard Key Insights (Visualizations)
* **Geographical Sales Performance:** Segmented total revenue across global territories to isolate top-performing branches.
* **Executive Top Performers:** Created a dedicated VIP dashboard section displaying the organization's top 3 sales drivers dynamically.
* **Product Management:** Classified and tracked hundreds of stock items based on internal product groupings.

---

## 📂 Project Files Breakdown
* `SQL_Master_Library.sql`: Contains optimized enterprise queries used during the data preparation phase.
* `Sales_Analysis_Dashboard.pbix`: The full interactive Power BI dashboard ready for operational deployment.

---
*💡 Designed with a focus on data governance and reporting architectures suited for large-scale corporations like Saudi Aramco.*
