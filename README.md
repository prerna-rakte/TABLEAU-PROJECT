# Tata Motors Vehicle Sales and Profitability Analysis Dashboard Using Tableau

## Project Overview

This project focuses on analysing Tata Motors vehicle sales data using Tableau. An interactive dashboard has been developed to understand overall revenue, estimated profit, units sold, vehicle-type performance, regional sales and monthly sales trends.

The dashboard presents important business information through KPI cards, charts, filters, segmentation and clustering.

## Project Objectives

1. To analyse overall vehicle sales and revenue performance.
2. To understand estimated profit and profit ratio.
3. To compare sales performance across different vehicle types and regions.
4. To identify the top 10 vehicle models based on revenue.
5. To analyse sales trends using interactive visualizations.
6. To explore vehicle performance through segmentation and clustering.

## Dataset Details

Dataset Name: Tata Vehicle Sales Dataset

Dataset Source: GitHub

Dataset Link: https://github.com/Abhishek6290/Tata-Vehicle-Sales-Dashboard

Number of Records: Approximately 800

Dataset Format: CSV

Important Fields: Vehicle ID, Vehicle Model, Vehicle Type, Region, Sales Date, Sales Quantity, Revenue, Production Quantity, Inventory Levels, Cost per Vehicle and Profit Margin.

Note: This is a community-created dataset hosted on GitHub and is not official Tata Motors company data.

## Tools and Technologies Used

1. Tableau Desktop
2. CSV Dataset
3. Data Visualization
4. Dashboard Development and Analysis

## Dashboard Features

1. KPI Cards: Display Total Revenue, Estimated Profit, Total Units Sold and Profit Ratio.
2. Monthly Sales Trend: Shows the monthly revenue trend.
3. Sales by Vehicle Type: Compares revenue across different vehicle types.
4. Sales Performance by Region: Displays revenue comparisons across North India, South India and West India.
5. Top 10 Vehicle Models: Identifies the vehicle models with the highest revenue.
6. Vehicle Model Revenue Segmentation: Displays revenue distribution across vehicle types and models.
7. Vehicle Clustering: Groups vehicle models based on revenue and profit margin.
8. Interactive Filters: Allows users to filter the dashboard by Year, Vehicle Type and Region.

## Calculated Fields

Total Revenue = SUM([Revenue])

Estimated Profit = SUM([Revenue] * [Profit Margin (%)] / 100)

Profit Ratio = SUM([Revenue] * [Profit Margin (%)] / 100) / SUM([Revenue])

Average Sales = AVG([Revenue])

## Key Insights

1. The total revenue displayed in the dashboard is Rs. 172,660,277,052.
2. SUV is the highest-revenue vehicle type, contributing approximately Rs. 109.17 billion.
3. North India recorded the highest regional revenue of Rs. 59,581,968,515.
4. Tata Safari generated the highest revenue among the displayed vehicle models, with Rs. 35,797,484,757.
5. The dashboard displays an estimated profit of Rs. 23,942,013,815.70 and an overall profit ratio of 13.87 percent.

## Project Files

The repository includes the following files:

1. Tableau Workbook (.twbx)
2. Vehicle Sales Dataset (.csv)
3. Final Dashboard Screenshot
4. README.md

## Conclusion

This project demonstrates the use of Tableau for analysing and visualizing vehicle sales data. The interactive dashboard converts raw data into meaningful insights and helps users understand revenue performance, estimated profitability, regional sales, vehicle-type performance and top-performing vehicle models.

## Developed By

Name: Prerna Yesudas Rakte

Class: TY BSc IT Semester V

Academic Year: 2026-2027

Subject: Data Visualization with Power BI and Tableau
