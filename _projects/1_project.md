---
layout: page
title: Predicting Vehicle Prices
description: MSc data-analysis project using machine-learning techniques
img:
importance: 1
category: data-science
related_publications: false
---

## Overview

This graduate project was completed for the Weekend Masters in Applied Statistics and Data Science program at Jahangirnagar University. The report is dated 26 January 2025 and was supervised by Dr. Abdus Salam, Professor in the Department of Statistics and Data Science.

## Objective

The project aimed to estimate vehicle prices, identify influential pricing factors, and provide decision-support insights for buyers and sellers.

## Dataset and preparation

- **9,988 records**
- **18 vehicle-related fields**
- Duplicate removal and context-specific missing-value handling
- Feature engineering, one-hot encoding, IQR-based outlier handling, and numerical scaling
- Engineered vehicle age, registration lag, and views per hour

## Methods considered

- Linear Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Artificial neural networks
- Clustering
- Content-based vehicle recommendation

## Results

Random Forest Regressor was selected as the final model.

| Metric |    Result |
| ------ | --------: |
| R²     |      0.80 |
| MAE    |   374,433 |
| RMSE   | 1,927,833 |

Engine capacity, model, vehicle age, kilometers run, and brand were reported as the most influential features. The report concluded that older age and higher mileage generally reduce price, while engine capacity, brand, and model materially affect it.
