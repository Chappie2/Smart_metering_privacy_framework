# Smart_metering_privacy_framework

This repository relates to a simulation of a big data privacy framework relating to energy consumption of individual smart meters.

The Feature Engineering script makes the data engineering process transparent. The main goal here was to add weather and seasonality data (including holidays), and making all relevant data for future models numeric (binary | float). 

The Modelling 1.0.ipynb exemplifies the steps taken to make a predictive analysis for an individual smart meter.
The Exploratory processed data.ipynb illustrates the statistical analysis performed at the intitial phase of the present study.
ANN 2 LVL - Cluster level.ipynb performs the 2nd level MLP-neural network predictions of a given block.
ANN 1 LVL - Cluster level.ipynb is a proxy for a state-of-the-art model for a given block.
ARIMA - Cluster level.ipynb performs an ARIMA algorithm for a given block

The analyses:
The ARIMA analysis.ipynb evaluates the performance of the ARIMA predictions on the entire dataset.

