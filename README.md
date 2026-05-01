---

# Global Electronics Retailer – 360° Sales Analysis  
**SQL → Python → Power BI | Actionable Insights with $7M+ Potential**

## Project Overview
Analysed 5+ years of sales transactions for a global electronics retailer. I built a clean relational database, performed exploratory analysis in Python, and designed an interactive Power BI dashboard that uncovers growth opportunities worth over **$7M annually**.

## Tools & Technologies
- **SQL (MySQL)** – Data ingestion, cleaning, constraints, quality checks  
- **Python (pandas, matplotlib)** – Merging, revenue/currency logic, trend analysis  
- **Power BI** – Dashboard with DAX measures, 5‑page drill‑through

## Data Pipeline
1. **Raw Data Load**  
   Loaded 5 CSV files into MySQL with `LOAD DATA INFILE`.  
   <img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/99474e35-65a5-4410-a748-fbe81f6e9a9f" />
   <img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/31245e7c-6e2a-4c9f-8820-fe7e0bc214ac" />

2. **Cleaning & Standardisation**  
   Parsed dates, deduplicated customers, cast prices from text to decimal.  
   <img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/cfba3b7b-5432-44d6-8975-413ef12cdd31" />

3. **Relational Model**  
   Added primary/foreign keys to ensure referential integrity.  
   <img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/413edd34-306c-4408-b77b-a573ae27b535" />

4. **Currency Unification**  
   Verified all currency codes exist in exchange rates (zero mismatches).  
   <img width="1920" height="1080" alt="7" src="https://github.com/user-attachments/assets/b3b7c539-55e8-43e7-b0af-72423df5d693" />
   Converted non‑USD revenues (CAD, GBP, EUR, AUD) to USD in Python, preserving original values.  
   <img width="1920" height="1080" alt="17" src="https://github.com/user-attachments/assets/2301a82b-2e9a-4312-9e62-b9c6153b72b6" />

5. **Feature Engineering**  
   Examined nulls and data types before merging and creating `revenue`, `delivery_days`, and `channel`.  
   <img width="1920" height="1080" alt="13" src="https://github.com/user-attachments/assets/0d41a5d1-2bca-4468-b3ec-605756e6eb0d" />

6. **Power BI Modelling**  
   Built a star schema and implemented DAX measures for Total Revenue, AOV, Avg Delivery Days, and Revenue by Channel.  
   <img width="1920" height="1080" alt="26" src="https://github.com/user-attachments/assets/b39e4dae-97df-4c1a-9d96-e99dd76c0ef3" />

## Key Insights
- **Seasonal Revenue Dip**  
  Revenue peaks in December/January but crashes every **April** to ~$0.5M (monthly average: $3.5M).  
  <img width="1920" height="1080" alt="20" src="https://github.com/user-attachments/assets/fc4332dc-9d88-4797-8865-4230af63cf8c" />

- **Delivery Time Improvement**  
  Average delivery days dropped from **7.3 (2016) to 3.8 (2021)**. Slight slowdown in May & October.  
  <img width="1920" height="1080" alt="22" src="https://github.com/user-attachments/assets/6bbebbfd-9d50-45a4-ace2-42cccf8d6055" />

- **Online vs. In‑Store AOV**  
  Online AOV ($697) is nearly equal to in‑store ($717), but online contributes only **20.7% of revenue**.  
  <img width="1920" height="1080" alt="22" src="https://github.com/user-attachments/assets/ec5e57b9-a840-4ae8-89ef-59499e941e47" />


## Power BI Dashboard
A 5‑page interactive report (slicers for Country, Category, Channel):

- **Executive Overview** – KPIs, revenue by channel pie chart, monthly revenue trend  
  <img width="1920" height="1080" alt="27" src="https://github.com/user-attachments/assets/7a286c9a-e24d-41b2-a0cb-4c2a5b46cb1d" />

- **Product Analysis** – Top products, revenue share by category  
  <img width="1920" height="1080" alt="28" src="https://github.com/user-attachments/assets/a2392317-c4f6-41ec-a1f3-a5928814cae0" />

- **Operations** – Delivery time trend and average delivery days by month  
  <img width="1920" height="1080" alt="30" src="https://github.com/user-attachments/assets/7c375e1f-dac0-4477-ad82-08f3df37d7d6" />

- **Recommendations** – Quantified action plan  
  <img width="1920" height="1080" alt="31" src="https://github.com/user-attachments/assets/4a75faed-2066-4c02-8f17-a8d9148f27ec" />

## Recommendations (Quantified Impact)
1. **Scale Online Channel** – 5% shift from in‑store → **+$2M**  
2. **Focus on Core Categories** – 10% growth in Computers & Cell Phones → **+$2.2M**  
3. **Eliminate April Dip** – Seasonal Q2 promotions → **+$3M annually**  
4. **Expand in France & Netherlands** – Targeted marketing → **+$0.75M**  
5. **Optimise Peak‑Month Logistics** – Pre‑position stock in May/October → higher retention

---
