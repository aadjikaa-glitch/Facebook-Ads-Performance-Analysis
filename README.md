# Facebook-Ads-Performance-Analysis
This project analyzes Facebook advertising data from 2021 to evaluate campaign performance, advertising efficiency, and return on marketing investment (ROMI). The goal is to understand spending patterns, campaign effectiveness, and relationships between key marketing metrics.
#  Facebook Ads Performance Analysis (2021)

##  Project Overview

This project analyzes Facebook advertising data from 2021 to evaluate campaign performance, advertising efficiency, and return on marketing investment (ROMI).

The main goal is to understand how advertising spend relates to revenue generation and how campaign performance varies over time and across different campaigns.

---

##  Objectives

The analysis covers the following tasks:

### 1. Daily Performance Analysis
- Group data by day
- Calculate daily advertising spend
- Calculate daily ROMI
- Visualize daily trends
- Apply rolling averages to smooth fluctuations in:
  - Ad spend
  - ROMI

---

### 2. Campaign-Level Analysis
- Group data by campaign name
- Calculate total ad spend per campaign
- Calculate total ROMI per campaign
- Compare campaign performance

---

### 3. ROMI Distribution Analysis
- Analyze the spread of daily ROMI per campaign using box plots

---

### 4. ROMI Distribution
- Build a histogram to understand overall ROMI distribution

---

### 5. Correlation Analysis
- Build a correlation heatmap between all numerical variables
- Identify:
  - Strongest correlations
  - Weakest correlations
- Analyze how `total_value` relates to other metrics

---

### 6. Spend vs Revenue Relationship
- Build a scatter plot with linear regression
- Analyze relationship between:
  - `total_spend`
  - `total_value`

---

##  Methods & Techniques Used

- Data grouping (`groupby`)
- Time series analysis
- Rolling averages (`rolling(window=7)`)
- Data visualization:
  - Line plots
  - Box plots
  - Histograms
  - Heatmaps
  - Regression plots
- Correlation analysis
- Basic statistical exploration

---

## Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

---

## Dataset

`facebook_ads_data.csv`

Contains advertising performance data including:
- Ad spend
- Revenue (`total_value`)
- Campaign names
- ROMI metrics
- Date information

---

## Key Insights (

- Advertising performance varies significantly across campaigns.
- Some campaigns demonstrate higher efficiency in terms of ROMI.
- A positive relationship exists between ad spend and revenue generation.
- Rolling averages help reveal long-term trends by reducing daily volatility.
- ROMI distribution shows variability in campaign effectiveness.

---
