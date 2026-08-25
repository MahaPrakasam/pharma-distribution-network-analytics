# Pharmaceutical Distribution Network Efficiency & Regional Demand Analytics

## Industry

**Pharmaceutical Distribution & Supply Chain Analytics**

------------------------------------------------------------------------

## Project Overview

The pharmaceutical distribution industry requires efficient inventory
management, timely deliveries, effective warehouse operations, and
accurate demand monitoring. Inefficient distribution networks can lead
to stock imbalances, product spoilage, delivery delays, and increased
wastage costs.

This project, **Pharmaceutical Distribution Network Efficiency &
Regional Demand Analytics**, analyzes pharmaceutical distribution data
to evaluate regional demand, warehouse performance, inventory levels,
spoilage risks, and logistics efficiency.

The project uses **SQL for data management and analysis** and **Power BI
for interactive data visualization**, helping transform raw distribution
data into meaningful business insights.

------------------------------------------------------------------------

## Project Objectives

-   Analyze pharmaceutical distribution performance across different
    regions and states.
-   Identify regional demand patterns and revenue contribution.
-   Evaluate warehouse performance and distribution efficiency.
-   Monitor inventory levels, including available stock and closing
    stock.
-   Analyze product spoilage and wastage value.
-   Evaluate delivery performance across different transport modes.
-   Measure fulfillment efficiency and delivery timelines.
-   Develop an interactive Power BI dashboard for business
    decision-making.

------------------------------------------------------------------------

## Tools & Technologies

-   **MySQL** -- Database creation, table management, and SQL analysis.
-   **MySQL Workbench** -- Database development and query execution.
-   **Microsoft Power BI** -- Data cleaning, modeling, DAX calculations,
    and dashboard development.
-   **Power Query** -- Data transformation and data quality validation.
-   **DAX** -- KPI and calculated measure creation.
-   **Microsoft Excel** -- Initial dataset storage and preparation.
-   **GitHub** -- Project documentation, version control, and repository
    hosting.

------------------------------------------------------------------------

## Dataset Description

The project uses a pharmaceutical distribution dataset containing
approximately **15,000 records** and multiple attributes related to
orders, warehouses, inventory, products, spoilage, and delivery
performance.

The dataset includes information such as:

-   Order ID
-   Order Date
-   Warehouse ID
-   Warehouse Name
-   Region
-   State
-   Customer Type
-   Product ID
-   Product Name
-   Category
-   Dosage Form
-   Opening Stock
-   Received Quantity
-   Available Stock
-   Fulfilled Quantity
-   Closing Stock
-   Stockout Flag
-   Manufacture Date
-   Expiry Date
-   Days to Expiry
-   Storage Type
-   Average Temperature
-   Temperature Excursion
-   Storage Days
-   Spoilage Risk
-   Spoiled Quantity
-   Transport Mode
-   Distance
-   Delivery Days
-   Delivery Status
-   Distribution Cost
-   Unit Cost
-   Revenue
-   Wastage Value
-   Warehouse Utilization Percentage

The dataset was cleaned and validated before being used for analysis and
dashboard development.

------------------------------------------------------------------------

## SQL Analysis

SQL was used to create and manage the pharmaceutical distribution
database.

The analysis included:

-   Database and table creation.
-   Data storage and retrieval.
-   Total order analysis.
-   Revenue analysis.
-   Revenue by region and state.
-   Regional demand analysis.
-   Warehouse performance analysis.
-   Product-level revenue analysis.
-   Spoilage quantity analysis.
-   Wastage value analysis.
-   Delivery performance analysis.
-   Transport mode analysis.
-   Inventory and stock analysis.

The SQL database contains the pharmaceutical distribution dataset used
as the primary source for analysis.

------------------------------------------------------------------------

## Power BI Dashboard

The Power BI dashboard consists of **four interactive report pages**.

### 1. Executive Overview

Provides a high-level overview of the pharmaceutical distribution
network.

Key visualizations include:

-   Revenue Trend
-   Orders by Region
-   Delivery Performance
-   Total Order Quantity vs Fulfilled Quantity
-   Top 5 Products by Revenue
-   Revenue by Customer Type

### 2. Regional Demand & Distribution

Focuses on regional and geographical distribution performance.

Key visualizations include:

-   Revenue by State
-   Revenue Contribution by Region
-   Warehouse Performance
-   Region-wise Fulfillment Rate
-   Average Delivery Days by Region
-   Demand by Region Map

### 3. Inventory, Spoilage & Expiry Analytics

Focuses on inventory management, stock movement, spoilage, and wastage.

Key visualizations include:

-   Available Stock vs Closing Stock
-   Waste Value by Product Name
-   Spoilage Risk Distribution
-   Spoiled Quantity Analysis
-   Storage Days vs Spoiled Quantity

### 4. Logistics & Delivery Performance

Focuses on transportation efficiency and delivery performance.

Key visualizations include:

-   Average Delivery Days by Transport Mode
-   Delivery Status Distribution
-   Total Order Quantity by Transport Mode
-   Distance vs Delivery Days
-   Transport Mode Performance Matrix

------------------------------------------------------------------------

## Key KPIs

The dashboard tracks important business performance indicators,
including:

-   **Total Orders**
-   **Total Order Quantity**
-   **Total Revenue**
-   **Fulfillment Rate**
-   **Spoilage Rate**
-   **Average Delivery Days**
-   **Total Available Stock**
-   **Total Closing Stock**
-   **Total Spoiled Quantity**
-   **Total Wastage Value**

These KPIs provide a comprehensive overview of pharmaceutical
distribution performance.

------------------------------------------------------------------------

## Key Insights

The analysis helps identify important business patterns, including:

-   Regional differences in pharmaceutical demand and revenue.
-   States contributing the highest revenue.
-   Warehouses with stronger distribution performance.
-   Differences between available stock and closing stock.
-   Products contributing higher wastage value.
-   Distribution of low, medium, and high spoilage risk.
-   Transport modes with longer average delivery times.
-   Delivery status performance, including on-time and delayed
    deliveries.
-   The relationship between delivery distance and delivery days.
-   Overall fulfillment efficiency across the pharmaceutical
    distribution network.

These insights can support better inventory planning, demand
forecasting, warehouse optimization, and logistics decision-making.

------------------------------------------------------------------------

## Project Workflow

The project followed the following workflow:

1.  **Problem Understanding**\
    Defined the pharmaceutical distribution and supply chain business
    problem.

2.  **Dataset Preparation**\
    Prepared a dataset containing pharmaceutical orders, inventory,
    warehouse, spoilage, and logistics information.

3.  **SQL Database Creation**\
    Created the MySQL database and pharmaceutical distribution table.

4.  **Data Loading**\
    Imported the dataset into the MySQL database.

5.  **Data Cleaning & Validation**\
    Performed data quality checks, handled inconsistencies, checked
    missing values, validated business rules, and reviewed data types.

6.  **SQL Analysis**\
    Performed queries to analyze orders, revenue, demand, inventory,
    spoilage, warehouses, and delivery performance.

7.  **Power BI Data Transformation**\
    Used Power Query to clean and prepare the data for reporting.

8.  **Data Modeling & DAX**\
    Created measures and KPIs required for dashboard analysis.

9.  **Dashboard Development**\
    Designed four interactive Power BI dashboard pages.

10. **Insights & Business Analysis**\
    Interpreted the results to identify opportunities for improving
    distribution efficiency and operational performance.

------------------------------------------------------------------------

## Repository Structure

``` text
Pharmaceutical-Distribution-Network-Efficiency-Analytics/
│
├── README.md
│
├── Dataset/
│   └── pharmaceutical_distribution_dataset.xlsx
│
├── SQL/
│   ├── phramadistribution_db.sql
│   ├── database_creation.sql
│   ├── table_creation.sql
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── Pharmaceutical_Distribution_Network_Analytics.pbix
│
├── Screenshots/
│   ├── executive_overview.png
│   ├── regional_demand_distribution.png
│   ├── inventory_spoilage_expiry.png
│   └── logistics_delivery_performance.png
│
└── Documentation/
    └── Project_Report.pdf
```

------------------------------------------------------------------------

## Dashboard Screenshots

### Executive Overview

<img width="887" height="495" alt="Executive Overview" src="https://github.com/user-attachments/assets/b28c0ee3-2016-4c7f-8f15-27a6b04c9854" />


### Regional Demand & Distribution

<img width="885" height="498" alt="Regional Demand   Distribution" src="https://github.com/user-attachments/assets/5bed7865-bea9-43cc-b025-8950b6ebbc93" />


### Inventory, Spoilage & Expiry Analytics

<img width="889" height="494" alt="Inventory, Spoilage   Expiry Analytics" src="https://github.com/user-attachments/assets/759d0b50-7cba-4deb-ae67-7a6bdc4bee6d" />


### Logistics & Delivery Performance

<img width="881" height="493" alt="Logistics   Delivery Performance" src="https://github.com/user-attachments/assets/898965c6-6815-49e4-a1f2-a40e87879926" />


------------------------------------------------------------------------

## How to Run the Project

### Step 1: Clone or Download the Repository

Download the project files from this repository.

### Step 2: Set Up the Database

Open MySQL Workbench and execute the SQL database script available in
the `SQL` folder.

``` sql
CREATE DATABASE phramadistribution_db;
```

### Step 3: Import the Dataset

Import or execute the provided SQL database file to create the table and
load the pharmaceutical distribution data.

### Step 4: Open the Power BI File

Open:

``` text
PowerBI/Pharmaceutical_Distribution_Network_Analytics.pbix
```

using Microsoft Power BI Desktop.

### Step 5: Refresh the Data

If required, update the database or dataset connection and refresh the
data.

### Step 6: Explore the Dashboard

Navigate through the four dashboard pages:

-   Executive Overview
-   Regional Demand & Distribution
-   Inventory, Spoilage & Expiry Analytics
-   Logistics & Delivery Performance

------------------------------------------------------------------------

## Author

**Mahalakshmi.P**

**AF05258357 \| Data and business analytics \| Anudip Foundation**

------------------------------------------------------------------------

⭐ If you found this project useful, feel free to explore the repository
and the dashboard.
