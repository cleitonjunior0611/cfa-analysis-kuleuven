# Financial Analysis and Valuation Project (HMA89A)

## 📊 Project Overview

This repository contains Python code developed for the **Financial Analysis and Valuation (HMA89A)** course at **KU Leuven**. The code performs comparative financial analysis between Just Eat Takeaway (TKWY.AS) and market indices.

## 🔍 What the Code Does

### 📈 Data Collection & Processing
- **Fetches historical market data** using Yahoo Finance API for:
  - Just Eat Takeaway stock (TKWY.AS)
  - AEX Index (^AEX) and Euro Stoxx 50 Index (^STOXX50E)
- **Time period**: 2016-2023 (with variations across analyses)
- **Handles data alignment** and timezone normalization

### 📊 Performance Analysis
- **Normalizes price data** to base 100 for comparative analysis
- **Calculates daily returns** using percentage change method
- **Computes annualized volatility** (standard deviation of returns × √252)
- **Identifies key price points**:
  - Maximum and minimum closing prices
  - Corresponding dates for extreme values

### 📉 Visualization & Output
- **Generates comparative performance charts** showing normalized prices
- **Exports processed data** to Excel format for further analysis
- **Prins key metrics** including volatility measurements
- **Creates professional visualizations** with matplotlib

### 🔧 Technical Features
- **Data cleaning**: Handles missing values and aligns time series
- **Financial calculations**: Implements standard financial metrics
- **Flexible time periods**: Easily adjustable date ranges
- **Multiple comparative analyses**: Against both AEX and Euro Stoxx 50 indices

## 📋 Output Generated

- **Comparative performance charts** (Just Eat vs. Indices)
- **Volatility statistics** for both stock and benchmarks
- **Excel files** with processed data for further analysis
- **Price extreme analysis** (max/min values with dates)

*The code provides a foundation for more advanced valuation techniques including DCF analysis, beta calculation, and other financial metrics typically covered in advanced valuation courses.*
