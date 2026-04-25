# 🛍️ Daily Sales - DTC Power BI Dashboard

## 📊 Project Overview
This Power BI dashboard tracks daily sales performance 
for a Direct-To-Consumer (DTC) business operating across 
Ecommerce and Retail channels in Canada (CA) and 
United States (US).

---

## 🎯 Business Problem
The business needed a centralized dashboard to:
- Monitor daily, weekly, monthly, quarterly & yearly sales
- Compare Actual Sales vs Budget targets
- Track Year Over Year (YOY) performance
- Identify underperforming locations
- Monitor Returns and Discounts by location

---

## 📌 Key KPIs Tracked

| Time Period | Actual Sales | Budget | % Budget | % YOY |
|-------------|-------------|--------|----------|-------|
| Year | $23,050,260 | $24,091,093 | 96% | +11% |
| Quarter | $6,676,820 | $6,887,635 | 97% | -2% |
| Month | $3,535,954 | $3,642,316 | 97% | -18% |
| Week | $207,530 | $253,012 | 82% | -72% |
| Day | $89,343 | $105,515 | 85% | -70% |

---

## 📍 Location Coverage

### Ecommerce Channel
- CA Online
- US Online

### Retail Channel
- CA - Calgary
- CA - Kitsilano
- CA - Ossington
- CA - Ottawa
- CA - Pop Up
- CA - Southgate
- CA - Square One

---

## 📈 Dashboard Pages

### 1️⃣ Summary Page
- Year/Quarter/Month/Week/Day KPI cards
- Location Summary Table
- Actual vs Budget comparison
- YOY % change by location
- Returns & Discounts tracking

### 2️⃣ Budget Tracking Page
- Cumulative Budget vs Cumulative Sales line chart
- Net Sales to Budget Ratio trend
- Location wise budget breakdown
- Total Budget = $38,416,488

---

## 🔍 Key Insights
- ✅ Yearly sales ON TRACK at 96% of budget
- ✅ Year over year growth of 11% at yearly level
- ⚠️ Weekly and Daily sales showing decline vs last year
- ⚠️ CA - Calgary underperforming at only 41% of budget
- ✅ CA - Square One exceeded budget at 104%
- 📉 Ecommerce down 78% YOY on daily basis

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** — Dashboard development
- **DAX** — Calculated measures
  - YOY % calculations
  - Budget % calculations
  - Cumulative Sales & Budget
- **Power Query** — Data transformation
- **Data Source** — Sales & Budget data

---

## 📐 DAX Measures Used
- YOY % = (Actual Sales - Last Year Sales) / Last Year Sales
- Budget % = Actual Sales / Budget
- Cumulative Sales = TOTALYTD(Sales)
- Cumulative Budget = TOTALYTD(Budget)
- Net Sales to Budget Ratio = Cumulative Sales / Cumulative Budget


November 2025
