🚚 Fleet Performance & Delivery Efficiency Dashboard


📌 Overview

A Power BI dashboard analyzing fleet performance, delivery efficiency, fuel usage, and operational costs for a logistics company. The goal is to help stakeholders make data‑driven decisions and identify inefficiencies.

 
🗂️ Dataset Includes:

Trip details
Vehicle master data
Drivers
Fuel consumed
Maintenance cost
Distance traveled
Delivery status

 
🧹 Data Preparation

Removed duplicate and blank records
Standardized data types
Imputed missing fuel values for late deliveries (avg = 91.57 L)
Created relationship: Trip_Data[Vehicle_ID] → Vehicle_Master[Vehicle_ID]


🧮 Key DAX Measures

Fuel Efficiency = Distance / Fuel Consumed
On‑Time Delivery % = On‑Time Trips / Total Trips
Cost per Km = (Fuel Cost + Maintenance Cost) / Distance


📊 Dashboard Features

Slicers: Vehicle Type, Driver ID, Destination
KPI Cards: Fuel Efficiency, On‑Time Delivery %, Cost per Km
Bar chart: On‑Time Delivery by Destination
Line chart: Fuel Efficiency Trend
Pie chart: Maintenance Cost by Vehicle Type
Key Influencers: Factors affecting delivery delays
Decomposition Tree: Cost per Km breakdown


✅ Insights 

Driver D03 shows higher on‑time delivery rates
Trucks have higher maintenance cost but strong efficiency
Delivery performance varies significantly by city
Cost per km differs across vehicle types


🏁 Conclusion

The dashboard provides a clear view of fleet operations, helping optimize vehicle usage, reduce costs, and improve delivery reliability.
