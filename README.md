# Freshmart-Sales-Analytics-Excel-Automation

<img width="1254" height="836" alt="Image" src="https://github.com/user-attachments/assets/ea0cb078-a441-44ba-93c6-ed97adc6a8cf" />

---

## BUSINESS SCENARIO

**Company:** FreshMart Supermarkets Ltd
**Industry:** Grocery & Retail
**Headquarters:** Birmingham, United Kingdom
**Operations:** 10 stores across 5 regions — North, South, East, West, Central

FreshMart is a mid-sized supermarket chain operating 10 stores across the UK.
Every quarter, the Regional Sales Manager receives a raw transaction file from
the POS system containing thousands of rows of sales data across products,
categories, stores, and sales reps.

The current process is entirely manual; the manager copies data into a blank
spreadsheet, builds ad-hoc charts, and emails a Word document summary to the
board. This takes 2–3 days every quarter and is highly error-prone.

**The Ask:** Build a professional Excel-based Quarterly Sales Analytics Solution
that automates the entire reporting process from data entry to board-ready PDF.

---

## PROJECT OBJECTIVES

1. Centralise all quarterly sales transactions in a structured Excel database
2. Build an interactive dashboard with dynamic KPI targets the manager can update
3. Enable drill-down analysis by Region, Category, Quarter, and Store
4. Automate quarterly PDF report generation with one click
5. Add a data entry form so new transactions can be logged directly in Excel
6. Validate all data entry to prevent errors at the source

---

## 📊 DATASET OVERVIEW

**File:** retail_sales_data.csv 
**Rows:** 2,000 transactions (500 per quarter)
**Period:** Full Year 2024 — Q1 through Q4
**Columns:** 18 fields

| # | Column | Type | Description |
|---|--------|------|-------------|
| 1 | Transaction ID | Text | Unique ID per sale (TXN1000+) |
| 2 | Date | Date | Transaction date (YYYY-MM-DD) |
| 3 | Quarter | Text | Q1, Q2, Q3, Q4 |
| 4 | Month | Integer | Month number (1–12) |
| 5 | Region | Text | North, South, East, West, Central |
| 6 | Store | Text | Store name and location |
| 7 | Product | Text | Product name |
| 8 | Category | Text | Product category (9 categories) |
| 9 | Unit Price | Decimal | Price per unit in GBP |
| 10 | Quantity | Integer | Units sold per transaction |
| 11 | Discount | Decimal | Discount applied (0–0.15) |
| 12 | Revenue | Decimal | Net revenue after discount |
| 13 | Cost | Decimal | Cost of goods sold |
| 14 | Profit | Decimal | Revenue minus Cost |
| 15 | Stock Level | Integer | Remaining stock units |
| 16 | Payment Method | Text | Cash, Card, Mobile Pay, Voucher |
| 17 | Customer Type | Text | Regular, New, Loyalty Member, Online |
| 18 | Sales Rep | Text | Name of sales representative |

---

## WORKBOOK STRUCTURE (6 Sheets)

| Sheet | Description | 
|-------|-----------|
| **Data Entry** | Data entry form for new transactions |
| **Sales Data** | Master database — all transactions |
| **KPI Targets** | Dynamic targets the manager sets each quarter |
| **Pivot Analytics** | PivotTables powering all charts |
| **Dashboard** | Interactive quarterly dashboard with slicers |
| **Data Dictionary** | Field definitions and validation rules |

---

## DASHBOARD KPI CARDS (6 Cards)

1. Total Revenue
2. Total Profit
3. Profit Margin %
4. Total Transactions
5. Top Performing Region
6. Best Selling Category

---

## CHARTS ON DASHBOARD (6 Charts)

1. **Revenue by Region** 
2. **Top 10 Products by Revenue**
3. **Sales by Category** 
4. **Monthly Revenue Trend** 
5. **Profit Margin by Region**

---

## SLICERS (2 Interactive Filters)

- Customer Type
- Payment Method

---

## VBA AUTOMATION MODULES

### MODULE 1 — SubmitTransaction
Validates and saves new transactions from the Data Entry sheet to the Sales Data table

### MODULE 2 — ResetForm
Deletes last submitted record + clears Data Entry form

### MODULE 3 — UpdateDashboard
Refreshes all PivotTables, recalculates KPI targets, and updates charts

### MODULE 4 — ExportQuarterlyReport
Exports Dashboard as timestamped PDF to project folder

### MODULE 5 — ClearFilters

Clears all applied filters from tables and PivotTables across the workbook

### MODULE 6 — AddDataValidation
Sets all dropdowns and number rules on the Data Entry sheet (run once)

### MODULE 7 — HighlightStockRisk
Scans Sales Data, highlights rows where Stock Level < 20 in red

---

## DYNAMIC KPI TARGETS 

The manager fills in these cells each quarter — all dashboard cards
and charts automatically update to show the current values:

---

## DATA VALIDATION — Data Entry SHEET DROPDOWNS

| Field | Dropdown Options |
|-------|-----------------|
| Quarter | Q1, Q2, Q3, Q4 |
| Region | North, South, East, West, Central |
| Store | Dynamic based on region selected |
| Category | 9 categories |
| Payment Method | Cash, Card, Mobile Pay, Voucher |
| Customer Type | Regular, New, Loyalty Member, Online |
| Sales Rep |  Rep names |

---

## KEY BUSINESS QUESTIONS ANSWERED

1. Which region generates the most revenue each quarter?
2. Which product category has the highest profit margin?
3. Which stores are underperforming vs KPI targets?
4. Which sales reps are hitting their numbers?
5. What is the month-on-month revenue trend?
6. Which products are at risk of stockout?
7. Are loyalty members spending more than new customers?
8. Which payment method is most popular?

---




