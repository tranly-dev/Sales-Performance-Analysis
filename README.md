# Sales-Performance-Analysis
Real-time key metrics: $1.07B revenue, $451M profit, 73K orders, 13M units, 42.2% margin. Features revenue by country, product line donut chart, 2016-2018 profit/revenue trend, top sales managers leaderboard. Fully filterable &amp; responsive.
# Sales Performance Analysis Dashboard – Power BI

![Preview](https://via.placeholder.com/800x400.png?text=Sales+Performance+Dashboard+Preview)  
*(Replace the link above with your actual dashboard screenshot)*

## Background
A global consumer electronics & lifestyle retailer operates in **14 countries** across North America, Europe, Asia, Latin America, and Oceania from **2016 to 2018**.  
The company offers five main product lines:  
- Video Games  
- Mobile  
- Computer  
- Home & Kitchen  
- Books  

With over **72,000 transactions** generated through multiple sales channels (Web, Telephone, E-mail, Sales visit, Fax, etc.), leadership required a single, interactive source of truth to monitor performance in real time.

## Objective
Deliver an executive-level Power BI dashboard that enables stakeholders to:  
- Monitor key metrics: **$1.07B+ revenue**, **$451M+ profit**, 73K orders, 13M units sold, 42.2% gross margin  
- Analyze performance by Country, Region, Product Line, Order Method, and Sales Manager  
- View multi-year trends (2016–2018) and YoY growth  
- Identify top-performing sales managers via dynamic leaderboard  
- Explore data instantly using interactive slicers and filters  

## Dataset Overview
The project includes four clean Excel files:

| File                     | Description                                           | Rows     |
|--------------------------|-------------------------------------------------------|----------|
| `4.SalesManagement.xlsx` | Fact table – all transactions (Country, Order method, Product line/type, Date, Quantity, Price, Revenue, Unit Cost) | 72,704   |
| `2.Region.xlsx`          | Dimension – Country → Region mapping                  | 15       |
| `1.SalesManagers.xlsx`   | Dimension – Country → Sales Manager mapping           | 15       |
| `3.Dates.xlsx`           | Full Date table (Excel serial dates: 42370 → 43830)   | ~1,500+  |

