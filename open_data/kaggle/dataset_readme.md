# tRacket Noise Data

This dataset is a 3-month snapshot of data collected by tRacket noise sensors in and around Toronto, Ontario. The data set is great for visual story telling, time series analysis, forecasting, or outlier detection.

## Description

The IoT sensors send data at 5-minute granularity, capturing minimum, maximum and average noise levels over the log periods in dBA units. Each sensor is at a fixed location, please see the `locations.csv` file for approximate lat/lon coordinates (there are locations shown for which there is no data available in the 3-month period). 

We set the dataset to update weekly, loading the most recent 3 months worth of data for all sensors that recorded any data in the period.

## More Data & Updates

Please check the source notebook below - you can load data for other time periods yourself by rerunning the notebook with different parameters.

The data can be explored here as well through the tRacket dashboard https://dashboard.tracket.info/locations

## More Info

Please find more info about the tRacket project & sensors below and feel free to contribute:

Project Website: https://tracket.info/
Github: https://github.com/CivicTechTO/tRacket-directory-START-HERE