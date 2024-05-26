# GLOBAL SUPERSTORE DASHBOARD

## Overview
Welcome to the Power BI project for the global store dataset! This project delivers an in-depth report on sales transactions across worldwide branches. It features a range of visualizations to assist stakeholders in analyzing and comprehending crucial aspects of the business.


## Table of Contents

- [Getting Started](#Getting_Started)
- [Data Cleaning](#data-cleaning)
- [Visual Segmentation](#visual-segmentation)
- [Shipping Analysis](#shipping-analysis)
- [Sales Visualizations](#sales-visualizations)
- [Tables](#tables)
- [Contributing](#contributing)
- [To download Power BI File](#To-download-power-bi-file)

## Getting Started

To get started with the Power BI project, follow these steps:

1. Download the Power BI file from [https://docs.google.com/spreadsheets/d/1Ez8RhO1rE2QikfdddOZ19eEZhN4r6eW7WHb9qB05T7E/edit?usp=sharing].
2. Open the file using Power BI Desktop.
3. Explore the various visualizations and tables to gain insights into sales transactions.

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

## Data Cleaning

The dataset has undergone basic data cleaning to ensure accuracy and consistency. Cleaning steps include correcting the column headers,removing/filling null values if required.

## Visual Segmentation

- **Region, Country, and Market Slicers:**
  - Utilize slicer visualizations to segment data by region, country, and market for a focused analysis.

## Shipping Analysis

- **Shipping Percentage by Ship Mode:**
  - A DAX formula has been applied to calculate the percentage of shipping costs based on ship mode.
    ```DAX
    DIVIDE(SUM('Orders'[Shipping Cost]), CALCULATE(SUM('Orders'[Shipping Cost]), ALL('Orders'[Ship Mode])))
    ```

## Sales Visualizations

- **Sales by Region (Map):**
  - Use the map visualization to visually represent sales across different regions.
  
- **Sales by City (Stacked Column Chart):**
  - Analyze sales trends in various cities using the stacked column chart.

- **Sales by State (Map):**
  - Visualize sales distribution across different states using the map.

- **Sales by Market (Stacked Bar Chart):**
  - Understand sales performance by market through the stacked bar chart.

## Tables

- **Tables for Detailed Information:**
  - Supporting tables have been created for each visualization.

## Contributing

Fell free to contribute to this project.

## To download Power BI File

If you are not able to download the Power BI file, please check the [Releases section](../../releases) , there you can find the power BI file,screenshot and video.

# Visual Segmentation
* Region, Country, and Market Slicers:
  *  Utilize slicer visualizations to segment data by region, country, and market for a focused analysis.


