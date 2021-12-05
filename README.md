# Manipulating Time Series Data in Python
This is a tutorial project which explains how to use dates and times in pandas.

# Date & time series functionality
At the root: data types for date & time information
  Objects for points in time and periods
  Attributes & methods reflect time-related details
Sequences of Dates & periods:
  Series or DataFrame columns
  Index: convert object into Time SEries
Many Series/DataFrame methods rely on time information in the index to provide time-series functionality


# Time Series Transformation
Basic time series transformations include:
  Parsing string dates and convert to datetime64
  Selecting & slicing for specific subperiods
  Setting & changing DateTimeIndex frequency 
    Upsampling vs Downsampling
 
 # Lags, Changess and returns for stock price series
 Typical Time SEries manipulations include:
  Shift or lag values back or forward back in time
  Get the difference in value for a given time period
  Compute the percent change over any number of periods
 pandas built-in mehtods rely on pd.DatetimeIndex
 
