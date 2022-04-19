# Time Series
## Call Center Forecasting
![](/images/ts_call_center.png)

**Project description:** Forecast the number of call offering for the next 30 days and apply ErlangC algorithm on projections to calculate the optimal number of needed resources, each 30 minutes of the day, to optimize the workforce planning. 

### 1. Data
* Batch ETL pipeline to refresh offered call volume

### 2. Model
* Forcasting: Ensemble of FbProphet, ThymeBoost and a custom model to learn temporal structure and calculate the forecast.
* Calculate the seasonal daily distribution of calls.
* Dispatch forecasted call volume according to daily proportions, by slice of 30 minutes.
* Workforce Planinng: Apply ErlangC algorithm on the call volume estimated for each slice of 30 minutes, for each day.

[Back](https://cotedave.github.io/)
