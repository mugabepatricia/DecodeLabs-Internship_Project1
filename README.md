# Retail Sales Analysis Using Excel (Descriptive Statistics & Outlier Detection)

## Project Overview

This project performs foundational exploratory data analysis (EDA) on a retail sales dataset using Microsoft Excel. The objective is to compute descriptive statistics, identify trends, and detect outliers using statistical methods such as the Interquartile Range (IQR).

The analysis serves as the first stage in a broader analytics pipeline, preparing the dataset for deeper SQL exploration and Tableau visualization.

## Objectives

* Compute key descriptive statistics (mean, median, min, max, standard deviation)
* Analyze sales trends using pivot tables
* Identify outliers using the IQR method
* Create flags for anomalous transactions
* Summarize business insights from raw transactional data

## Dataset Description

The dataset contains retail transaction records including:

* Order ID
* Product Name
* Quantity
* Total Price
* Payment Method
* Order Status
* Order Date
* Referral Source

## Key Analysis Performed

1. Descriptive Statistics

Computed using Excel functions:

* AVERAGE()
* MEDIAN()
* MIN()
* MAX()
* STDEV.S()

Applied on:

* Total Sales (Revenue)
* Quantity per order

2. Trend Analysis

* Pivot tables grouped by Month / Year
* Revenue trends over time visualized using line charts
* Identification of peak and low-performing periods

3. Outlier Detection (IQR Method)

Outliers were identified using:

* Q1 (25th percentile)
* Q3 (75th percentile)
* IQR = Q3 − Q1
* Lower Bound = Q1 − 1.5 × IQR
* Upper Bound = Q3 + 1.5 × IQR

## Key Insights

* Revenue distribution is right-skewed, indicating a small number of high-value transactions
* Most orders fall within a stable spending range
* A small number of extreme values were flagged as outliers, likely representing bulk purchases or data anomalies
* Seasonal variation observed in monthly sales trends

## Tools Used

* Microsoft Excel
* Pivot Tables
* Statistical Functions
* Conditional Formatting

## Key Outcome

This phase established a clean statistical baseline for the dataset and enabled structured downstream analysis in SQL and Tableau.
