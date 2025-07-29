# Manufacturing Operations Analysis (Excel)

## Business Context

ElectroniTech Manufacturing Co. is a leading company in the manufacturing and distribution of electronic components. The company has a diverse clientele ranging from large-scale wholesalers to small retail businesses, and it operates across multiple manufacturing sites and regional offices. 

As the company expands, it faces challenges in managing its increasing volume of data related to customers, employees, shipments, and financial transactions. Efficient handling and analysis of this data are crucial for maintaining operational excellence, customer satisfaction, and financial health.

## Objective

The project aims to analyze ElectroniTech Manufacturing Co.'s operational datasets to gain insights into:

- Customer behavior
- Employee efficiency
- Shipment logistics
- Financial transactions

All analysis was done using Microsoft Excel to identify trends, inefficiencies, and areas for improvement. This includes:
- Data cleaning and integration
- Customer and employee performance analysis
- Shipment tracking and categorization
- Financial analysis
- Dashboard creation to visualize KPIs

The end goal is to provide insights for a data-driven decision-making and enhance the company's operational efficiency and overall customer satisfaction.

---

## Dashboards

### 1. Customer Insights Dashboard

- **Metrics**: Total customers, Average Membership Duration
- **Excel Techniques**:
  - Formulas for Customer Segmentation
  - Pivot Tables & Charts

![Customer Insights Dashboard](image/Customer%20Insights%20Dashboard.png)

---

### 2. Financial Health Dashboard

- **Metrics**: Total payment amount, Outstanding payment amount, Received payment amount.
- **Excel Techniques**:
  - Pivot Tables with Slicers
  - GETPIVOTDATA for data referencing 

![Financial Health Dashboard](image/Financial%20Health%20Dashboard.png)

---

### 3. Shipment Overview Dashboard

- **Metrics**: Total shipments, average weight, shipment efficiency, Days to deliver.
- **Excel Techniques**:
  - Efficiency metric calculated using custom formulas (Weight/Charges)
  - Stacked Column Charts (Service Type vs Domain)
  - Dynamic Slicers for Domain and Status
  - Pivot Tables

![Shipment Overview Dashboard](image/Shipment%20Overview%20Dashboard.png)

---

## Excel Techniques & Features Used

-  **Conditional Formatting**: For shipment weight categorization (Heavy/Light), delivery delays, etc.
-  **Customer Segmentation**: Segmented customers using:Total Payment (High, Medium, Low) & Membership Duration (days)
-  **Dynamic Named Ranges**: Used to calculate average payment dynamically by mode (CARD, COD)
-  **Conditional Formatting** Highlighted entire rows for shipments where Weight > 500 units
-  **Pivot Tables**: Summarized metrics across domains, types, and segments.
-  **VLOOKUP/XLOOKUP**: Used for merging datasets like Payment Details with Customer or Membership data.
-  **Array Formulas**: For calculating various metrics.
-  **Calculated Columns**: For metrics like membership duration, shipment efficiency, and customer segmentation.
-  **Slicers & Timelines**: For better interactivity across dashboards.
-  **Charts**: Pie charts, bar charts, stacked column, and combined metric visualizations.

---


