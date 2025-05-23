# Elevatelabs_task8
# Superstore Sales & Profitability Dashboard

## Project Overview

This project analyzes retail data from a fictional **Superstore** to uncover business insights, improve decision-making, and monitor key performance indicators through an interactive Power BI dashboard.

---

##  Dataset

- **Source**: `Superstore_Cleaned.csv`
- **Size**: ~9,994 rows × 21 columns
- **Fields**:  
  - `Order ID`, `Customer ID`, `Product ID`, `Sales`, `Quantity`, `Profit`, `Discount`,  
  - `Order Date`, `Ship Date`, `Region`, `State`, `City`, `Category`, `Sub-Category`, etc.

---

## Data Cleaning (Python)

The raw data was cleaned using Python:
- Parsed `Order Date` and `Ship Date` to datetime
- Removed rows with critical missing values
- Dropped duplicates
- Saved cleaned file as `Superstore_Cleaned.csv`

**Cleaning Script**: `clean_superstore_data.py`

---

## Tools Used

- **Python (Pandas)** – for data cleaning and preparation
- **Power BI Desktop** – for dashboard creation and data modeling


## Dashboard Views

### 1. Executive Summary
- Total Sales, Profit, Quantity
- Sales and Profit trends over time
- Sales by Region, Category

### 2. Sales Breakdown
- Sales by Category & Sub-Category
- Top 10 Products by Sales
- Tree map by Product Performance

### 3. Profitability & Discount
- Profit vs. Discount scatter plot
- State-wise profit heat map
- Profit margin analysis

### 4. Customer & Segment Insights
- Sales by Segment
- Repeat vs. New Customers (DAX)
- Top customers by order value

### 5. Shipping & Logistics
- Ship mode efficiency
- Avg. shipping delay
- Shipping trends over time

---

## Key Insights

-  **Furniture** has high sales but low profit margin — discount strategy needs review.
-  **California** contributes highest to revenue but also experiences higher discount rates.
-  **Same-day shipping** shows lower adoption but has higher profit per order.
-  **Consumer segment** drives the majority of sales but not profit.

---

## Files Included

- `Superstore_Cleaned.csv` – cleaned dataset
- `clean_superstore_data.py` – Python script for cleaning
- `PowerBI_Superstore.pbix` – Power BI dashboard (not included here but referenced)
- `README.md` – documentation
