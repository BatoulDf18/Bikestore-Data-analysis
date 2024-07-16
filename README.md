# BikeStore Data Analysis Project

This project analyzes BikeStore data using SQL Server, Excel, and Tableau to derive insights and create visualizations.

## Table of Contents

- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Data Source](#data-source)
- [Analysis Process](#analysis-process)
- [Results and Visualizations](#results-and-visualizations)
- [Files in this Repository](#files-in-this-repository)
- [How to Use This Project](#how-to-use-this-project)

## Project Overview

This project analyzes BikeStore revenue data across multiple dimensions including stores, customers, states, cities, and order dates. Using SQL Server for data extraction, Excel for pivot table analysis, and Tableau for visualization, we aim to provide clear insights into sales performance. Our goal is to identify top performers, uncover trends, and highlight growth opportunities. This analysis will help BikeStore management make informed decisions to optimize revenue, improve inventory management, By transforming raw data into actionable insights, we're enabling data-driven decision-making to boost the company's overall financial performance.

## Tools Used

- SQL Server: For initial data querying and extraction
- Microsoft Excel: For pivot table analysis and dashboard creation
- Tableau: For creating advanced visualizations and interactive dashboards

## Data Source

The data used in this project comes from [ "a BikeStore database production and sales  information from 2016 to 2018"].

## Analysis Process

1. **SQL Server Query**: 
   - Wrote and executed a complex query to extract relevant data from the BikeStore database.
   

2. **Excel Analysis**:
   - Imported the SQL query results into Excel.
   - Created pivot tables to analyze revenu .
   - Developed a dashboard in Excel to visualize key metrics.

3. **Tableau Visualization**:
   - Connected Tableau to the Excel file containing the analyzed data.
   - Created interactive visualizations and dashboards to represent key metrics.

## Results and Visualizations
Here are some key findings and visualizations from my analysis:
![screen1](images/sreen1.png)
![screen2](images/sreen2.png)
![screen3](images/sreen3.png)


## Files in this Repository

- `SQl Queries /Sql Queries/Query.sql`: The SQL query used to extract data from SQL Server.
- `Visualisation/BikeStore.xlsx`: Excel file containing pivot tables and dashboard.
- `Visualisation/BikeStore.twb`: Tableau workbook with visualizations and dashboards.


## How to Use This Project
1.create a database on Sql server calles Bikestore then install the zip file on databases and excute eatch sql file on it.
2. Execute the SQL query in `BikeStore_Analysis_Query.sql` on your SQL Server instance containing the BikeStore database.
3. Open `BikeStore_Analysis.xlsx` to view the Excel pivot tables and dashboard. Refresh the data connection if needed.
4. Open `BikeStore_Visualizations.twb` in Tableau to interact with the visualizations. You may need to reconnect to the Excel data source.

