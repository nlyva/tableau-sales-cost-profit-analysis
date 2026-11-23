# tableau-sales-cost-profit-analysis
Tableau analysis of sales versus cost, customer sales concentration, and profit by product sub-category.
# Sales, Cost & Profit Analysis in Tableau

For a Business Analytics assignment at ADA University, I used Superstore
order data to compare sales with costs, examine how sales are concentrated
across customers, and show how product sub-categories contribute to total profit.

## Tableau Public Visualizations

| Visualization | Business question | Tableau technique |
| --- | --- | --- |
| [1. Sales vs. Cost by Product Sub-Category](https://public.tableau.com/app/profile/nazrin.aliyeva/viz/HW7-Q1_17646798282950/Sheet1) | Which product sub-categories generated sales above or below their costs? | Created a `Cost` calculated field using `[Sales] - [Profit]` and compared total sales with total cost for each sub-category. |
| [2. Customer Sales Concentration — Pareto Chart](https://public.tableau.com/app/profile/nazrin.aliyeva/viz/HW7-Q2_17646798553940/Sheet4) | What share of total sales comes from the highest-spending customers? | Sorted customers by descending sales. Used distinct customer counts (`COUNTD`), running totals, and percent-of-total calculations to plot cumulative customer share on the x-axis and cumulative sales share on the y-axis. |
| [3. Profit Contribution by Sub-Category — Waterfall Chart](https://public.tableau.com/app/profile/nazrin.aliyeva/viz/HW7-Q3_17646797992700/Sheet2) | Which product sub-categories increased or reduced total profit? | Used a running total of `SUM([Profit])` to show how each positive or negative contribution changes cumulative profit. |

## Data Source

[Hm7Orders Excel dataset](https://github.com/ogut77/BA/blob/main/Hm7Orders.xls)
