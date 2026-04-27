# FreshMart Retail Sales Analytics & Excel Automation

<img width="1254" height="836" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/ea0cb078-a441-44ba-93c6-ed97adc6a8cf" />

> An end-to-end Excel analytics solution that transforms manual retail reporting into an automated, insight-driven system using PivotTables, dashboards, and VBA.

---

## Overview

FreshMart Supermarkets Ltd is a mid-sized UK grocery chain operating across multiple regions. Quarterly reporting was previously a **manual, time-intensive process**, requiring 2–3 days to compile, analyze, and present sales performance.

This project delivers a **fully automated Excel-based analytics system** that:

- Centralizes transactional data  
- Enables real-time performance tracking  
- Automates reporting workflows  
- Produces board-ready outputs with one click  

---

## Business Scenario

**Company:** FreshMart Supermarkets Ltd  
**Industry:** Grocery & Retail  
**Location:** Birmingham, United Kingdom  
**Operations:** 10 stores across 5 regions  

The Regional Sales Manager receives raw POS transaction data each quarter. The existing workflow involves:

- Manual data cleaning and structuring  
- Building ad-hoc charts in Excel  
- Creating summary reports in Word  

This approach is:
- Time-consuming  
- Error-prone  
- Not scalable  

---

##  Project Objectives

- Build a **centralized sales database** for all transactions  
- Develop an **interactive dashboard** with dynamic KPI tracking  
- Enable **multi-dimensional analysis** (Region, Category, Store, Quarter)  
- Automate **quarterly report generation (PDF export)**  
- Implement a **data entry system with validation controls**  
- Reduce reporting time from days to minutes  

---

## Dataset Overview

- **File:** `retail_sales_data.csv`  
- **Records:** 2,000 transactions  
- **Time Period:** Full Year 2024 (Q1–Q4)  
- **Fields:** 18 columns  

Key metrics captured include revenue, cost, profit, stock levels, and customer segmentation.

---

## System Architecture

### Workbook Structure

<img width="667" height="61" alt="Image" src="https://github.com/user-attachments/assets/0a05f08b-5a2f-46ef-a675-dedd6e01c3a8" />



| Sheet | Description |
|------|------------|
| **Data Entry** | Structured form for inputting new transactions |
| **Sales Data** | Centralized transaction database |
| **KPI Targets** | Editable performance targets |
| **Pivot Analytics** | Backend PivotTables powering visuals |
| **Dashboard** | Interactive analytics interface |
| **Data Dictionary** | Field definitions and validation rules |

> The system follows a clear flow: **Input → Storage → Processing → Visualization → Reporting**

---

## Solution Walkthrough

### Data Entry Form
<img width="601" height="642" alt="Image" src="https://github.com/user-attachments/assets/3acb8419-7270-4dab-8ccf-51626eafe61a" />

> Structured input interface with dropdown validation and automated calculations.

---

### Sales Data Table
<img width="1670" height="876" alt="Image" src="https://github.com/user-attachments/assets/41ad1091-0443-4dfc-ac66-0951ab9b2d3f" />

> Centralized dataset serving as the single source of truth.

---

### KPI Targets
<img width="850" height="495" alt="Image" src="https://github.com/user-attachments/assets/9a69edbb-27e0-4311-afcd-869166126546" />

> Editable quarterly targets that dynamically drive dashboard metrics.

---

### Dashboard
<img width="1633" height="736" alt="Image" src="https://github.com/user-attachments/assets/3833ddc0-6d07-4351-8396-5fc15eb8dec3" />

> Interactive dashboard with slicers, KPIs, and performance insights.

---

##  Key Features

### Dashboard KPIs
- Total Revenue  
- Total Cost
- Profit Margin %  
- Total Transactions 

---

### Visual Analytics
- Revenue by Region  
- Top 10 Products  
- Sales by Category  
- Monthly Revenue Trend  
- Profit Margin by Region  

---

### Interactive Filters
- Customer Type  
- Payment Method  

---

## Automation (VBA)

| Module | Function |
|-------|--------|
| SubmitTransaction | Validates and records new transactions |
| ResetForm | Clears input form and resets entries |
| UpdateDashboard | Refreshes PivotTables and charts |
| ExportQuarterlyReport | Generates PDF reports |
| ClearFilters | Resets all filters across workbook |
| AddDataValidation | Applies dropdowns and rules |
| HighlightStockRisk | Flags low-stock items |

---

## Data Validation & Integrity

- Controlled dropdown inputs (Region, Category, Payment, etc.)  
- Numeric constraints on price, quantity, and discount  
- Automated calculations for derived metrics  
- Error prevention at point of entry  

---

## Business Insights Enabled

This solution answers key business questions such as:

- Which regions drive the highest revenue?  
- Which categories yield the best margins?  
- Which stores are underperforming?  
- Which products are at risk of stockout?  
- How do customer segments behave?  

---

## Impact

| Before | After |
|------|------|
| Manual reporting (2–3 days) | Automated reporting (minutes) |
| Static analysis | Interactive dashboard |
| High error risk | Validated data entry |
| Disconnected workflow | Fully integrated system |

---

## Project Structure

 FreshMart-Sales-Analytics
 
├──  README.md

├──  VBA_MODULES.md

├──  assets/images/

└──  FreshMart_Analytics.xlsm



---

## How to Use

1. Open the `.xlsm` file and enable macros  
2. Use **Data Entry** to input transactions  
3. Click **Update Dashboard** to refresh analytics  
4. Export reports using VBA buttons  

---

## Key Skills Demonstrated

- Advanced Excel (PivotTables, dashboards)  
- VBA automation & workflow design  
- Data modeling and validation  
- Business analysis & KPI design  
- Reporting automation  

---

## Additional Documentation

- VBA Modules: https://github.com/Analyst-Idris/freshmart-sales-analytics-excel-automation/blob/main/VBA_MODULES
---

## Collaboration & Contact

I am open to collaborating on data analytics, Excel automation, and dashboard development projects.

- Email: oladejoidris55@gmail.com 
- LinkedIn: https://www.linkedin.com/in/oladejo-idris-191a6024a/
- GitHub: https://x.com/im_classic24
- WhatsApp: wa.me/2347025062857  

---

## Summary

This project demonstrates how Excel can be transformed into a **powerful analytics and automation platform**, bridging the gap between raw data and executive-level insights.
