# 📊 Northwind Sales Dashboard — Business Intelligence Analysis

An interactive **Business Intelligence solution built in Power BI** to analyze sales performance, customer activity, product performance, revenue trends, employee order volumes, and geographic sales distribution using the Northwind dataset.

The project demonstrates practical skills in **data modeling, DAX measures, KPI development, interactive dashboard design, and business insight generation**.

---

## 📌 Table of Contents

1. [Project Overview](#-project-overview)
2. [Business Questions](#-business-questions)
3. [Data Model](#-data-model)
4. [Power BI Dashboard](#-power-bi-dashboard)
5. [Key KPIs](#-key-kpis)
6. [Key Business Insights](#-key-business-insights)
7. [Strategic Recommendations](#-strategic-recommendations)
8. [Tools & Technologies](#-tools--technologies)
9. [Repository Structure](#-repository-structure)

---

## 📊 Project Overview

The **Northwind Sales Dashboard** provides an executive and detailed view of sales performance across products, customers, employees, categories, countries, and time.

The dashboard was designed to help management answer key questions around:

- Overall revenue and order performance
- Year-over-year revenue growth
- Average order value
- Product sales and revenue contribution
- Customer activity and value
- Employee order performance
- Category-level revenue contribution
- Geographic distribution of sales
- Unshipped orders and operational follow-up
- Changes in average order value over time

The solution contains two interactive Power BI pages:

1. **Executive Overview**
2. **Detailed Insights**

---

## 🎯 Business Questions

The dashboard was developed to answer the following business questions:

### Sales Performance
- What is the total revenue generated?
- How many orders have been placed?
- What is the average order value?
- How is revenue changing year over year?
- How has average order value changed over time?

### Product & Category Performance
- Which products generate the highest revenue?
- Which products have the highest sales volumes?
- Which product categories contribute the most revenue?
- Are there products with high sales volume but relatively lower revenue contribution?

### Customer Performance
- How many active customers are there?
- Which customers contribute the highest order volumes?
- How does customer value relate to total orders?

### Employee Performance
- Which employees handle the highest number of orders?
- How is order volume distributed across employees?

### Geographic Performance
- Which countries generate the highest revenue?
- Where are sales concentrated geographically?

### Operations
- How many orders remain unshipped?
- Which areas of the business may require operational attention?

---

# 🧩 Data Model

The Power BI model is organized around the following core tables visible in the project:

- **DimCustomer** — customer information
- **DimDate** — date and calendar information
- **DimEmployee** — employee information
- **DimProduct** — product information
- **FactOrderDetails** — order transaction details
- **_Measures** — centralized DAX measures used across the report

This structure supports analysis across multiple dimensions including **time, customers, employees, products, and orders**.

---

# 📈 Power BI Dashboard

## Page 1: Executive Overview

The Executive Overview provides a high-level view of the company's sales performance.

It includes:

- Total Revenue
- Total Orders
- Average Order Value
- Revenue Year-over-Year %
- Total Revenue vs. Revenue LY by Year
- Total Revenue by Category
- Total Revenue by Country
- Total Orders by Employee
- Year, Category, and Country filters

![Northwind Executive Overview](https://github.com/Litern/NorthWind-Analysis/blob/main/images/Executive%20Overview.png)

### Executive KPIs

| KPI | Value |
|---|---:|
| **Total Revenue** | $448,386,633.25 |
| **Total Orders** | 16,282 |
| **Average Order Value** | $27,538.79 |
| **Revenue YoY %** | 9.82% |

These KPIs provide management with an immediate understanding of overall sales performance.

---

## Page 2: Detailed Insights

The Detailed Insights page provides a deeper analysis of customers, products, revenue, and order behavior.

The page includes:

- Active Customers
- Unshipped Orders
- Active Customers by Year
- Customer Value: Orders vs. Revenue
- Top 10 Products Sold
- Average Order Value by Year
- Year, Category, and Country filters

![Northwind Detailed Insights](https://github.com/Litern/NorthWind-Analysis/blob/main/images/Detailed%20Insights.png)

### Detailed KPIs

| KPI | Value |
|---|---:|
| **Total Orders** | 16,282 |
| **Average Order Value** | $27,538.79 |
| **Active Customers** | 92 |
| **Unshipped Orders** | 21 |

---

# 🔎 Key Business Insights

## 1. Strong Overall Revenue Performance

The dashboard reports total revenue of approximately **$448.39 million** across **16,282 orders**, with an average order value of approximately **$27.54K**.

This indicates a strong overall sales performance and provides a useful baseline for monitoring future growth.

---

## 2. Positive Year-over-Year Revenue Growth

The Executive Overview reports a **9.82% Revenue YoY** performance.

The year-by-year revenue trend also provides management with a way to identify periods of stronger or weaker performance and investigate the underlying drivers.

---

## 3. Beverages Are the Largest Revenue Category

The category analysis shows **Beverages** as the largest revenue contributor at approximately **20.55%** of total category revenue.

Other major categories include:

- Confections
- Meat/Poultry
- Dairy Products
- Condiments
- Seafood
- Produce

This suggests that category-level performance should be monitored closely to understand where revenue concentration exists.

---

## 4. Product-Level Sales Concentration

The Top 10 Products Sold analysis highlights significant differences in both sales volume and revenue contribution.

Examples of high-volume products shown on the dashboard include:

- Teatime Chocolate Biscuits
- Thüringer Rostbratwurst
- Tofu
- Tourtière
- Tunnbröd
- Uncle Bob's Organic Dried Pears
- Valkoinen suklaa
- Vegie-spread
- Wimmers gute Semmelknödel
- Zaanse koeken

The Top 10 products together account for approximately **2.01 million units sold** and **$61.24 million in revenue** according to the detailed dashboard view.

---

## 5. Customer Value Varies with Order Volume

The **Customer Value: Orders vs. Revenue** visual compares total orders against total revenue for customers.

The analysis makes it possible to identify:

- High-order, high-revenue customers
- High-order customers with relatively lower revenue
- Lower-order, high-value customers
- Customers that may require targeted retention or upselling strategies

---

## 6. Employee Order Performance

The employee performance visual shows differences in the number of orders handled by employees.

The leading employees displayed include:

- Margaret Peacock
- Nancy Davolio
- Steven Buchanan
- Robert King
- Michael Suyama

This can support performance monitoring and workload analysis across the sales team.

---

## 7. Unshipped Orders Require Operational Monitoring

The Detailed Insights dashboard shows **21 unshipped orders**.

Although this represents a small proportion of the overall order volume, monitoring unshipped orders is important to minimize fulfillment delays and maintain customer satisfaction.

---

## 8. Average Order Value Has Changed Over Time

The Average Order Value by Year visual shows noticeable fluctuations over the analysis period, including a significant decline followed by recovery.

This can help management investigate changes in:

- Product mix
- Customer purchasing behavior
- Pricing
- Order size
- Sales strategy

---

# 💡 Strategic Recommendations

### 1. Strengthen High-Performing Categories
Continue investing in categories that contribute the largest share of revenue while identifying opportunities to improve underperforming categories.
### 2. Focus on High-Value Customers
Use customer order and revenue analysis to identify high-value customers and develop targeted retention, cross-selling, and upselling strategies.
### 3. Optimize Product Portfolio
Review the Top 10 products regularly to ensure high-demand products remain adequately stocked while evaluating products with weaker sales performance.
### 4. Monitor Unshipped Orders
Introduce regular operational monitoring of unshipped orders to reduce fulfillment delays and improve customer experience.
### 5. Use Employee Performance Insights
Use order-volume data to understand workload distribution, identify performance trends, and support targeted coaching and resource allocation.

### 6. Investigate AOV Fluctuations

Analyze periods of declining average order value to determine whether the changes are driven by customer behavior, product mix, pricing, or order composition.

---

# 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX**
- **Power BI Data Modeling**
- **Data Visualization**
- **Business Intelligence**
- **KPI & Performance Analysis**
- **Interactive Slicers and Filters**

# 👩‍💻 Project Purpose

This project demonstrates how **Power BI can transform transactional sales data into actionable business intelligence**.

The dashboard combines executive-level KPIs with detailed product, customer, employee, and geographic analysis to support data-driven decision-making.

---

## ⭐ Dashboard Highlights

**Total Revenue:** $448.39M  
**Total Orders:** 16,282  
**Average Order Value:** $27.54K  
**Revenue YoY:** 9.82%  
**Active Customers:** 92  
**Unshipped Orders:** 21  

---

## 📬 Conclusion

The Northwind Sales Dashboard provides a consolidated view of sales performance and enables management to move from raw transactional data to actionable insights.
By combining **KPIs, trend analysis, product performance, customer analysis, employee performance, and geographic reporting**, the dashboard provides a practical foundation for monitoring business performance and supporting strategic decisions.
