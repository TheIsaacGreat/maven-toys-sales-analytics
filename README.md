Maven Toys Sales Analytics Dashboard

A Power BI analytics solution that transforms raw toy sales data into actionable insights for revenue growth, inventory planning, and executive decision making.

Project Overview

This project analyzes sales performance for Maven Toys using Power BI. It provides interactive dashboards that help business leaders understand revenue trends, product performance, store contribution, and profitability.

The dashboard supports data driven decisions for sales strategy, inventory optimization, and regional performance management.

Goal

Sales teams and executives often struggle to connect raw transactional data to business outcomes. This project was built to bridge that gap by turning complex sales records into clear insights that support planning, forecasting, and performance monitoring.

The project demonstrates strong data modeling, DAX calculation design, and storytelling with data.

Features

Interactive Power BI dashboards with slicers for year, product category, store location, and product type

Clean star schema data model with fact and dimension tables

DAX measures for total revenue, profit, margin, units sold, and year over year growth

KPI cards that highlight business health at a glance

Drilldown visuals for product and store level analysis

Clear visual hierarchy for executive reporting

Data

Source: Kaggle Maven Toys Dataset

The dataset contains toy sales transactions across multiple stores and years.

Key fields include:

Order date

Product category and product name

Store location and store type

Units sold

Revenue

Cost and profit

Data cleaning steps included removing duplicates, fixing data types, validating date fields, and creating calculated columns for analysis.

Usage

Download the repository

Open the file Maven_Toys_Sales_Report.pbix in Power BI Desktop

Use slicers to filter by year, product category, or store

Click visuals to explore relationships and trends

No external configuration is required.

Project Structure
/data
  raw_data.csv
  cleaned_data.csv

/powerbi
  Maven_Toys_Sales_Report.pbix

/docs
  data_dictionary.md
  project_notes.md

README.md

Technical Details

Tool: Power BI Desktop

Data modeling: Star schema

Data cleaning: Power Query

Calculations: DAX measures

Visualization: KPI cards, bar charts, line charts, tables, slicers

Key challenges included building efficient measures for revenue and profit while keeping the data model simple and performant.

Results and Insights

A small number of product categories drive most revenue

Certain store locations consistently outperform others

Seasonal sales peaks appear during holiday periods

Profit margins vary widely across product types

These insights support better pricing strategy, inventory planning, and regional focus.

Future Work

Add sales forecasting using time series models

Include inventory and supply chain data

Publish the dashboard to Power BI Service for live sharing

Contribution Guidelines

Fork the repository

Create a new branch

Commit changes with clear messages

Open a pull request

Contact

For questions or collaboration, reach out via GitHub issues or LinkedIn.

References

Kaggle Maven Toys Dataset

Microsoft Power BI Documentation
