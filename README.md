# Introduction
Software for forecasting meteorological weather indicators of the cities of the Novosibirsk region using models based on neural networks. The predicted indicators are the average temperature for the day and the amount of precipitation that fell during the day.
To implement the software, the R-studio development environment and the programming language R. were chosen. Functions for statistical analysis, modeling and forecasting of meteorological indicators were created using standard R packages, and the program interface was created using the Shiny package

# Data

Weather data for the last 60 years (1971 – 2022) for each weather station of the Novosibirsk region and Novosibirsk. The data includes weather characteristics for each day such as maximum, minimum and average daily temperatures, the amount of precipitation that fell during the day, air humidity, atmospheric pressure and others.

# Requirement

R: 4.1.3

Packages: tsibble, opera, NlcOptim, Metrics, nnfor, forecast, tseries, lubridate, mixture, smooth, tsfgrnn, shiny, keras, tensorflow, XML,
          RCurl, timeperiodsR, vroom, tools, shinycssloaders, colourpicker, leaflet, shinytitle, plyr, stringr, reader, DT, tidyverse, reticulate, glue, httr, RSQLite
          
# Models

Autoregression — moving average method (ARIMA) 
Holt-Winters method
Multilayer perceptron method (MLP)
Neural network autoregression method (NNAR)
Neural network method with long-term short-term memory (LSTM)
Method of polynomial potential aggregation
Averaging method
