# About 
This repository contains a Power BI dashboard analyzing and visualizing a random retail dales dataset.

## Overview 
The Retail Sales Analysis Dashboard is built using Microsoft's Power BI. It showcases visulalization to help understand sales and profit over time, categories, products and regions.

## Features 
- An interactive Slicer that allows users to filter by region, category and product.
- Bar chart displaying sum of sales by region.
- Bar chart displaying total sales by product.
- Pie chart displaying total sales by category.
- Line chart visualizing sales over time.

### Files
- Retail_Sales_Data.xlsx: The sales data used in the Power BI dashboard, containing information about orders, products, categories, sales, and profit.
- Retail_Sales_Data.pbix: The Power BI project file containing the dashboard visuals, filters, and DAX measures.
- Retail_Sales_Data_Dashboard.pdf: PDF screenshot of the dashboard.

### DAX Measures Used 
- Total Sales = SUM('Sheet1'[Sales])
- Total Profit = SUM('Sheet1'[Profit])
- Profit Margin = DIVIDE([Total Profit], [Total Sales])

## How to Use

1. **Download the Data File**:
   - Download the `Retail_Sales_Data.xlsx` file from this repository.
  
2. **Open the Power BI Project**:
   - Open `Sales_Analysis.pbix` in **Power BI Desktop**.
  
3. **Interact with the Dashboard**:
   - Use the slicers at the top of the dashboard to filter data by **Region**, **Category**, and **Product**.
   - Right-click or use drill-down features to explore detailed data for specific categories or regions.

  
