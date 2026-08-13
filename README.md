# ecommerce-sales-dashboard-powerbi
Power BI dashboard analyzing e-commerce sales, profit, and category performance
E-commerce businesses generate large volumes of order-level data but often lack a
single view that connects revenue, profitability, and customer behavior. This
dashboard was built to give stakeholders a quick, interactive way to monitor sales
performance, identify high/low-performing product categories, and understand
where revenue and profit are coming from — by time period, geography, and payment
method.

## Data
- **Orders table**: order-level records including order date, customer, and state
- **Details table**: line-item level data including category, sub-category,
  quantity, amount, profit, and payment mode

## Tools
- Power BI Desktop (data modeling, DAX measures, report design)

## Approach
- Built a relational data model connecting Orders and Details tables
- Created DAX measures for key metrics, including Average Order Value (AOV)
- Designed an interactive single-page dashboard with:
  - KPI summary cards (Total Sales, Total Profit, Total Quantity, AOV)
  - Time-series trend of profit by month
  - Profitability breakdown by product sub-category
  - Category and payment mode mix (donut charts)
  - Geographic performance by state
  - Top customers by sales amount
  - Quarter and State slicers for interactive filtering

## Key Insight / Outcome
Overall profit margin across the business was 8.4%, but this masked significant
variation at the sub-category level: 5 out of 20 sub-categories (including
Furnishings, Electronic Games, and Skirts) were operating at a **loss**, with
35% of all line items (529 of 1,500) being loss-making, totaling ₹38K in losses.
Rajasthan stood out as the only major state with negative overall profit despite
generating ₹22K+ in sales, and Credit Card transactions were nearly as profitable
in total as COD despite having 4x fewer orders — suggesting a more profitable
customer segment worth targeting. These findings point to specific opportunities
for margin-focused pricing review at the sub-category level and regional
performance investigation in Rajasthan.
