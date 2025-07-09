
## Super Store Sales Dashboard

An interactive Power BI dashboard analyzing a year’s worth of orders and revenue for a national superstore. This dashboard uncovers top‑performing categories, shipping efficiencies, regional strengths, and 21‑day sales forecasts—equipping stakeholders with data‑driven insights to optimize marketing, logistics, and inventory.

---

### 📂 Dataset  
- **Source**: `Super_Store_Sales_Dataset.csv`  
- **Records**: 51,690 orders  
- **Time span**: January 2019 – January 2021  
- **Key fields**: Order Date, Category, Sub‑Category, State, Segment, Ship Mode, Sales, Quantity, Profit

---

### 📊 Key Metrics (Dashboard Summary)  
- **Total Sales**: ₹ 1.57 M  
- **Total Orders**: 22 K  
- **Total Profit**: ₹ 175.26 K  
- **Average Shipping Time**: 4 days  

---

### 🔍 Major Findings  

1. **Category Performance**  
   - **Office Supplies** leads with ₹ 0.64 M in sales  
   - **Furniture** follows at ₹ 0.47 M  
   - **Technology** contributes ₹ 0.45 M  

2. **Top Sub‑Categories**  
   - Phones: ₹ 0.20 M  
   - Chairs: ₹ 0.18 M  
   - Binders: ₹ 0.17 M  

3. **Shipping Modes**  
   - Standard Class accounts for ₹ 0.91 M (58% of sales)  
   - Second Class: ₹ 0.31 M  
   - First Class: ₹ 0.24 M  
   - Same Day: ₹ 0.10 M  

4. **Customer Segments**  
   - Consumer: 48% of revenue  
   - Corporate: 33%  
   - Home Office: 19%  

5. **Payment Methods**  
   - Cash on Delivery: 43%  
   - Online Payment: 35%  
   - Credit/Debit Cards: 22%  

6. **Regional Highlights**  
   - **California**: ₹ 0.34 M  
   - **New York**: ₹ 0.19 M  
   - **Texas**: ₹ 0.12 M  

---

### 📈 Sales Forecast (Next 21 Days)  
Using built‑in Power BI forecasting:
- Forecast peaks at **₹ 10.6 K** around January 2021  
- Identifies potential dips to **₹ 0.2 K** in off‑peak windows  

---

### 🛠 How to Use This Dashboard  
1. Open `Super_Store_Sales_Dashboard.pbix` in Power BI Desktop (tested on version 2.XX).  
2. Refresh the data source if you update the CSV.  
3. Explore filters for:  
   - Date ranges (monthly, quarterly)  
   - Category & Sub‑Category slicers  
   - State/Region map interactions  
   - Segment and Ship Mode breakdowns  
4. View the “Forecast” page for 21‑day projections and confidence intervals.

---

### 🔧 Technologies  
- **Power BI Desktop** for data modeling, visualization, and forecasting  
- **DAX** measures for dynamic KPIs  
- **Map visual** using Bing Maps integration  

---

### 📌 Next Steps  
- Integrate real‑time data source (e.g., SQL database) for live updates  
- Extend forecasting to longer horizons with Python/R scripts via Power BI  
- Build an automated email report for daily/weekly KPI summaries  

---

> All metrics and visuals are based on the real sales dataset of 51,690 orders and reflect actual performance and forecasts.  
