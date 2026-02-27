# Visualising and Cleaning Sales Data of a Restaurant
## Overview 
The goal of this project is to design an interactive dashboard that helps restaurant stakeholders track sales performance, customer paying behaviour and revenue trends from January 2022 to December 2023. 

Insights and recommendations are provided on the following areas:
- **Total revenue** and **Amount of dishes and drinks sold**
- **Customr payment methods**
- **Revenue by category**
  
The original dataset, cleaned dataset, pivot tables and dashboard can all be found [here](https://github.com/dtan20441/portfolio_restaurant_sales/blob/main/restaurant_sales_data.xlsx).

Here is a snapshot of the dashboard: ![restaurant dashboard](https://github.com/dtan20441/portfolio_restaurant_sales/blob/main/restaurant_dashboard.png)

## Data structure
The dataset consists of 1 table with 17,535 rows.
![Image of dataset](https://github.com/dtan20441/portfolio_restaurant_sales/blob/main/restaurant_schema.png)

## Process
1. **Data cleaning**: Item names and prices were missing, with some of the empty values being resolved using known information. Some inconsistent formats, such as "Beef Chili" and "Beef Chilli".
2. **Visualisations from Pivot Tables**: 
- Line chart for revenue trend.
- Horizontal bar chart for top performing menu items.
- Pie chart for payment method distribution.
- Vertical bar chart for category-level revenue contribution.
3. **KPI cards**: Created dynamic KPI cards (Average Order Value, Count of Orders, Total Revenue) using Pivot Tables.
4. **Dashboard design**: Applied consisting formatting, colours and visualisation placements for a professional appearance.

## Insights and Recommendations
### Total revenue and amount of dishes and drinks sold
- Between January 2022 and December 2023, total revenue declined by 4.7%, alongside a $0.45 decrease in average order value (AOV). Sales were heavily driven by main dishes, which accounted for all items within the top five best-selling products, indicating limited purchases for categories.
- To improve revenue performance and increase sales across other categories, bundled offerings should be introduced (e.g. pairing a main dish with a dessert or drink). This strategy can encourage multi-item purchases, increase average order value, and diversify revenue beyond main dishes.

### Customer payment methods
- Payment methods are evenly distributed across cash, card, and digital wallet transactions, indicating a diversified and balanced transaction ecosystem. 
- Maintain support for all payment methods to minimise transaction friction and ensure accessibility across customer segments.

### Revenue by category
- Main dishes contribute 47.1% of total revenue, while drinks generate the smallest share at 6.7%, indicating limited revenue contribution from beverage sales.
- Further review shows that no alcoholic beverages are currently offered. Given that alcoholic drinks typically carry higher profit margins and increase average order value, this represents an opportunity to expand the drinks category by introducing premium-priced alcoholic options.
- Expanding the drinks menu may improve category revenue diversification and support overall revenue growth through complementary purchases alongside main dishes.

 
