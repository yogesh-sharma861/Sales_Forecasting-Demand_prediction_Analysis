# Sales Forecasting & Demand Prediction Analysis

A sales forecasting project on 12,000 orders (Jan 2023 – Dec 2025) to study sales trend, seasonality and product demand, and to forecast 2026 sales using Excel and Power BI.

> **Note:** The dataset is synthetic (self-generated) and was created for this project.

## Dataset Overview
- **Orders:** 12,000
- **Period:** Jan 2023 – Dec 2025 (36 months)
- **Total Sales:** ₹8.48 cr (₹84,826,268)
- **Coverage:** 6 categories, 24 products

## Tools Used
- Microsoft Excel (monthly and weekly analysis, moving average, trend, seasonality, forecast)
- Power BI (interactive dashboard with forecast)

## Methodology
- Monthly and weekly sales aggregation
- 3-month and 4-week moving averages
- Linear trend (about ₹33K sales growth per month)
- Seasonal index by month
- Forecast model: **Trend × Seasonality**
- Forecast error (MAPE) on historical months: **about 6.6%**

## Business Questions & Insights

### 1. Which months have the highest sales?
Dec, May and Oct are the strongest months (seasonal index above 1), and December is the single biggest month. The lowest months are Aug, Feb and Sep.

### 2. Is there a seasonal pattern?
Yes.
- Sales spike in the festive season (Oct–Nov) and at year-end (Dec).
- A smaller lift appears in Apr–May (summer products like AC and fans).
- Winter products (heaters, jackets) peak in Dec–Jan, and wedding-season items peak in Nov–Dec.

### 3. What is the overall sales trend?
Increasing.

| Year | Sales | Growth |
|---|---|---|
| 2023 | ₹2.34 cr | – |
| 2024 | ₹2.85 cr | +21.8% |
| 2025 | ₹3.30 cr | +15.9% |

### 4. Which products will have high demand?
- **By forecast units (2026):** T-Shirt, Packaged Snacks, Dry Fruits Box, Yoga Mat, Bedsheet Set.
- **By forecast revenue:** Air Conditioner, Refrigerator, Laptop, Smartphone, Water Heater.
- **Strongest category growth (2025 vs 2024):** Home & Kitchen (+25.0%).

### 5. Forecast for 2026
The Trend × Seasonality model projects about **₹3.79 cr** for 2026 (+14.8% vs 2025).

### 6. Day-of-week pattern
Weekends sell about **34.6% more per day** than weekdays.

## Category Performance

| Category | Total Sales | Share | YoY 2025 vs 2024 |
|---|---|---|---|
| Appliances | ₹3.33 cr | 39.3% | +19.9% |
| Electronics | ₹2.50 cr | 29.5% | +10.0% |
| Home & Kitchen | ₹0.80 cr | 9.4% | +25.0% |
| Clothing | ₹0.76 cr | 9.0% | +17.6% |
| Sports | ₹0.72 cr | 8.5% | +6.1% |
| Grocery | ₹0.36 cr | 4.3% | +16.3% |

## Recommendations for Demand Planning
1. **Build stock before peaks:** Raise inventory for festive electronics, home & kitchen and dry fruits 6–8 weeks before October, with extra safety stock for December.
2. **Season-specific stocking:** ACs, fans, coolers and T-shirts from March; heaters and jackets from October; wedding-season clothing and bedsheets from September.
3. **Use the forecast in monthly planning:** Compare actual vs forecast every month. If actuals deviate by more than the MAPE, revise purchase orders.
4. **Staff and promote for weekends:** More staff and promotions on Fri–Sun, when daily sales are highest.
5. **Protect the low season:** Bundle offers and clearance sales in Aug–Sep to smooth cash flow and avoid dead stock.
6. **Prioritise fast growers:** More shelf space and supplier commitments for categories and products with the highest forecast growth. Review slow movers quarterly.
7. **Improve data quality:** Capture City, Payment Mode and Segment properly so regional and customer-level forecasts can be added next.

## Power BI Dashboard
The dashboard includes KPI cards (Total Sales, Total Orders, Avg Order Value, YoY Growth %), a sales trend line chart with forecast, seasonal index by month, product and category bar charts, and Year / Region slicers.

## Project Files

| File | Description |
|---|---|
| `Sales_Forecasting_Analysis_File_project4.xlsx` | Insights, monthly analysis, weekly trend and product forecast |
| `Sales_forecasting_and_demand_prediction_analysis.pbix` | Power BI dashboard |



## Author
**Yogesh Sharma**
[GitHub](https://github.com/yogesh-sharma861)
