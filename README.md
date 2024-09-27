
# Sales Analysis Dashboard for Tea Products (2021)

## Project Objectives
- The primary objective of this project was to develop a comprehensive sales analysis dashboard for a range of tea products, focusing on revenue, profit margins, and customer segments. 
- This analysis provides insights into **product performance**, **regional sales**, and **customer types** to aid in strategic decision-making for improving sales and profitability.

## Key Insights and Findings
### Total Revenue and Profit:

- **Total Revenue**: CAD 208,718
- **Total Cost**: CAD 177,371
- **Total Profit**: CAD 31,347
- **Gross Profit Margin (GPM)**: 15%
### Top Performing Products:

- Bamboo Grove Tea was the top-selling product, generating CAD 86,642 in revenue with an 11% GPM.
- Henan Happy Tea had the highest profit margin at 40%, despite lower total revenue compared to Bamboo Grove Tea.
### Customer Segments:

- Distributor customers contributed the highest share of revenue (56.43%), followed by Grocery Stores (32.88%).
- Other segments such as Barn and Restaurants had a minor contribution of 8.14% and 2.55% respectively.
### Regional Performance:

- The United States accounted for 54.13% of total revenue, slightly ahead of Canada (45.87%).
- Cities like Seattle and Vancouver were top revenue generators, with Seattle contributing CAD 46,000 and Vancouver CAD 46,000.
### Trends Over Time:

- Both revenue and orders trended downward between October 2020 and September 2021, with a 24.88% decrease in revenue and an 18.84% decrease in orders.
- The steepest decline was observed between April 2021 and September 2021, where orders fell from 63 to 56.
## Key Questions Explored
- Which product had the **highest sales** and **profit margins**?
Bamboo Grove Tea led in sales, while Henan Happy Tea had the highest profit margin.
- Which **customer segment** contributed the **most to the revenue**?
Distributors were the top revenue-generating customer segment.
- What were the **regional sales trends**?
The US outperformed Canada slightly, with Seattle and Vancouver leading city-wise revenue generation.
- How did **sales evolve over time**?
There was a noticeable downward trend in sales, particularly after April 2021.
Challenges and Limitations
## Data Availability:
- The dataset lacks specific **customer-level details**, which would help in deeper segmentation and personalization of sales strategies.
- **Time-series** data was limited to the year 2021, which restricted analysis of longer-term trends.
- **Granularity of Cost Data**: More detailed cost data by product type and customer type would provide better insights into profitability drivers.
## Technical Details
### Semantic Model:
* The model includes tables for **sales** data, **product types**, **customer segments**, and **regional information**.
- Key relationships were established between these entities to facilitate meaningful cross-analysis of **revenue**, **profit margins**, and **customer trends**.

### DAX Measures:

- Total Revenue = SUM(Sales[Revenue])
- Total Cost = SUM(Sales[Cost])
- Total Profit = [Total Revenue] - [Total Cost]
- Gross Profit Margin (GPM) = DIVIDE([Total Profit], [Total Revenue], 0)
*These measures were crucial in providing insights into profitability, especially when broken down by product, region, and customer type.*
### Visualizations:

* Bar Charts: Used to display revenue and orders by month, product, and customer type.
* Pie Charts: Highlighted the contribution of different customer segments and product types to overall revenue.
* Maps: Showed regional sales performance across Canada and the United States, with specific focus on key cities like Seattle and Vancouver.
### Power BI Features Utilized:

* Slicers for filtering by year, quarter, and month.
* Drill-through functionality to allow deeper exploration of product-specific and region-specific data.
