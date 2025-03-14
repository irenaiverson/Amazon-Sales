# Amazon Channel Sales Analysis 

## Project Overview
This Tableau dashboard provides an interactive analysis of Amazon sales, focusing on order status, sales trends, shipping service levels, and regional distribution. Users can dynamically filter the data to explore key sales performance metrics across different dimensions such as category, state, and order fulfillment.

#### Links to Dataset on Kaggle and Tableau Dashboard
https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data
https://public.tableau.com/app/profile/irena.iverson/viz/AmazonChannelSalesDashboard/Dashboard1

## Dataset & Key Fields Used
The dataset includes Amazon order details, and the following key fields were utilized in this analysis:
- Date – Order transaction date.
- Status – Order status (Shipped, Cancelled, Pending, etc.).
- Sales Channel – Identifies if the order was placed through Amazon or another channel.
- Ship Service Level – Shipping speed (Standard, Expedited, etc.).
- Category – Product category.
- Size – Product size variant.
- Courier Status – Indicates if the order was shipped, cancelled, or returned.
- Qty – Number of units sold per order.
- Currency – Transaction currency.
- Amount – Total sales value of the order.
- Ship State – State where the order was shipped.
- B2B – Identifies whether the order was a Business-to-Business (B2B) transaction.

## Key Features of the Dashboard
- Order Status Breakdown – Interactive bar chart categorizing orders by status (Shipped, Cancelled, Pending, etc.).
- Sales Trends Over Time – Line charts tracking quantity and sales amount by week.
- Sales Channel & B2B Performance – Displays sales distribution between Amazon and non-Amazon channels, including B2B transactions.
- Top 10 States by Sales & Shipping Service Level – Identifies high-performing regions based on expedited vs. standard shipping.
- Regional Sales Distribution – A filled map showing total quantity sold by state.
- Sales Breakdown by Size & Category – Stacked bar charts analyzing sales volume across different product sizes and categories.

## Visualizations Used in the Dashboard
- Stacked Bar Chart - Quantity by Week & Category – Shows order trends over time, segmented by product category.
- Line Chart - Amount by Week & Category – Tracks total sales value over time for different product categories.
- Donut Chart - Quantity by Courier Status & Category – Displays the percentage of orders that were shipped, unshipped, or cancelled.
- Bar Chart - Quantity by Order Status – Highlights the volume of orders by fulfillment status.
- Horizontal Bar Chart - Top 10 States by Quantity & Shipping Level – Shows the highest-selling states with a breakdown of standard vs. expedited shipping.
- Filled Map - Quantity by State – Visualizes sales distribution geographically.
- Stacked Bar Chart - Quantity by Size & Category – Compares sales across different product sizes.

## Insights & Findings
- Majority of Orders Are Shipped – Most orders are successfully fulfilled, but cancellations also occur frequently.
- Expedited Shipping Trends – Some states show a higher preference for expedited shipping, which may indicate urgent purchase behavior.
- Regional Sales Variation – Maharashtra, Karnataka, and Tamil Nadu are among the top-selling states.
- B2B Transactions Are Minimal – The majority of sales come from individual consumers rather than business orders.
- Consistent Weekly Sales Trends – Sales volume remains stable, with occasional spikes in demand.
- Technical Highlights
- Data Preparation – Cleaned and structured raw sales data before visualization in Tableau.
- Interactive Features – Filters and dynamic category selection enhance user experience.
- Visual Encoding – Used color coding and chart types to improve interpretability.

TABLEAU SCREENSHOT
<img width="1327" alt="Picture 2025-03-14 at 2 12 57 PM" src="https://github.com/user-attachments/assets/10728e15-fa40-40c3-a00b-65d7adb7e64c" />
