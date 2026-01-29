# 📊 End-to-End Supply Chain & Logistics Analytics Dashboard (Power BI)

##  Project Overview

This project is an **end-to-end Supply Chain & Logistics Analytics dashboard** built using **Power BI**.  
It covers the complete business flow — **Suppliers → Manufacturing → Shipment → Customers** — and connects multiple departments into a single analytical view.

The objective of this project was not just to visualize data, but to **analyze operational performance, identify inefficiencies, and support data-driven decision-making** in a realistic enterprise setup.

---

##  Business Objectives

This dashboard was designed to answer key business questions such as:

- How much revenue and profit is the supply chain generating?
- Are suppliers reliable in terms of cost, quality, and lead time?
- Are manufacturing facilities operating efficiently?
- Where are shipment delays and logistics costs coming from?
- Which customers and sales channels are driving profitability?

---

## Data Model

The project follows a **star schema**, ensuring clarity, performance, and scalability.

### Dimension Tables
- `dim_customer` – customer details, country, channel type  
- `dim_product` – product category, pricing, cost  
- `dim_supplier` – supplier tier, location, quality score  
- `dim_facility` – manufacturing and logistics facilities  
- `dim_date` – calendar table for time-based analysis  

### Fact Tables
- `fact_procurement` – procurement cost, lead time, quality  
- `fact_production` – units produced, defective units  
- `fact_inventory` – stock and inventory levels  
- `fact_shipment` – shipment quantity, delivery delay, shipping cost  
- `fact_sales` – revenue, profit, quantity sold  


---

##  Executive Overview

A high-level snapshot of the entire supply chain performance.

### Key Metrics
- **Gross Revenue:** ₹186.86M  
- **Total Revenue:** ₹176.95M  
- **Total Profit:** ₹48.56M  
- **Profit Margin:** 27%  
- **Perfect Order Rate:** 75%  
- **Total Shipments:** ~8K  

### Outcome
The business is profitable overall, but the **perfect order rate highlights operational gaps** across procurement, manufacturing, and logistics stages.

---

##  Supplier Overview (Procurement Analysis)

### Key Metrics
- **Total Procurement Cost:** ₹78.13M  
- **Total Order Quantity:** 129K units  
- **Average Lead Time:** 11.53 days  
- **Average Quality Score:** 96.63  
- **On-Time Delivery Rate:** 15%  

### Observations
- Procurement cost is fairly distributed across major suppliers (₹10–11M each).
- Supplier quality remains consistently high.
- On-time delivery performance is low despite good quality, indicating **lead-time inefficiencies rather than quality issues**.
- Procurement costs show a declining trend, suggesting improved cost control.

### Conclusion
Supplier quality is strong, but **delivery reliability and lead-time optimization** should be the primary focus for improvement.

---

## Manufacturing Overview (Operations Analysis)

### Key Metrics
- **Total Units Produced:** ~4M  
- **Defective Units:** ~24K  
- **Defect Rate:** ~1%  
- **Average Daily Production:** ~5.26K units  
- **Capacity Utilization:** ~90%  

### Observations
- Facilities are operating at high capacity, indicating efficiency but also potential risk.
- Defect rate is low overall, showing strong quality control.
- Certain products generate higher defects relative to output, pointing to **product-specific quality risks**.
- Production volume shows a gradual downward trend over time.

### Conclusion
Manufacturing operations are efficient but **operating close to capacity limits**, which could lead to bottlenecks if demand increases.

---

##  Shipment Overview (Logistics Analysis)

### Key Metrics
- **Total Shipments:** ~8K  
- **Total Shipped Quantity:** ~3M units  
- **Total Shipping Cost:** ₹19.42M  
- **Average Delivery Time:** 14.19 days  
- **On-Time Delivery Rate:** 15%  

### Observations
- Smartphones account for the largest share of shipment volume (~55%).
- Shipping costs show a declining trend, indicating cost optimization.
- Delivery performance varies significantly across customers and carriers.
- Some carriers contribute disproportionately to delays.

### Conclusion
While logistics costs are improving, **delivery reliability remains a major concern** and directly impacts customer satisfaction.

---

##  Customer Overview (Sales & Profitability)

### Key Metrics
- **Total Revenue:** ₹176.95M  
- **Total Quantity Sold:** 187K units  
- **Total Profit:** ₹48.56M  
- **Profit Margin:** 27%  
- **Average Order Value:** ₹20.82K  

### Observations
- Online and retail channels together contribute over 80% of total revenue.
- Revenue is concentrated among a few large customers, increasing dependency risk.
- Smartphones generate the highest sales volume, but not necessarily the highest margins.
- Sales trend shows a gradual decline, indicating potential demand slowdown.

### Conclusion
Revenue remains strong, but the business should focus on **margin optimization and customer diversification**.

---
