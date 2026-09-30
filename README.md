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
<img width="898" height="501" alt="Screenshot 2026-09-29 235911" src="https://github.com/user-attachments/assets/3b7da0cc-d474-4e2f-87a8-521a5364a9d2" />
<img width="941" height="563" alt="Screenshot 2026-09-23 103945" src="https://github.com/user-attachments/assets/62342beb-deda-4807-8e6f-f7b71cbb1a3e" />

* **Geographical Sales Performance:** Segmented total revenue across global territories to isolate top-performing branches.
* **Executive Top Performers:** Created a dedicated VIP dashboard section displaying the organization's top 3 sales drivers dynamically.
* **Product Management:** Classified and tracked hundreds of stock items based on internal product groupings.

---

## 📂 Project Files Breakdown
* `SQL_Master_Library.sql`: Contains optimized enterprise queries used during the data preparation phase.
* `Sales_Analysis_Dashboard.pbix`: The full interactive Power BI dashboard ready for operational deployment.

---
---

## 💡 Executive Business Insights (Data Storytelling)
*Based on the Financial and Sales Performance Dashboard visualizations, here are the core strategic recommendations for executive decision-makers:*

### 📌 1. Time-Series Analysis: The Q4 Sales Surge (October & December)
* **Observation:** October stands out as the highest-performing month globally, generating **$21.7M** (nearly 18% of annual revenue), followed by December at **$17.4M**. Conversely, March is the lowest at **$5.6M**.
* **Strategic Recommendation:** Investigate the specific marketing campaigns or seasonal discounts that triggered the Q4 surge. Logistics and inventory teams must optimize supply chain operations and maximize warehouse stocking prior to September to prevent stockouts during peak seasons.

### 📌 2. Geographical Dominance & Market Penetration
* **Observation:** The United States dominates sales volume, while Mexico lags at the bottom of the regional sales chart.
* **Strategic Recommendation:** While maintaining stability in the mature US market, a dedicated market research team should be deployed to Mexico to evaluate competitor pricing, local distribution bottlenecks, or custom duties impacting regional growth.

### 📌 3. Profit Margin Optimization (The COGS Watch)
* **Observation:** Total Gross Sales reached **$118.73M**, yielding a Net Profit of **$16.89M**, which translates to a net profit margin of approximately **14.2%**. The majority of revenue is consumed by the Cost of Goods Sold (COGS).
* **Strategic Recommendation:** The business has high sales velocity but tight margins. The procurement department should renegotiate contracts with raw material suppliers or explore manufacturing automation to reduce COGS and expand net profitability.

