E-Commerce Analytics Dashboard – Onyx DataDNA Challenge (Nov 2025)
==================================================================

Overview
--------
This dashboard was developed as part of the Onyx DataDNA November 2025 Challenge, focused on analyzing an E-Commerce dataset containing event-level sales, customer, and product information. 
The objective was to design an interactive and insight-driven Power BI report that highlights key business metrics such as revenue realization, order performance, product trends, and channel contributions.

Dashboard Link Coming Soon...

Dataset
-------
The project uses three primary tables:
- **Events:** Order, revenue, and transactional details  
- **Customers:** Demographics, acquisition channels, and regional information  
- **Products:** Product categories, pricing models, and subscription details  

A custom **Dates table** was created using DAX to support time intelligence, fiscal periods, and proper month-year sorting.

Key Measures (DAX)
------------------
The report includes a comprehensive measure layer to track performance and comparisons:
- Total Revenue USD  
- Total Order Value USD  
- Total Orders  
- Total Customers  
- Revenue Per Customer  
- Month-over-Month (MoM %) and Year-over-Year (YoY %) growth  
- Previous Month Revenue and Previous Month Orders  
- Total Quantity Ordered, Total Quantity Sold, and Total Products  
- Progress and share metrics: Filtered % of Total Revenue, Remaining % of Total Revenue  
- Validation flags: Has Data, Has Data 2  

Dashboard Pages
---------------
1. Executive Summary
   - **KPI Cards:** Total Revenue USD, Total Customers, Total Events, Products, and Total Quantity Sold  
   - **Revenue Realization Chart:** Line chart comparing Total Order Value USD vs Final Revenue USD by month  
   - **Cash Flow Drivers:** Donut chart showing Annual vs Monthly vs One-time billing contributions  
   - **Resale Model Breakdown:** Donut chart comparing Direct Resale, Marketplace, and Affiliate revenue  
   - **Top 10 Products:** Matrix table displaying highest revenue-generating products  
   - **Order Drivers:** Column chart showing which channels drive the most orders  
   - **Floating Insight Ticker:** Continuous HTML text bar summarizing key insights  
   - **Filter Slicers:** Date slicers and “Is Refunded” filter  

2. Product Performance
   - Displays key metrics such as Total Revenue, Total Orders, Monthly Revenue and Orders with previous month comparisons  
   - Highlights top-performing items such as Top Vendor, Category, and Product  
   - **Donut Chart:** Shows where most units are sold  
   - **Table Chart:** Displays product-wise vendor, orders, and revenue data  
   - **Hierarchical Bar Chart:** Category → Product Name showing order performance  
   - **Filter Slicers:** Date slicer, Country, and “Is Refunded” filter  

3. Customer Summary
   - **KPI Cards:** Total Customers and Total Revenue Generated  
   - **Donut Charts:** Channel-wise and age-wise customer distribution  
   - **Top 100 Customers Table:** Displays Customer ID, Country, Orders, Revenue (USD), and Quantity Sold  
   - **Map Visual:** Shows customer distribution by country and region (APAC, EU, LATAM, NA)  
   - **Column Chart:** Visualizes Total Customers or Revenue per Customer over time  
   - **Filter Slicers:** Date slicers and “Is Refunded” filter  

Floating Insight (HTML Marquee)
-------------------------------
A unique feature of the dashboard is a floating insight ticker created using the HTML Content visual with a custom DAX measure. 

DAX Code Snippet:

`FloatingInsightHTML =
"<marquee behavior='scroll' direction='left' scrollamount='8' style='font-family: Segoe UI; font-size:23px; color:#FFFFFF;'>
Revenue realization remains consistent with an average monthly revenue of about $515K against an average order value of $1.22M, indicating a strong conversion rate. 
| Organic channels continue to drive the highest orders (3,965), followed by Paid Search and Social. 
| Annual billing leads cash flow generation with $8.27M, showing strong long-term customer commitments. 
| Direct resale remains the primary source of revenue at $5.87M, while Marketplace and Affiliate models follow behind. 
| Microsoft 365 Business Standard Annual retains the top spot with $424K in revenue, supported by Azure AI Studio and Adobe product lines driving steady growth. 
</marquee>"`

Outcome
-------
This project demonstrates advanced DAX modeling, Power BI dashboard design, and storytelling skills for e-commerce analytics. 
The combination of interactive visuals, dynamic metrics, and a real-time floating insight ticker delivers a professional and engaging reporting experience.

Dashboard Pages
------

Executive Summary: 
<img width="1912" height="1079" alt="image" src="https://github.com/user-attachments/assets/bd674ed0-42e7-490b-9ed5-c42ca8582d9b" />

Product Summary: 
<img width="1916" height="1079" alt="image" src="https://github.com/user-attachments/assets/af09b94c-a9a4-46c2-88b7-bb78d298949f" />

Customers Summary: 
<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/3f1a7bf3-e9c4-4ac7-be7d-197a4e965c3c" />

Data Model
------
<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/6bcb473e-e40f-4cd0-8ab7-aa1de6986ebf" />

Figma Background: 
------
<img width="500" height="900" alt="image" src="https://github.com/user-attachments/assets/ee11090c-c4df-4546-bb42-db35cbde55d9" />
<img width="500" height="900" alt="image" src="https://github.com/user-attachments/assets/1cff4512-9fa6-423f-b16a-c80d1a977405" />
<img width="500" height="900" alt="image" src="https://github.com/user-attachments/assets/f14db23f-2f61-43ff-a932-8507baeeac8c" />

Tools Used: 
------

| Tools | Used For |
| -------- |---------- |
| Microsoft Power BI | Dashboard creation, DAX measures and Analysis |
| Excel | For Dataset Extraction |
| Power Query | For Cleaning and Transformation | 
| Figma | Dashboard Background and design |
| HTML | For Floating Ticker | 
| Microsoft PowerPoint | Documentation | 



