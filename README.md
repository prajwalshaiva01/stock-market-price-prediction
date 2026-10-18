# Stock Market Price Prediction System

A predictive machine learning project analyzing daily financial trading records to forecast stock closing prices using supervised regression techniques.

## Problem Statement
Forecasting financial equity prices to understand market volatility and intraday price convergence using historical market indicators.

## Dataset Overview
- **Data:** 1,000 historical daily trading sessions.
- **Target Variable:** `Close` (Daily closing stock price).
- **Features Used:** `Open`, `High`, `Low`, `Volume`.

## Data Pipeline & Modeling
- Implemented data preprocessing and chronological train-test split (80-20 ratio).
- Benchmarked Linear Regression, Decision Tree, and Random Forest Regressor models.
- Analyzed price movements using historical moving averages (20-day MA).

## Model Performance
| Model | MAE ($) | R² Score |
| :--- | :--- | :--- |
| **Linear Regression** | 1.320 | 0.986 |
| **Decision Tree Regressor** | 1.574 | 0.980 |
| **Random Forest Regressor** | **1.448** | **0.984** |

**Key Finding:** Both linear and ensemble tree models captured intraday price volatility, achieving an R² score exceeding 0.98 with a low Mean Absolute Error ($1.45).
