# Tableau Electric Vehicle Dashboard
## Overview
This repository contains a Tableau project that analyzes the "Electric Vehicle Dataset." The project includes the Tableau workbook file and the dataset used in the analysis.

## Files
EV_Dashboard.twbx - The main Tableau workbook file.
Electric_Vehicle_Details.csv - Dataset containing detailed information about electric vehicles.
Sales_Performance.csv - Dataset containing sales performance data.
## Usage
Download the EV_Dashboard.twbx file.
Open it in Tableau Desktop.
Ensure that the dataset files (Electric_Vehicle_Details.csv) are placed in the folder relative to the .twbx file location.

## Column Descriptors
Electric_Vehicle_Details.csv
VIN (1-10): Vehicle Identification Number of the vehicle mentioned in the dataset.
County: Name of the county from where the data is gathered.
City: Name of the city from where the data is gathered.
State: Name of the state from where the data is gathered.
Postal Code: The postal code from where the data is present.
Model Year: Manufacturing year of the model mentioned in the dataset.
Make: Manufacturer of the vehicle.
Model: Model name of the mentioned vehicle.
Electric Vehicle Type: Type of the vehicle present in the dataset.
Clean Alternative Fuel Vehicle (CAFV) Eligibility: Clean alternative for the data present in this dataset.
Electric Range: The range the car provides.
Base MSRP: Base cost without any accessories.
Legislative District: Legislative district it falls under.
DOL Vehicle ID: Department of Licensing issued Vehicle ID.
Sales_Performance.csv
Order ID: Unique identifier for each order.
Product: Product name.
Quantity: Quantity ordered.
Price: Price of the product.
Total Sales: Total sales amount.
Order Date: Date the order was placed.
Customer ID: Unique identifier for each customer.
Region: Geographic region of the sale.

## How to Use the Dashboard
The dashboard provides insights into various aspects of the electric vehicle dataset, including:
Total Vehicles: Understand the overall landscape of electric vehicles, encompassing both BEVs and PHEVs, to assess the market's size and growth.
Average Electric Range: Determine the average electric range of the electric vehicles in the dataset to gauge technological advancements and efficiency of EVs.
Total BEV Vehicles and % of Total BEV Vehicles: Identify and analyze the total number of Battery Electric Vehicles (BEVs) in the dataset, and calculate the percentage of BEVs relative to the total number of electric vehicles.
Total PHEV Vehicles and % of Total PHEV Vehicles: Identify and analyze the total number of Plug-in Hybrid Electric Vehicles (PHEVs) in the dataset, and calculate the percentage of PHEVs relative to the total number of electric vehicles.
Additional visualizations include:
Total Vehicles by Model Year (From 2010 Onwards): Line/Area chart illustrating the distribution of electric vehicles over the years, providing insights into growth patterns and adoption trends.
Total Vehicles by State: Map chart showcasing the geographical distribution of electric vehicles across different states, allowing for the identification of regions with higher adoption rates.
Top 10 Total Vehicles by Make: Bar chart highlighting the top 10 electric vehicle manufacturers based on the total number of vehicles, providing insights into market dominance of specific brands.
Total Vehicles by CAFV Eligibility: Pie/Donut chart illustrating the proportion of electric vehicles eligible for Clean Alternative Fuel Vehicle (CAFV) incentives, aiding in understanding the impact of incentives on vehicle adoption.
Top 10 Total Vehicles by Model: Tree map highlighting the top 10 electric vehicle models based on the total number of vehicles, offering insights into consumer preferences and popular models in the market.

## Notes
Ensure that you have Tableau Desktop installed to view and interact with the .twbx file.
The datasets should be placed in the same folder as the Tableau workbook for proper data linking.
