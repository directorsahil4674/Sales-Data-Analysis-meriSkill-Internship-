
# Sales Data Analysis 

This project is based on analyzing the sales all accross the cities of United States. This project includes the weekly, month-to-month, city-wise analysis under the year 2019. 

Sales-Analysis Dashboard link
Dashboard Link: https://app.powerbi.com/groups/8bb600a6-52a9-4c17-bd03-fbaf92a61f49/lineage?experience=power-bi
Problem Statement
This dashboard helps to understand the sales data all across the US. It helps understand the product selection of the customers and sales analysis of each product on a monthly and weekly selection basis, including both single and multiple items.
This dashboard helps gain insights into the business and identify the key areas, customer preferences, and profit margin.
Steps followed
Step 1: Loaded data into Power BI Desktop; the dataset is a CSV file.
Step 2: Open the power query editor & in the view tab under the Data Preview section and check the "column distribution," "column quality," & "column profile" options.
Step 3: Since the profile will be opened only for 1000 rows by default, you need to select "column profiling based on the entire dataset."
Step 4: Add the columns related to the DateTime field by segregating them through the 'add column field.' Columns include month number, month name, order quantity (Identified by inserting a calculated file that discusses single and multiple item orders), timing, and states and cities.
Step 5: Reterived the data back to the report view. Rearranged the columns and identified and applied calculated columns and DAX measures.
Step 6: Based on the DAX measures, the associated sales data fields were identified using the matrix initially to cross-check the identified measure's accuracy before getting into charts.
Step 7: Nonetheless, all the KPIs were identified using the card and grouped using the effective charts demonstrating the details of the KPIs.
Step 8: Salse Visuals identified such as (a) Total Orders(b) Total Profit Margin(c) Count of Quantity ordered (Based on city, products respectively)(d) Top 5 Products By Sales (Using TreeMap)(e) Total Sales by Order Quantity (Single and Multiple Orders Count)(f) Total Sales Identified based on the different cities of the US(g) Product Monthly Sales using the line chart
Snapshot of Dashboard (Power BI Service)

Insights
A single-page report was created on Power BI Desktop & it was then published to Power BI Service.
The following inferences can be drawn from the dashboard;
[1] Total Number of Orders = 185.95K
[2] Overall Profit Margin = 0.59%
Profit Margin will change if different visual filters are applied.
[3] Top city with most orders sold:
    City = San Francisco
    Total Orders = 44.73K
    Profit Margin = 0.61%
    Sales Breakthroughobservedd = From October to December with little attenuation between November. 

[4] Top 5 Products by Sales:
    (i) Lightning Charging Cable
    (ii) USB-C Charging Cable 
    (iii) Wired Headphones 
    (iv) AA-Battries (4-Pack)
    (v) AAA-Battries (4-Pack)

The data of TreeMap will change if different visual filters are applied.# Sales-Data-Analysis-meriSkill-Internship- This project was purely done using Microsoft Power BI. The project identifies the sales pattern across the United States. The project is approved and organized by meriSkill
