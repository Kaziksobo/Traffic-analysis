# Traffic indicators on I-94

## Project Description

The goal of this project is to determine a few indicators of heavy traffic on the I-94 Interstate highway, and determine what factors can contribute to the traffic volume. For example, does heavy rain lead to heavier traffic? Does traffic get worse during the week or on weekends? These are the types of questions we will be exploring in this project. This project is done in a Jupyter notebook using Python.

## About the dataset

The dataset has 48204 rows and 9 columns. Each row corresponds to a 1-hour period. Here are the columns:

- `holiday`: Categorical US National holidays plus regional holiday, Minnesota State Fair
- `temp`: Numeric Average temp in kelvin
- `rain_1h`: Amount in mm of rain that occurred in the hour
- `snow_1h`: Amount in mm of snow that occurred in the hour
- `clouds_all`: Percentage of cloud cover
- `weather_main`: Short textual description of the current weather
- `weather_description`: Longer textual description of the current weather
- `date_time`: Hour of the data collected in local CST time
- `traffic_volume`: Hourly I-94 ATR 301 reported westbound traffic volume

This dataset includes data from 2012-10-02 09:00:00 to 2018-09-30 23:00:00.

## Credits

The dataset was made available by John Hogue and can be downloaded from the UCI Machine Learning Repository. The dataset documentation can be found [here](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume).
