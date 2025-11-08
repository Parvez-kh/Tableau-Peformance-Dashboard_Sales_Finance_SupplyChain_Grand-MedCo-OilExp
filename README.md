# Tableau-Peformance-Dashboard_Sales_Finance_SupplyChain_Grand-MedCo-OilExp
This project visualizes **5 years of business performance data** across **Finance**, **Sales**, functions.   Built in **Tableau**, it showcases key KPIs such as Sales Growth, Profit Margins, OTIF, and Forecast Accuracy — providing a unified performance view for decision-makers.
### 🗂️ Dataset
**Source:** Internal business data (2019–2024)  
**Records:** ~50,000 orders  
**Key Columns:**
- Order Date, Country, Customer Type, Product, Sales, Cost, Profit, OTIF, Forecast Vol, Operating Profit  
- Finance metrics include SP/L, CP/L, Margin/L, Transport & Storage Cost  

---

### 🧮 Dashboards Included

#### 1️⃣ Finance Dashboard
**KPIs:**
- YTD Sales, Profit, Cost, Volume vs LY vs Target  
- Margin %, YOY Growth, CAGR  
-- Operating Profit vs Operating Margin (%)  

**Visuals:**
- Bullet charts for Actual vs Target  
- Dual-axis combo chart for Profit vs Margin%  
- KPI cards with ▲▼ trend icons  

---

#### 2️⃣ Supply Chain Dashboard
**KPIs:**
- YTD Sales, Cost, Volume vs LY vs Target  
- OTIF %, Forecast Accuracy, Forecast Bias  
- Average Delivery Days, Inventory Turnover, Carrying Cost  

**Visuals:**
- Line charts for Monthly Orders Trend  
- Bar charts for Forecast vs Actual (DFA)  
- Box plot for Delivery Days  
- KPI indicators for OTIF % and Forecast Bias  

---

#### 3️⃣ Sales Dashboard
**KPIs:**
- YTD Sales & Profit vs Target  
- YOY Growth %, 
- Market, Industry, and Customer Order Type Analysis  
- Product Mix, Channel & Salesperson Performance  

**Visuals:**
- Pareto chart for top industries/customers  
- Map for regional market share  
- Bar chart for Salesperson ranking  

---

### 🧩 Features
- 📈 Dynamic **Top N filter** (parameter-based) for flexible analysis  
- 🔺🔻 **Color-coded trend icons** to highlight improvement/decline  
- 🧮 **YTD, YOY, and CAGR calculations** using table & LOD expressions  
- 🔁 Rolling averages for quick trend comparison  
- 🎨 Unified, color-coded design for cross-dashboard consistency  

---

| Finance Dashboard | Supply Chain Dashboard | Sales Dashboard | New Dashboard |
|------------------|----------------------|----------------|----------------|
|  ![Dashboard Overview](Images/New_Dashboard.png) |![Finance](Images/Finance_Dashboard.png) | ![Supply Chain](Images/SupplyChain_Dashboard.png) | ![Sales](Images/Sales_Dashboard.png) | ![Dashboard Overview](Images/New_Dashboard.png) |


---

### 📊 KPI Definitions
| KPI | Description |
|------|--------------|
| **YTD Sales** | Total sales for current year up to today |
| **YOY Growth** | (This Year Sales – Last Year Sales) / Last Year Sales |
| **CAGR** | Compound Annual Growth Rate of Sales over 5 years |
| **OTIF %** | On-Time In-Full delivery performance |
| **Forecast Bias** | Forecast – Actual Volume |
| **Margin %** | (Sales – Cost) / Sales |
| **Operating Margin %** | Operating Profit / Sales |

