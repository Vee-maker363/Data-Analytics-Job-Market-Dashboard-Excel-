# Data-Analytics-Job-Market-Dashboard-Excel-
Interactive Excel dashboard analysing the data &amp; analytics job market using Power Query, Power Pivot and DAX. The project covers EDA, salary distribution analysis, outlier handling, skill normalisation, relational modelling and dynamic KPIs, demonstrating structured data cleaning, modelling discipline and business-focused dashboard design. 


An end-to-end Excel Business Intelligence project analysing the data & analytics job market using Power Query, Power Pivot, DAX and advanced Excel features.

This project demonstrates structured analytical thinking — from exploratory data analysis (EDA) to data cleaning, relational modelling, and interactive dashboard design.

🎯 Project Objective

The goal of this project was not simply to build charts, but to:

Validate distributional behaviour before reporting

Identify and handle data quality issues

Standardise inconsistent salary formats

Model relational data correctly

Build a clean, interactive dashboard aligned with business questions


The final output is a fully interactive Excel dashboard analysing:

Salary structure and distribution

Outlier impact

Remote vs on-site job breakdown

Top in-demand skills

Job listing platforms


🔎 Phase 1: Exploratory Data Analysis (EDA)

Using Excel’s Analysis ToolPak and PivotTables:

Identified a strong right-skew in salary data

Detected extremely high-end outliers

Confirmed heavy-tailed distributions (kurtosis)

Quantified missing values in the salary and skills columns


Key insight:
Because salary data was heavily skewed, Median was selected as the primary KPI metric instead of Average.


🧹 Phase 2: Data Cleaning (Power Query)

All transformations were performed in Power Query to ensure reproducibility.

Key transformations:

Created a unique Job_ID

Standardised hourly salaries into annual equivalents

Applied IQR-based outlier flag (Core vs Outlier)

Cleaned categorical fields (job_via, location, etc.)

Normalised comma-separated skills into a relational table

Modelled salary bands for distribution analysis

The dataset was reduced from 21 columns to 12 purpose-driven modelling fields.


🧠 Phase 3: Data Modelling (Power Pivot)

The cleaned tables were loaded into the Data Model.

Created a one-to-many relationship between jobs and skills

Built DAX measures for dynamic KPIs

Enabled cross-table filtering


DAX Measures include:

Median Salary

Core Median Salary

Total Job Count

Percentage of Remote Roles


All metrics update dynamically via slicers.

📈 Final Dashboard Features

Median Salary by Role

Salary Distribution (model-driven binning)

Remote vs On-site Breakdown

Top 10 In-Demand Skills

Job Listings by Platform

Dynamic KPI Cards


The dashboard separates:

Analysis layer (PivotTables + validation)

Presentation layer (interactive dashboard sheet)


🛠 Tools Used

Microsoft Excel

Analysis ToolPak

Power Query

Power Pivot

DAX

PivotTables & PivotCharts

Slicers & Report Connections


💡 What This Project Demonstrates

Statistical awareness (skewness, kurtosis, IQR)

Data cleaning discipline

Relational modelling in Excel

Dynamic KPI development

Business-focused dashboard design


🚀 Possible Enhancements

Automated refresh pipeline

AI-based skill clustering

Time-series trend forecasting

Power BI migration version

📚 Dataset Source

The dataset used in this project was sourced from a public data analytics job market dataset shared by Luke Barousse.

Original dataset reference:
https://www.youtube.com/watch?v=pCJ15nGFgVg

The dataset was used for educational and portfolio purposes, and was further explored, cleaned, modelled, and transformed as part of this independent analytical project.
