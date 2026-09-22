# Comparative Analysis of Time Series Forecasting Models for Cabai Rawit Merah Price Prediction in Central Jakarta

This repository contains the analysis and implementation for the study:

> **Comparative Analysis of Time Series Forecasting Models for Cabai Rawit Merah Price Prediction in Central Jakarta**

The study compares several time series forecasting models to predict daily bird's eye chili prices in Central Jakarta and evaluates their forecasting performance using RMSE, MAE, and MAPE.

## Authors

- **Asyifa Izzatil Isma**
- **M. Aufa Mumtaza Ibadillah**

School of Computer Science  
Bina Nusantara University  
Jakarta, Indonesia

---

## Research Overview

Bird's eye chili is one of the important horticultural commodities in Indonesia. Its price tends to fluctuate considerably due to changes in supply, demand, weather conditions, distribution, and market conditions.

This study aims to compare different time series forecasting approaches under the same experimental conditions to identify a suitable model for forecasting daily bird's eye chili prices in Central Jakarta.

The analysis uses daily price data obtained from the **National Strategic Food Price Information Center (PIHPS)** maintained by Bank Indonesia.

---

## Dataset

The dataset consists of daily bird's eye chili price observations from traditional markets in Central Jakarta.

| Information | Description |
|---|---|
| Commodity | Bird's eye chili / Cabai Rawit Merah |
| Location | Central Jakarta |
| Frequency | Daily |
| Period | May 2021 – May 2026 |
| Number of observations | 1,305 |
| Data source | PIHPS – Bank Indonesia |

The dataset contains weekday observations from Monday to Friday. Therefore, a seasonal period of 5 observations was used to represent one weekly trading cycle. :contentReference[oaicite:1]{index=1}

---

## Methodology

The research consists of six main stages:

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Stationarity Assessment
      ↓
Forecasting Model Development
      ↓
Performance Evaluation
