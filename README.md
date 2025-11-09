Walmart Sales Data Analysis – Capstone Project

This repository contains a comprehensive data analysis project on Walmart’s sales dataset. The goal is to uncover insights that can help Walmart manage inventory and understand the factors influencing sales across its stores.

Project Overview

Dataset: Walmart.csv (6435 rows × 8 columns)

Tools Used: Python, pandas, matplotlib, seaborn, Jupyter Notebook


Key Analyses

Data Cleaning & Preprocessing:

Checked for missing values and converted date columns to datetime format.

Removed outliers from key columns (Weekly_Sales, Unemployment).

Exploratory Data Analysis:

Identified best and worst performing stores by total sales.

Visualized sales distribution across stores.

Feature Impact Studies:

Analyzed the effect of Unemployment, Temperature, CPI, and Fuel Price on weekly sales using binning, bar plots, and correlation heatmaps.

Investigated the impact of holidays on sales.


Correlation Analysis:

Computed and visualized correlations between Weekly_Sales and other numeric features.
Seasonality:

Identified top-performing months for sales.
Insights
•	Analysed 6,435 records from Walmart’s sales dataset covering 45+ stores over a 3-year period (2010–2012) to uncover demand patterns and inventory challenges.

•	Explored variables including temperature, fuel price, unemployment, CPI and holiday flags, identifying their correlation with sales peaks in order to find the impact on demand , informing better planning .

•	Found that holiday flag correlate with significant sales peaks, revealing a 7.84% spike in sales  data helping inform demand forecasting and reduce stockouts during peak periods.

• Despite  of  FEB & SEP  have holiday still its avg sales is less noraml avg.



Sales are highest in moderate temperature ranges and during certain months (NOV,DEC) Percentage Increase in Sales during Top 2 months: 12.22%

Sales are lowest in JAN month 

Unemployment and CPI show negative correlation with sales.
 
Holiday weeks have a distinct impact on sales patterns.
 
Outlier removal improves the reliability of insights.


Usage

Open wp.ipynb in Jupyter Notebook or VS Code to view the step-by-step analysis, code, and visualizations.
