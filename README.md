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
![Cleaned Dataset After Calculate important Matrixes and Conditional Formatting.](https://github.com/Junaid-Khan199/SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-/blob/a9bce75b861f9a922bdc57c20d4be4575b71c4bf/Screenshoot/Figure%202_Cleaned%20Data.png)
![Cleaned Dataset After Calculate important Matrixes and Conditional Formatting.](https://github.com/Junaid-Khan199/SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-/blob/8e78087dcac4b7f079d867a31a12948551a68754/Screenshoot/Figure%203_Cleaned%20Data%20%26%20New%20Calculated%20Columns.png)
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
![Pivot-based Business Analysis](https://github.com/Junaid-Khan199/SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-/blob/4d3641b926a83a6bedb0b96fb8d865f3cec1bbf0/Screenshoot/Figure%204_Pivot%20Tables.png)
*Figure 4: Pivot-based Business Analysis*

## Key Performance Indicators (KPIs) Performed:
-	Total Sales: $2.29M
-	Total Profit: $285K
-	Total Quantity Sold: 37,785
-	Total Orders: 9,978
-	Average Profit Margin: 12%
-	Return Rate: 8%

## Dashboard Features
The Excel dashboard includes:
-	Category-wise performance charts
-	Top products analysis
-	Regional sales and profit comparison
-	Segment performance breakdown
-	Returns impact visualization
-	Manager accountability by region
-	Yearly sales trend
-	Interactive slicers: Category, Segment, Region, Year
![Overall Dashboard layout](https://github.com/Junaid-Khan199/SUPERSTORE-SALES-RETURNS-PROFIT-ANALYSIS-DASHBOARD-EXCEL-/blob/6874f4b797e8a19cd4146e355e36bf87c3cf72df/Screenshoot/Figure%205_%20OverAll%20Dashboard%20Preview.png)
*Figure 5 Overall Dashboard layout*

## Business Insights
-	The business generated $2.29M in total sales and $285K in total profit, with an average profit margin of 12%, indicating moderate overall profitability.
-	Among categories, Technology is the most profitable ($145K profit), while Furniture generated only $18K profit despite strong sales volume, suggesting margin inefficiencies.
-	At the sub-category level, Tables recorded a negative profit of -$17.7K on $206K sales, highlighting a pricing or cost-control issue. In contrast, Phones delivered strong performance with $44.5K profit.
-	Regionally, the West region is the top performer ($108K profit), followed by the East ($90K). The Central region ($39K) shows comparatively weaker profitability, indicating potential operational gaps.
-	From a customer segment perspective, the Consumer segment contributes the highest sales ($1.16M) and profit ($133K), making it the primary revenue driver.
-	The company processed 9,978 orders, of which 800 were returned, resulting in an 8% return rate. Non-returned orders generated $261K profit, whereas returned orders significantly reduced profitability, confirming the financial impact of returns.
-	Region-wise accountability analysis shows that Anna Andreadi (West) manages the most profitable region, while other regions may require performance optimization strategies.
-	Sales show consistent year-on-year growth, increasing from $483K (2014) to $730K (2017), reflecting steady business expansion.

## Business Recommendations
-	The Tables sub-category should undergo a pricing and discount strategy review. Despite generating over $206K in sales, it resulted in a negative profit (-$17.7K), indicating margin leakage that needs immediate corrective action.
-	Given that Technology contributes $145K in profit, the company should consider expanding product offerings, increasing targeted promotions, and prioritizing inventory in this high-margin category.
-	The Central region, with only $39K profit, underperforms compared to West and East. A review of regional sales strategies, cost structure, and operational efficiency is recommended to improve profitability.
-	With an 8% return rate (800 orders), analyzing return reasons by product category and region could help reduce losses and protect overall margins.
-	As sales have grown steadily from $483K (2014) to $730K (2017), reinvesting in high-performing regions (West, East) and profitable segments (Consumer, Technology) can further accelerate growth.

## Tools Used
-	Microsoft Excel,		Pivot Tables,		Slicers,		(Shapes)Dashboard Design
-	AI (Chat GPT)

# Conclusion
This project demonstrates how raw retail data can be transformed into meaningful business insights using Excel. Through data cleaning, structured analysis, and dashboard design, the report provides clear visibility into sales performance, profitability, regional contribution, and return impact. The dashboard enables decision-makers to quickly understand trends and identify improvement areas.
