---
title: "Project 4: Time Series Forecasting of Store Sales"
excerpt: "Forecasted store sales in Ecuador using Time Series Analysis"
collection: portfolio
permalink: /portfolio/project-4
---

Some small outlier correction has been performed in advance.

* Used a yearly moving average plot to identify an underlying trend
<br/><img src='/Projects/TSA/Observation.png'>
<br/><img src='/Projects/TSA/MA.png'>
* Used seasonal plots to identify weekly and yearly seasonal behavior
  * Verified seasonality using the periodogram
  <br/><img src='/Projects/TSA/Correlation.png'>
  <br/><img src='/Projects/TSA/Periodogramm.png'>
* Used PACF to identify cyclic behavior and modeled it using an AR(8)-process
<br/><img src='/Projects/TSA/PACF.png'>

[This Project's GitHub Repository](https://github.com/lbrilh/Portfolio/tree/main/Time%20Series%20Forecasting)
