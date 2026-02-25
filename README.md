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
