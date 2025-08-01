 🚗 InsightDrive: Vehicle Service Dashboard

 📘 Overview
**InsightDrive** is a Power BI dashboard created to analyze and visualize vehicle service data. Built using 60 real-world service records, this project offers deep insights into service trends, technician performance, revenue analysis, and customer behavior. It's designed to empower technicians, managers, and analysts with actionable metrics.

---

 📊 Dataset Information
File: `VehicleServiceData.txt`  
Records: 60 vehicle service entries  
Fields:
- `ServiceID`, `CustomerName`, `VehicleType`, `ServiceType`, `TechnicianName`
- `StartTime`, `EndTime`, `ServiceDuration`, `ServiceCost`, `CustomerRating`
- `IssuesReported`, `PartsUsed`, `PaymentMethod`

---

⚙️ Features
- KPI Cards: Total Services, Avg. Rating, Revenue
- Visuals:
  - Donut Chart – Payment Method Distribution  
  - Bar Chart – Vehicle Type Counts  
  - Column Chart – Avg. Service Cost by Type  
  - Line Chart – Daily Volume Trends  
  - Table – Technician Performance Summary  
- Calculations:
  - `Technician Score = AVERAGE(CustomerRating) - (SUM(ServiceDuration)/60)`
- Interactivity:
  - Drill-through pages (Technician detail)  
  - Slicers for date, vehicle type, and technician  
  - Custom tooltips for deeper insight

---

🎯 Goals
- Understand service flow and demand patterns  
- Compare technician performance and customer ratings  
- Monitor payment method preferences  
- Track revenue across service categories  
- Enhance operational decision-making through dynamic visuals

---

💻 Setup
1. Open `InsightDrive.pbix` in Power BI Desktop  
2. Review and explore dashboard tabs  
3. Use slicers and tooltips for deeper insights  
4. Customize visuals or expand dataset as needed

---
[!img url]()
