# 🚆 Forecasting LRT Kelana Jaya Line Ridership in Malaysia
This project aims to forecast monthly ridership of the LRT Kelana Jaya Line, a major light rail transit system in the Klang Valley, Malaysia. The forecast insights acts to support the rationale of government's decision to increase the amount of train sets.

## 📌 Objective
To analyze trends in ridership and forecast future demand for the next 24-months using time series models.

## 📅 Dataset
Data: Monthly public transport ridership

Period: Jan 2019 - Jul 2024

Source:[ Ministry of Transport Malaysia Open Data
]([url](https://data.gov.my/data-catalogue/ridership_headline))

## 🔧 Tools & Models Used
| Programming | Models/Methods| Packages | Skills | 
| --- | --- | --- | --- |
| R | Random walk drift method, ETS model, ARIMA | fpp2 | Data preparation, data visualization, data analysis, model fitting, time series forecasting |

## 🛠️ Methodology
**1. Data Cleaning**
- Removed data from 2020 and early 2021 to eliminate pandemic-related noise
- Checked for missing values and outliers
- Converted to time series data type using R

**2. Exploratory Data Analysis (EDA)**
- Visualized overall ridership trends
- Seasonal decomposition to identify seasonality and trend components
- Plotted ACF/PACF to assess stationarity

**3. Model Building**
- Tried several models, including drift method, ETS models and ARIMA models
- Selected the best model according to model fit and forecast accuracy

**4. Forecasting**
- Forecasted ridership for the next 24 months
- Visualized forecast with 95% confidence intervals

## 🔑 Key Findings
- Ridership is on an increasing trend post-pandemic recovery.
- Both ETS model and ARIMA model shown increasing LRT Kelana Jaya Line ridership in the next 24 months (Aug 2024 - Jul 2026) but at different rates.
- Conclusion is to support the government to increase number of train sets with continuously monitoring of LRT ridership

### Acknowledgement
This project was completed as part of a Regression Analysis class assignment at Sunway University. 
