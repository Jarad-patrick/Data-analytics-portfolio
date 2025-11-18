E-Commerce Sales Analysis Dashboard (Power BI)

The company wants to understand how its sales are performing across different months, products, and customer segments.  
Management needs insights into revenue, profit, best-selling products, and overall business trends to make decisions that increase growth.

---

 Dataset
**File:** ecommerce_sales_data.csv
**Rows:** -5,000  
**Columns:**  
- `OrderID`  
- `OrderDate`  
- `CustomerName`  
- `Segment`  
- `Category`  
- `ProductName`  
- `Quantity`  
- `UnitPrice`  
- `Discount`  
- `Profit`  
- `Region`

---

Tasks performed
1. Data Cleaning
- Converted `OrderDate` to proper date format  
- Created new columns:  
  - Revenue = Quantity × UnitPrice  
  - Month = FORMAT(OrderDate, "MMM")  
  - Year  
- Removed missing or invalid records  

2. Exploratory Data Analysis
Looked at:
- Sales trends by month  
- Best-selling product categories  
- Profitability across segments  
- Top customers by revenue  

3. Power BI Dashboard Development
Created interactive visuals:
- Revenue by Month  
- Sales by Category  
- Profit by Segment  
- Top 10 Customers  
- Region-wise Sales Map  
- Overall KPIs (Revenue, Profit, Total Orders, Avg Order Value)

---

 Insights / Findings
- Revenue peaked in November, likely due to promotional seasons.  
- Technology category generated the highest revenue.  
- Corporate segment provided steady high-profit margins.  
- Top 10 customers contributed nearly **30% of total revenue**.  
- East region had the strongest performance overall.

---

  Recommendations
- Increase stock and marketing for high-selling Technology items.  
- Offer loyalty programs for top customers.  
- Target the Consumer segment to improve profit margins.  
- Focus campaigns on the East region for maximum ROI.

---

 Tools & Skills Used
- Power BI (Dashboard, DAX, data modeling)   
- Data Visualization 
- Business Analytics

---

  Files in This Project
- Ecommerce_Sales_Dashboard.pbix — Interactive dashboard  
- data/ecommerce_sales_data.csv — Dataset  
- README.md — Documentation (this file)

---

 📸 Dashboard Preview
*(Add screenshot here after publishing your Power BI dashboard)*

---

