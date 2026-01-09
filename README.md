# Food Price in Nigeria (2007–2025)
Analysis of food prices across different states in Nigeria showing trends over time and predicting what the future price could be.

## Overview
This project analyzes food price trends in Nigeria from 2007 to 2025 and predict possible future prices using a dataset compiled by the World Bank Development Economics Data Group. 
The analysis focuses on identifying long-term trends, regional price disparities, and the potential influence of socio-political events—particularly election cycles—on food price inflation. Insights from this project aim to support data-driven decision-making for households, businesses, and policymakers.

## Problem Statement
Food price volatility remains a major economic and social challenge in Nigeria, directly affecting household welfare, business planning, and national food security. Despite the availability of raw price data, there is limited accessible analysis that explains:

- How food prices have evolved over time

- Whether certain periods experience abnormal price spikes

- How prices differ across regions and markets

- What socio-economic factors may influence these fluctuations

- What is the possible future food price 

This project addresses these gaps by exploring historical price patterns, identifying structural breaks in trends, and highlighting geographic and political influences on food prices.

## Dataset
The dataset is a weekly-updated resource compiled by the World Bank Development Economics Data Group. It combines direct price measurements with machine learning-based estimation techniques to impute missing values. Data sources include the World Food Program (WFP), FAO, national statistical offices, and official exchange rate records.

Spatial coverage (Nigeria): Abia, Borno, Yobe, Katsina, Kano, Kaduna, Gombe, Jigawa, Kebbi, Oyo, Sokoto, Zamfara, Lagos, Adamawa, and Market Averages

Citation:
Andrée, B. P. J. (2021). Monthly food price estimates by product and market (Version 2025-08-25). NGA_2021_RTFP_v02_M. Washington, DC: World Bank Microdata Library.
https://doi.org/10.48529/2ZH0-JF55

## Tools Used
Microsoft Excel – Data exploration and cleaning

Power BI – Trend analysis and visualization

Python – Used for data preprocessing, modeling, evaluation, and visualization.

## Methodology
### 1. Data Exploration and Cleaning (Excel)

The dataset was first imported into Excel for basic cleaning and transformation. The following steps were performed:

- Converted the dataset into a structured table

- Renamed columns for clarity:
  adm1_name → state
  adm2_name → local_govt
  mkt_name → market_name

- Converted numeric month values into textual month names

- Handled missing values by computing the average of the open, close, low, and high estimates for each product.
This ensured consistent formatting, better interpretability, and reduced missingness before visualization.

### 2. Descriptive Analysis (Power BI)

The cleaned dataset was imported into Power BI for interactive visualization and time-series analysis. Line charts, state-level comparisons, and commodity-wise breakdowns were used to identify structural changes, long-term trends, and volatility patterns.

### 3. Predictive Analysis (Python)
Using maize prices as a case study SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables) was use for historical time series data. Accurate forecasting of food prices is crucial for agricultural planning, policy formulation, and food security decision-making. 
this 

## Key Insights
### 1. Long-Term Price Trends

From 2007 to 2015, most food items exhibited a relatively linear upward trend.

A major structural break occurred in 2016, after which prices accelerated sharply.

The period from 2019 to 2025 showed extreme volatility and sustained price increases.

External factors such as COVID-19, currency redesign policies, national elections, and subsidy changes likely contributed to these fluctuations.

### 2. Electoral Cycle Impact

A consistent pattern was observed linking election years with food price spikes. Price surges were especially notable following the 2015, 2019, and 2023 elections, suggesting a strong correlation between political cycles and food inflation.

### 3. Geographic Price Variations

Substantial differences exist in food prices across states and markets. For example:

Bread: Most expensive in Lagos, Oyo, Zamfara; least expensive in Abia, Jigawa, Sokoto

Cassava Meal: Most expensive in Oyo, Kebbi, Gombe; least expensive in Lagos, Zamfara, Jigawa

Cowpeas: Most expensive in Abia, Lagos, Oyo; least expensive in Sokoto, Yobe, Katsina

Rice: Most expensive in Borno, Gombe, Lagos; least expensive in Jigawa, Kebbi, Zamfara

These disparities highlight the importance of localized market dynamics.

### 3. Food Price Prediction
- Maize prices follow predictable seasonal cycles, likely driven by planting and harvest periods, supply chain patterns, and market demand fluctuations.

- Price movements show strong dependence on past trends, suggesting that inflationary pressures tend to persist once established.

- The forecast points to a moderate stabilization and slight decline in prices in the near term, rather than extreme short-term spikes.

- However, the model also highlights growing uncertainty over longer forecast horizons, implying that unexpected economic or policy shocks could significantly alter future prices.

From a business perspective, these forecasts can support better inventory planning, procurement strategies, and risk management for traders, retailers, and agribusinesses.

From a policy standpoint, the results emphasize the importance of early intervention through market stabilization policies, improved storage systems, and targeted food subsidies. Timely policy actions could reduce extreme price swings and improve food affordability, especially for vulnerable households.

## Conclusion
This analysis reveals that food prices in Nigeria have experienced sustained long-term growth, punctuated by periods of extreme volatility. Political cycles, macroeconomic shocks, and regional market differences play significant roles in shaping price behavior.

The findings emphasize the importance of proactive planning, region-specific strategies, and improved storage and supply-chain infrastructure. By leveraging historical price patterns, households, businesses, and policymakers can better anticipate price shocks and reduce the impact of food inflation.

Conclusion

This project provides a comprehensive analysis of food price dynamics in Nigeria from 2007 to 2025, combining historical trend analysis with predictive modeling to better understand both past behavior and future risks. The findings confirm that food prices in Nigeria are not only on a long-term upward trajectory but are also highly sensitive to macroeconomic shocks, political cycles, and regional market conditions.

Overall, this project emphasizes that food price inflation in Nigeria is a systemic challenge rather than a short-term anomaly. For businesses, the insights support more informed pricing, procurement, and inventory planning decisions. For policymakers, the results reinforce the need for proactive, data-driven interventions—such as market stabilization policies, improved supply chain infrastructure, and targeted social protection measures—to mitigate price volatility and strengthen national food security.

By transforming raw food price data into actionable insights, this project demonstrates how data analytics and time-series forecasting can contribute meaningfully to economic planning, risk management, and policy formulation in developing economies

