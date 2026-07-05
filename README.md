# Supply-Chain-Analytics
Supply Chain BI Project — 118,310 orders analyzed using Excel Power Query and Power BI

# Supply Chain Analytics Dashboard
### Brazilian E-Commerce Network — 118,310 Orders Analyzed

## Project Summary
End-to-end supply chain analysis built with Excel Power Query 
ETL, Power BI Star Schema, 9 DAX measures, and a 3-page 
interactive dashboard identifying ₹2.37M in freight leakage 
and 126-day delivery failures.

## Key Metrics
| Metric | Value |
|--------|-------|
| Total Revenue | ₹16.64M |
| Total Orders | 99,000 |
| Worst Delivery Delay | 126 days — Novo Brasil,ES |
| Total Freight Cost | ₹2.37M (14.24% of revenue) |
| Late Delivery Rate | 7.66% |
| Avg Review Score | 4.03 out of 5 |
| Revenue Growth | 168x from 2016 to 2018 |

## Key Findings
- Novo Brasil,ES records 126-day average delivery delay
- Freight costs consuming 14.24% of total revenue
- Credit Card = 67.2% of all payments (₹12.78M)
- São Paulo = 13.8% of total network revenue (₹2.27M)
- Revenue grew from ₹53K in 2016 to ₹8.96M in 2018

## What I Built
- Excel Power Query ETL pipeline
- 7 raw CSV tables cleaned and merged into FactOrders_Clean
- Star Schema with 6 active Many-to-One relationships
- 9 custom DAX measures for business KPIs
- 3-page interactive Power BI dashboard
- 6 Excel pivot tables with conditional formatting

## Dashboard Pages
1. Executive Overview — KPIs, Revenue trends, Regional analysis
2. Supply Chain Performance — Delivery delays, Seller analysis
3. Financial Impact — Freight breakdown, Payment analysis

## Tools Used
- Microsoft Excel — Power Query ETL
- Power BI Desktop — Star Schema, DAX, Dashboard
- Dataset: Brazilian E-Commerce Olist (Kaggle)

## Data Pipeline
9 Raw CSV Files
→ Power Query Cleaning and Merging
→ FactOrders_Clean Master Table (118,310 rows)
→ Star Schema in Power BI (6 relationships)
→ 9 DAX Measures
→ 3-Page Interactive Dashboard
→ Business Insights and Recommendations

<img width="1325" height="748" alt="DASHBOARD 1" src="https://github.com/user-attachments/assets/d8f06209-4013-411b-a338-20c6e3949dac" />


<img width="1350" height="744" alt="DASHBOARD 2" src="https://github.com/user-attachments/assets/0903f0f1-5080-4599-8edb-13ce835bef1c" />


<img width="1331" height="747" alt="DASHBOARD 3" src="https://github.com/user-attachments/assets/e604ed9e-f76b-4d9f-a05f-35699d87d6c2" />

<img width="1691" height="733" alt="Star Schema screenshot" src="https://github.com/user-attachments/assets/ed9cb493-2fcc-4f49-8a3d-4c28ee412b46" />







