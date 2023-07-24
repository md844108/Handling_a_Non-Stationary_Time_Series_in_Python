# Handling_a_Non-Stationary_Time_Series_in_Python
## Introduction: 
What do these applications have in common: predicting the electricity consumption of a household for the next three months, estimating traffic on roads at certain periods, and predicting the price at which a stock will trade on the New York Stock Exchange?

They all fall under the concept of time series data! You cannot accurately predict any of these results without the ‘time’ component. And as more and more data is generated in the world around us, time series forecasting keeps becoming an ever more critical technique for a data scientist to master.

But time series is a complex topic with multiple facets at play simultaneously.

For starters, making the time series stationary is critical if we want the forecasting model to work well. Why? Because most of the data you collect will have non-stationary trends. And if the spikes are erratic how can you be sure the model will work properly?
## AIM: 
The focus of this task is on the methods for checking stationarity in time series data. This article assumes that the reader is familiar with time series, ARIMA, and the concept of stationarity.
## Table of Contents
<ol>
<li>A Short Introduction to Stationarity</li>
<li>Loading the Data</li>
<li>Methods to Check Stationarity</li>
  <ol>
  <li>ADF Test</li>
  <li>KPSS Test</li>
  </ol>
<li>Types of Stationarity<li>
  <ol>
  <li>Strict Stationary</li>
  <li>Trend Stationary</li>
  </ol>
<li>Difference Stationary</li>
<li>Making a Time Series Stationary</li>
    <ol>
    <li>Differencing</li>
    <li>Seasonal Differencing</li>
    <li>Log transform</li>
    </ol>
</ol>

## Reference
 https://www.analyticsvidhya.com/blog/2018/09/non-stationary-time-series-python/

## Install some packages on which our dependency

        pip install matplotlib
        pip install seaborn
        pip install pandas
## To Run Code 
        Here, I'm using Jupyter Notebook to write code so you can run code to select cell from above to down.
