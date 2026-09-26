# Time-Series-Data
# US Candy Production by Month: Time Series Forecasting Dataset

## Overview

This repository contains a monthly time series of U.S. candy and sugar product output, used to practice building forecasting models in R.

Kaggle: US Candy Production by Month(https://www.kaggle.com/datasets/rtatman/us-candy-production-by-month), uploaded by Rachael Tatman (2017)
Original source: Board of Governors of the Federal Reserve System, G.17 *Industrial Production and Capacity Utilization* release
Distributed by: Federal Reserve Bank of St. Louis, FRED, series [IPG3113N](https://fred.stlouisfed.org/series/IPG3113N)
Time span: January 1972 to August 2017 


1.
File name: candy_production.csv

---
2. 
## Data Dictionary

Variable 1
Variable name: observation_date
Readable name: Observation date
Measurement units: YYYY-MM-DD
Allowed values: 1972-01-01 to 2017-08-01, consecutive months, no gaps
Description: Each row represents the entire month. This shows the production value for each month.

Variable 2
Variable name: IPG3113N
Readable name: Industrial Production Index: Sugar and Confectionery Products (NAICS 3113), not seasonally adjusted
Measurement units: Numeric (continuous, decimal)
Allowed values: Index number, base year = 100
Description: Measures the real output of U.S. sugar and confectionery manufacturers relative to the base year. A value of 110 means output was 10% higher than the base-year average; 90 means 10% lower.

---
3. 
## Data Collection Methodology

**Who collects it**: The Board of Governors of the Federal Reserve System produces the data as part of its G.17 statistical release, *Industrial Production and Capacity Utilization*. The Federal Reserve Bank of St. Louis republishes it in its FRED database, which is where the Kaggle uploader obtained it in 2017.

**How it is collected**: The Federal Reserve does not survey candy companies directly for this index. It builds each industry's index from two main kinds of source datas. A physical output data such as quantities produced, gathered from government agencies and private trade associations. The Fed uses this wherever it is available and reliable. Second is an input data, used when physical output data are not available. Output is estimated from the hours worked by production workers in the industry, which the Bureau of Labor Statistics collects in its monthly establishment payroll survey, combined with an estimate of productivity. Industry indexes are combined using weights based on each industry's share of value added, and the index has been constructed as a chain-type index since 1972, which is why this series begins in January 1972.

**How often**: The Federal Reserve publishes new estimates monthly, around the middle of the month, for the previous month. Each month's first estimate is preliminary and gets revised over roughly the next five months as more complete source data arrive. The Fed also conducts periodic annual revisions that can update the whole history.

---
4.
## Why This Dataset Intrigues Me

This dataset interests me because it lets me test something most people assume is true: that candy is mostly a holiday business. In this dataset, I can see which months' production  rises and whether those increases line up only with the big candy holidays like Valentine's Day, Easter, Halloween, and Christmas, or whether there are other times of year when production goes up. I'm also curious how far ahead of each holiday manufacturers start ramping up because this data tracks production rather than store sales. For example, does the Halloween peak show up in October, or months earlier in late summer? Furthermore, I want to look for anomalies, such as months or years that break the usual pattern, and figure out what caused them.

Beyond the seasonal pattern, I want to explore whether candy production is connected to bigger economic and social factors. I'm curious whether recessions, caused production to drop, or whether candy holds steady as an affordable treat people keep buying in hard times. I'd  like to consider whether long-term changes, such as growing health awareness around sugar, changes in sugar prices, or international candy manufacturing, show up in the overall trend. Understanding these patterns would help me build better forecasts, and it would show how a company in this industry could plan its production, staffing, and ingredient purchasing around when demand actually happens.

---
## References

- Board of Governors of the Federal Reserve System (US), *Industrial Production: Manufacturing: Nondurable Goods: Sugar and Confectionery Product (NAICS = 3113)* [IPG3113N], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/IPG3113N
- Tatman, R. (2017). *US Candy Production by Month*. Kaggle. https://www.kaggle.com/datasets/rtatman/us-candy-production-by-month
