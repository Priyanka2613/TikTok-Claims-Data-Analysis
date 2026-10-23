# TikTok Claims Data Analysis

## Project Overview
This project explores a simulated TikTok dataset to understand the differences between videos classified as **claims** and **opinions**.

The analysis examines video engagement metrics, author ban status, and patterns that may help inform future video classification models.

**Project:** Google Advanced Data Analytics Professional Certificate — TikTok Portfolio Project

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Exploratory Data Analysis (EDA)
- Data Cleaning and Descriptive Statistics

## Dataset
The dataset contains **19,382 video records**.

- Claim videos: 9,608
- Opinion videos: 9,476
- Missing claim-status values: 298

*Note: This is a simulated educational dataset, not real TikTok platform data.*

## Key Findings

### 1. Claim vs. Opinion Videos
Among videos with known claim status:
- 50.35% are claims.
- 49.65% are opinions.

### 2. Video Engagement
- Claim videos average approximately **501,029 views**.
- Opinion videos average approximately **4,956 views**.
- Claim videos generally have higher likes-per-view, comments-per-view, and shares-per-view ratios.

### 3. Author Ban Status
- 14.98% of claim videos are associated with banned authors.
- 2.07% of opinion videos are associated with banned authors.
- Videos associated with banned authors generally have higher engagement than videos associated with active authors.

These findings indicate associations, not causal relationships.

## Recommendations
- Investigate missing claim-status values.
- Conduct further exploratory analysis of engagement patterns.
- Assess data quality before developing a classification model.

## Project Notebook
[View the Jupyter Notebook](TikTok_Data_Analysis.ipynb)

## Conclusion
This project demonstrates practical skills in data exploration, data manipulation, descriptive statistics, and communicating data-driven insights using Python.
