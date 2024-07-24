# Car Registrations Austria Report

This project was part of my master's degree in the Data Engineering module. I analyzed a dataset on new car registrations in Austria since 2000.
The dataset was provided by Statistics Austria and is available [here](https://www.data.gv.at/katalog/dataset/1446c895-cd1f-3ed4-8dd2-66fee300c16e).

This repository contains the code and data analysis for the project on the Austrian automotive market. The study explores car registration trends, market dynamics, and their correlations with economic indicators. The report presents key findings and insights from the analysis.

## Introduction

The automotive industry is crucial to modern society, and this study focuses on new car registrations in Austria. The key objectives are:

* Examine if Volkswagen maintains the highest market share.
* Investigate the seasonality of car registrations.
* Analyze the correlation between economic conditions and car registrations.

## Data Exploration

### Dataset Description

The dataset includes:

Passenger car brand: The brand of the car.
Time (monthly values): The month and year of registration.
Number of registrations: Number of new car registrations per brand and month.
Dataset Overview
Rows: 12,612
Columns: 3 (after dropping the "Vehicle type" column)
Unique brands: 105
Total registrations: 7,213,112
Monthly Car Registrations
The number of new car registrations is aggregated by month to provide a comprehensive view, accounting for brands with no registrations in some months.

### Car Companies

Brands are grouped under their respective companies to analyze the performance of major car manufacturers effectively.

### Seasons

The data is grouped into four seasons (spring, summer, autumn and winter) to analyze seasonal patterns in car registrations.

### Economic Indicators

The dataset is extended to include GDP and the Austrian Traded Index (ATX) to analyze the impact of economic conditions on car registrations.

## Analysis and Results

### Hypothesis 1: Volkswagen Dominance

Volkswagen consistently holds the highest market share in new car registrations in Austria, with only occasional exceptions. The Volkswagen Group remains dominant, with other brands like Skoda showing significant performance.

### Hypothesis 2: Seasonality

Car registrations exhibit strong seasonal patterns, with higher registrations in spring and summer and lower in autumn and winter. This seasonality reflects consumer behavior influenced by weather conditions, holidays, and other factors.

### Hypothesis 3: Correlation with Economic Conditions

The correlation analysis suggests a slight negative correlation between car registrations and economic indicators like GDP and ATX. This indicates that other factors, such as consumer preferences and seasonality, may have a more significant impact on car registrations.
