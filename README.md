# Solar Home System (SHS) Energy Consumption Analysis

## Overview

This repository analyzes **hourly electricity consumption data from 1,000 Solar Home Systems (SHS)** as part of an **Energy Data Analytics** study. The analysis focuses on understanding household energy-use patterns and supporting data-driven SHS sizing.

## Dataset

- **Systems:** 1,000
- **Resolution:** Hourly
- **Analysis period:** First 365 days
- **Consumption unit:** Wh
- **Time representation:** Elapsed hourly observations

Zero values represent no recorded consumption, while missing values (`NaN`) are retained as missing observations.

## Analysis

The analysis includes:

- Hourly and daily energy consumption
- Representative 24-hour load profiles
- Daytime and nighttime consumption
- Peak consumption and peak hours
- Daily consumption statistics
- Autocorrelation of daily demand
- Load-profile clustering
- Battery capacity requirements

## Tools

```text
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook
