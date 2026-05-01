Global Electronics Retailer – 360° Sales Analysis
SQL → Python → Power BI | Actionable Insights with $7M+ Potential

Project Overview
Analysed 5+ years of sales transactions for a global electronics retailer. I built a clean relational database, performed exploratory analysis in Python, and designed an interactive Power BI dashboard that uncovers growth opportunities worth over $7M annually.

Tools & Technologies
SQL (MySQL) – Data ingestion, cleaning, constraints, quality checks

Python (pandas, matplotlib) – Merging, revenue/currency logic, trend analysis

Power BI – Dashboard with DAX measures, 5‑page drill‑through

Data Pipeline
Raw Data Load
Loaded 5 CSV files into MySQL with LOAD DATA INFILE.
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/1148d2f3-4048-45e4-bf31-8fb6da67499f" />
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/b9d49e3d-9867-4369-a2b9-ab5870c93115" />

Cleaning & Standardisation
Parsed dates, deduplicated customers, cast prices from text to decimal.
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/f7459c4d-c6ea-4745-bf03-30cdb49e1885" />

Relational Model
Added primary/foreign keys to ensure referential integrity.
<img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/dd13c13d-6fbb-48ab-a239-9123ff2bf30e" />

Currency Unification
Verified all currency codes exist in exchange rates (zero mismatches).
<img width="1920" height="1080" alt="7" src="https://github.com/user-attachments/assets/9b744fe9-785e-4337-bc76-3a62fcf08a95" />
Converted non‑USD revenues (CAD, GBP, EUR, AUD) to USD in Python, preserving original values.
<img width="1920" height="1080" alt="17" src="https://github.com/user-attachments/assets/94aefd29-a5fc-42a3-b174-339d9b61a635" />

Feature Engineering
Examined nulls and data types before merging and creating revenue, delivery_days, and channel.
<img width="1920" height="1080" alt="13" src="https://github.com/user-attachments/assets/286df6df-178c-496b-a684-760c9ccece69" />

Power BI Modelling
Built a star schema and implemented DAX measures for Total Revenue, AOV, Avg Delivery Days, and Revenue by Channel.
<img width="1920" height="1080" alt="26" src="https://github.com/user-attachments/assets/19711b48-1e3c-4501-9ad3-bcdbb8d0c372" />

Key Insights
Seasonal Revenue Dip
Revenue peaks in December/January but crashes every April to ~0.5M (monthlyaverage:3.5M).
<img width="1920" height="1080" alt="20" src="https://github.com/user-attachments/assets/e4219d53-1bdd-427d-a6fe-0554d1e7b633" />

Delivery Time Improvement
Average delivery days dropped from 7.3 (2016) to 3.8 (2021). Slight slowdown in May & October.
Online vs. In‑Store AOV
Online AOV (697) is nearly equal to in‑store(717), but online contributes only 20.7% of revenue.
<img width="1920" height="1080" alt="22" src="https://github.com/user-attachments/assets/34a2b2ca-6be6-4488-b3c7-404bda550c65" />

Power BI Dashboard
A 5‑page interactive report (slicers for Country, Category, Channel):
Executive Overview – KPIs, revenue by channel pie chart, monthly revenue trend
<img width="1920" height="1080" alt="27" src="https://github.com/user-attachments/assets/16525daa-fbe6-4211-af75-3e9f009a73f2" />

Product Analysis – Top products, revenue share by category
<img width="1920" height="1080" alt="28" src="https://github.com/user-attachments/assets/46f5d9ae-a837-4df5-84cc-e97055bf2766" />

Operations – Delivery time trend and average delivery days by month
<img width="1920" height="1080" alt="30" src="https://github.com/user-attachments/assets/e774552c-3894-4b65-a605-346ddc06cca0" />

Recommendations – Quantified action plan
<img width="1920" height="1080" alt="31" src="https://github.com/user-attachments/assets/8892cddc-60a9-4fb2-82a2-bfa9f554a8b8" />

Recommendations (Quantified Impact)
Scale Online Channel – 5% shift from in‑store → +$2M

Focus on Core Categories – 10% growth in Computers & Cell Phones → +$2.2M

Eliminate April Dip – Seasonal Q2 promotions → +$3M annually

Expand in France & Netherlands – Targeted marketing → +$0.75M

Optimise Peak‑Month Logistics – Pre‑position stock in May/October → higher retention







































