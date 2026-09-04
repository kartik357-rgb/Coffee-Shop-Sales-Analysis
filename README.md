# ☕ Coffee Shop Sales Analysis (Excel Project)

## 📌 Objective
The main objective of this project is to analyze retail sales data to gain 
actionable insights that will enhance the performance of the Coffee Shop.

## ❓ Recommended Analysis (Business Questions)
- How do sales vary by day of the week and hour of the day?
- Are there any peak times for sales activity?
- What is the total sales revenue for each month?
- How do sales vary across different store locations?
- What is the average price/order per person?
- Which products are the best-selling in terms of quantity and revenue?
- How do sales vary by product category and type?

## 🧹 Data Cleaning & Transformation (Power Query)
- Cleaned the **Product Details** column — values like Lg/Sm/Rg/Not Defined 
  were standardized and replaced (blank/invalid values handled).
- Used **Transform → Replace Values** to fix size-related inconsistencies 
  in Product Details.
- Applied **Transform → Format → Trim** on text columns to remove extra 
  white spaces.
- Added a new column **Total Bill** = Transaction Quantity × Unit Price.
- Cleaned **Transaction Time** column — trimmed values after the delimiter 
  and converted it into proper Time format.
- Extracted **Month** and **Day** from Transaction Date.
- Extracted **Hour** from Transaction Time to analyze order timing.

## 🛠️ Tools & Techniques Used
- Microsoft Excel
- Power Query (Data Cleaning & Transformation)
- Power Pivot / Data Model
- Pivot Tables & Pivot Charts
- Interactive Dashboard (Slicers: Month, Day)

## 📊 Analysis Performed
- Hourly & daily order trends (Pivot: Rows = Hour, Values = Count of Transactions)
- Monthly total sales revenue
- Store location-wise footfall & sales comparison
- Top 5 products by sales revenue
- Category-wise sales distribution (%)
- Average bill per person & average order per person

## 📈 Dashboard Highlights
| Metric | Value |
|---|---|
| Total Sales | $6,98,812.33 |
| Total Footfall | 2,325 |
| Average Bill per Person | $4.68 |
| Average Order per Person | 1.41 |

- **Top Store:** Astoria ($3,907.40 sales)
- **Top Category:** Coffee (37%)
- **Top Product:** Barista Espresso ($1,351.20)
- **Peak Order Hours:** ~8 AM – 10 AM

