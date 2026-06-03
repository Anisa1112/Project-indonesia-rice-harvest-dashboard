# Indonesia Rice Harvest Area Dashboard (2024)

## Overview

This project analyzes rice harvest area data across Indonesia in 2024 using Python and Power BI. The objective is to monitor harvest area distribution, identify top-performing regions, and analyze seasonal harvest trends through an interactive dashboard.

## Objectives

* Analyze rice harvest area distribution across Indonesian provinces and regencies.
* Identify regions with the largest harvest areas.
* Monitor monthly harvest trends throughout 2024.
* Develop an interactive dashboard to support agricultural monitoring and decision-making.

## Dataset Information

* Coverage: 38 Provinces and 512 Regencies/Cities
* Period: January – December 2024
* Unit: Hectares (Ha)
* Source: Indonesian Agricultural Statistics

## Tools & Technologies

* Python
* Pandas
* Power BI
* Microsoft Excel

## Data Preparation

The dataset underwent several preprocessing steps:

* Removed metadata and unnecessary rows.
* Renamed and standardized column names.
* Handled missing values.
* Converted data types to numeric format.
* Transformed data from wide format to long format for analysis and visualization.

## Dashboard Features

* Total Harvest Area KPI
* Harvest Area by Province
* Top Producing Regencies/Cities
* Monthly Harvest Area Trend
* Geographic Distribution Map
* Interactive Filtering by Province and Month

## Key Insights

* Harvest activities were concentrated in several major agricultural regions.
* Significant differences in harvest area were observed across provinces.
* Monthly harvest patterns revealed seasonal fluctuations throughout the year.
* Certain provinces consistently contributed a large share of Indonesia's total harvest area.

## Repository Structure

```text
├── data/
│   ├── raw_data.xlsx
│   └── cleaned_data.csv
├── notebooks/
│   └── data_cleaning.ipynb
├── dashboard/
│   └── Rice_Harvest_Dashboard.pbix
├── images/
│   └── dashboard_preview.png
└── README.md
```

## Dashboard Preview

![Dashboard Preview](images/dashboard_preview.png)

## Conclusion

This project demonstrates the end-to-end data analytics process, including data cleaning, transformation, visualization, and insight generation. The dashboard provides an effective way to monitor rice harvest area performance and support data-driven agricultural decision-making.

## Author

Anisa Nur Fitri
