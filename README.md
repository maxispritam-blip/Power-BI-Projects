# 📊 Power BI Analytics & Data Visualization Portfolio

Welcome to my Business Intelligence portfolio! This repository contains **5 end-to-end Power BI projects** designed to solve complex business problems, transform raw data into actionable insights, and deliver data-driven solutions for stakeholders across various industries.

---

## 🛠️ Global Technical Stack
* **BI Tool:** Power BI Desktop / Power BI Service
* **Languages:** DAX (Data Analysis Expressions), M Language (Power Query)
* **Data Modeling:** Star Schema, Snowflake Schema, Fact/Dimension tables
* **Data Connectivity:** Excel, CSV, Multi-sheet Relational Datasets

---

## 📂 Portfolio Directory

| Project Name | Industry/Domain | Key Metrics Tracked | High-Impact Technical Feature |
| :--- | :--- | :--- | :--- |
| [1. Blinkit India Analysis](#1-blinkit-indias-last-minute-app-analysis) | Quick-Commerce / Retail | Total Sales ($1.20M), Avg Rating, Outlet Sizes | Dynamic Filter Panels & Matrix Granularity |
| [2. Madhab E-Commerce](#2-madhab-e-commerce-sales-dashboard) | E-Commerce / Retail | Total Amount (438K), AOV, Payment Modes | Sub-Category Profitability Pareto-style Views |
| [3. Corporate Financials](#3-corporate-financial-analysis-dashboard) | Corporate Finance | Total Revenue ($127.41M), Sales Rep KPI Tables | Multi-Axis Regional Dual charts & Store Ranks |
| [4. Food Store Sales](#4-food-store-dashboard) | Hospitality / QSR | Total Orders (2746), Delivery vs. Cancellation | Multi-File Segmented Monthly Data Ingestion |
| [5. Mobile Device Sales](#5-mobile-sales-dashboard) | Consumer Tech / Retail | Total Sales (769M), Same Period Last Year (SPLY) | Advanced DAX Time Intelligence (YoY & MTD) |

---

## 📊 Detailed Project Breakdowns

### 1. Blinkit India's Last Minute App Analysis
* **Business Use Case:** Designed to monitor retail operations, outlet efficiency, and product type profitability for a major quick-commerce delivery platform.
* **Key KPIs:** `$1.20M` Total Sales, `8,523` Items Uniquely Tracked, `3.9/5` Average Customer Rating.
* **Visual Highlights:** 
  * Outlet establishment trend lines showing performance variance since 2010.
  * Deep-dive donut visual tracking fat content split (`$776.3K` Low Fat vs. Regular).
  * Comprehensive grid comparing Grocery Stores vs. Supermarket Types on Item Visibility.
* **Technical Focus:** Dynamic UI formatting leveraging collapsible side filter panels for Location, Size, and Item Type segmentation.

---

### 2. Madhab E-Commerce Sales Dashboard
* **Business Use Case:** A dark-themed executive dashboard built to track transactional profitability, payment defaults/methods, and customer retention metrics.
* **Key KPIs:** `438K` Total Sales Amount, `5,615` Total Quantities Sold, `121K` Average Order Value (AOV), `37K` Net Profit.
* **Visual Highlights:**
  * Regional geo-mapping breakdown highlighting Maharashtra and Madhya Pradesh as top volume drivers.
  * Payment mode preference breakdown (Credit Card at `34%`, COD at `34%`, EMI at `13%`).
  * Sub-category profitability tracking showing high-performing assets like Printers and Bookcases against low-margin Tables.
* **Technical Focus:** Interactive quarter slicers (Q1-Q4) wired to dynamic tooltips showing high-value client purchases (e.g., Harivansh, Madhav).

---

### 3. Corporate Financial Analysis Dashboard
* **Business Use Case:** Built for global operations managers to evaluate top-performing store branches, global regions, and specific sales representative target achievements.
* **Key KPIs:** `$127.41M` Global Revenue, `$39.04K` Average Ticket Price, `3,264` Global Transactions across multiple countries.
* **Visual Highlights:**
  * Multi-axis line and clustered column chart charting revenue generation against average metrics across international territories.
  * Individualized Sales Representative Leaderboard showing itemized transaction counts and revenue ownership (e.g., Andrew T. tracking `$20.92M`).
  * Dynamic store matrix cross-filtering performance metrics across 5 distinct retail footprints.
* **Technical Focus:** Cross-report page filtering and advanced relational data modeling linking region, products (Smartphones, Accessories, Tablets, Laptops), and chronological sales data.

---

### 4. Food Store Dashboard
* **Business Use Case:** Developed for supply chain and restaurant operators to isolate operational bottlenecks, track delivery success rates, and analyze menu demand.
* **Key KPIs:** `2,746` Total Orders filled, segmented by customer tiers (Gold vs. Regular membership).
* **Visual Highlights:**
  * Operational delivery-status matrix tracking fulfilled vs. cancelled quantities across distinct categories (Snacks vs. Main Courses vs. Starters).
  * Restaurant leaderboard tracking order velocity for iconic locations (Bukhara, Saravana Bhavan, Indian Accent).
  * Theme-based categorical visual showing cuisine volume split (North Indian leading with `1,478` orders).
* **Technical Focus:** Appending and consolidating disjointed monthly data sheets (`January_Sales` through `April_Sales_2023`) seamlessly using Power Query transformation steps.

---

### 5. Mobile Sales Dashboard (Multi-Page Advanced BI)
* **Business Use Case:** An enterprise-level retail analytics pipeline built to benchmark real-time growth, geographical distribution, customer review health, and year-over-year revenue retention.
* **Key KPIs:** `769M` Aggregate Sales, `19K` Total Units Sold, `4K` Transaction Volumes, `200.57K` Sales Margins.
* **Visual Highlights:**
  * **Page 1 (Sales Overview):** Interactive map highlighting city-level distributions (Delhi, Bangalore, Chennai) alongside smartphone model trends (iPhone SE leading at `$59.6M`).
  * **Page 2 (MTD Trends):** Advanced linear forecasting modeling Month-To-Date (MTD) velocities peaking at `$23.9M` in March.
  * **Page 3 (SPLY Analysis):** Side-by-side growth bars comparing active sales vs. **Same Period Last Year** metrics across months, quarters, and global brands.
* **Technical Focus:** Advanced DAX Time Intelligence modeling (`TOTALMTD`, `SAMEPERIODLASTYEAR`, and custom date tables) to generate deep variance metrics.

---

## 🧠 Core Engineering Principles Applied
1. **Star Schema Data Modeling:** Every report enforces clean entity separation by organizing data into optimized Fact tables flanked by clear Dimension tables (`Dim_Date`, `Dim_Products`, `Dim_Customers`).
2. **DAX Best Practices:** Shifted heavy processing loads away from visuals by utilizing variables (`VAR`/`RETURN`) inside DAX calculations to drastically improve dashboard rendering speeds.
3. **User-Centric UI/UX Design:** Implemented consistent color spacing, accessible typography, distinct high-contrast layouts, visual grouping containers, and minimal clutter to make data reading instantaneous.

---
