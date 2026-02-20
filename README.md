# Happy Insurance: End-to-End Data Analysis Project

## Project Overview
This project demonstrates a full data lifecycle analysis for Happy Insurance, an insurance provider. The goal was to transform raw operational data into a high-performance analytical environment, providing actionable insights into revenue trends, product performance, and customer segmentation across global regions.

## Tools & Technologies
* **Excel & Power Query**: Data extraction, cleaning, and Star Schema modeling.

* **Power Pivot**: Tabular modeling, DAX measures, and relationship management.

* **Power BI**: Advanced semantic layer, dynamic KPIs, and interactive dashboards.

* **DAX Studio**: Data exploration (EDA) and query optimization.

## Project Phases
### 1. ETL & Star Schema Modeling (Power Query)
* **Extraction**: Loaded raw insurance data into Excel using Power Query.

* **Data Cleaning**: Standardized data formats and handled missing values for insurance products and customer records with M-Language.

   <img width="1688" height="917" alt="M-Language" src="https://github.com/user-attachments/assets/9985b236-ed36-46e1-846a-1e0d0450245a" />

  
* **Modeling**: Designed a Star Schema with a central Fact table (Sales) and related Dimension tables (Products, Customers, and a custom Dim_Date)
  
<img width="1312" height="733" alt="Star Schema" src="https://github.com/user-attachments/assets/cf5b520a-4728-4b38-80d5-2889effd2d23" />


### 2. Tabular Model Development (Power Pivot)
* **Relationships**: Established 1-to-Many relationships to ensure data integrity across the model.

* **Logic**: Developed core DAX measures, calculated columns, and hierarchies to enable deep-dive analysis.

### 3. Visualization & Semantic Layer (Power BI & Excel)
This project delivers insights through two distinct platforms to meet different business needs:

### Power BI Dashboards

* Two Interactive Dashboards: Focuses on high-level KPIs like Revenue, Products sold, and geographical distribution.

* Target Performance: A dedicated view for monitoring actual results against business goals.

* Dynamic KPIs: Implemented visual indicators that respond to slicers for Year (2011–2013), Region, and Product Line.

#### Products Sold in 2013 - Cusomters Performance
<img width="1290" height="726" alt="UnitSold2013 - Customers" src="https://github.com/user-attachments/assets/a7317d04-2b90-4ba2-b1a6-5ea200cbab7b" />

#### Revenue in 2013 - Countries and Products
<img width="1286" height="723" alt="Rev2013 - Country   Products" src="https://github.com/user-attachments/assets/4f0a2534-92a3-41c5-9c97-481a06e029bd" />

### Excel Reporting Layer
#### Management Dashboard: A streamlined dashboard for quick financial snapshots.
<img width="1337" height="649" alt="Excel Report" src="https://github.com/user-attachments/assets/85c76173-da94-4ce9-a8d3-efb9209e04ff" />

#### Three specialized analysis tables for detailed auditing of customer and product performance.
<img width="1219" height="625" alt="Pivot Tables" src="https://github.com/user-attachments/assets/653767f6-8c5a-4220-b520-49f0def479fa" />

### 4. Advanced Data Exploration (DAX Studio)
<img width="1082" height="720" alt="Dax" src="https://github.com/user-attachments/assets/ee515430-4373-4239-9514-eb3602d8ab87" />

<img width="1106" height="673" alt="Dax 1" src="https://github.com/user-attachments/assets/dac083b6-a24f-4bf1-a811-5798e233f045" />










