# SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-
## Excel-based sales performance analysis with interactive dashboard, KPIs, and business insights.

## Dataset Information
The dataset was sourced from Kaggle and contains three related tables:
- Orders – Sales transactions, products, customers, and profit data
- Returns – Information about returned orders
- People – Region-wise responsible managers

## Data Preparation & Cleaning
![Raw Data Before Analysis](https://github.com/Junaid-Khan199/SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-/blob/90c0f08d0e42d49f6ed1b42f93a72736c6877def/Screenshoot/Figure%201_Raw%20Data.png)
*Figure 1 Raw Dataset Before Analysis.*

- Standardized date and numerical formats
-	Identified logical duplicates using Order ID + Product ID
-	Aggregated duplicate records to ensure accurate totals
-	Linked Returns and People tables with Orders
-	Created calculated columns:
    +	Profit Margin
    +	Order Year
    +	Return Flag
-   Final cleaned dataset structured as **Master Data**
![Figure 2&3: Cleaned Dataset After Calculate important Matrixes and Conditional Formatting.](https://github.com/Junaid-Khan199/SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-/blob/a9bce75b861f9a922bdc57c20d4be4575b71c4bf/Screenshoot/Figure%202_Cleaned%20Data.png)
![Figure 2&3: Cleaned Dataset After Calculate important Matrixes and Conditional Formatting.](https://github.com/Junaid-Khan199/SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-/blob/8e78087dcac4b7f079d867a31a12948551a68754/Screenshoot/Figure%203_Cleaned%20Data%20%26%20New%20Calculated%20Columns.png)
*Figure 2&3: Cleaned Dataset After Calculate important Matrixes and Conditional Formatting.*

## Analysis Performed
The following analyses were conducted using Pivot Tables:
-	Overall Sales & Profit Summary
-	Category and Sub-Category Performance
-	Regional Sales & Profit Comparison
-	Customer Segment Analysis
-	Returned vs Non-returned Orders Comparison
-	Return Rate Calculation
-	Regional Performance by Manager
-	Year-wise Sales Trend
