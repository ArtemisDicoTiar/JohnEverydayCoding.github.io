---
title: "COVID-19 Analysis Page update"
date: 2020-05-24 17:43:00
categories: study
---

Prediction of active patient of COVID-19 is now plotted on the graph in 'covid.johnjongyoonkim.com'.
As it is illustrated on the webpage, prediction was drawn with polynomial regression.
However, the accuracy was not high enough so new method for prediction was researched.
The new way to predict is using Ordinary Differential Equation making three equations.
The three equations are 'Suspectiable', 'Infected' and 'Removed' which is also called as SIR model.

However, current situation is not an ordinary situation as other infectious diseases. Therefore, the prediction with only SIR model was not fit well.

Now, Autoregressive integrated moving average (ARIMA) model is applied to the prediction system.

The predictions only limited for active patient and the time length is 5days.

[Research about coronavirus(COVID-19)](http://covid.johnjongyoonkim.com)
