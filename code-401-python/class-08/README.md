## Read8

## What is pandas in python?

#### pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive

# ---------------

## What is difference between NumPy and pandas?

#### NumPy library provides objects for multi-dimensional arrays, whereas Pandas is capable of offering an in-memory 2d table object called DataFrame

# ----------------

## What is Data Frame?

#### A DataFrame is a 2-dimensional data structure that can store data of different types (including characters, integers, floating point values, categorical data and more) in columns.

# ----------------

## How do I create plots in pandas?

#### import pandas as pd
#### import matplotlib.pyplot as plt
#### air_quality = pd.read_csv("data/air_quality_no2.csv", index_col=0, parse_dates=True)
#### air_quality.head()
#### Out[4]: 
####  station_antwerp  station_paris  station_london
#### datetime                                                           
#### 2019-05-07 02:00:00              NaN            NaN            23.0
#### 2019-05-07 03:00:00             50.5           25.0            19.0
#### 2019-05-07 04:00:00             45.0           27.7            19.0
#### 2019-05-07 05:00:00              NaN           50.4            16.0
#### 2019-05-07 06:00:00              NaN           61.9             NaN
#### air_quality.plot()
#### Out[5]: <AxesSubplot: xlabel='datetime'>
#### plt.show()
#### air_quality["station_paris"].plot()
#### <AxesSubplot: xlabel='datetime'>
#### plt.show()
#### air_quality.plot.scatter(x="station_london", y="station_paris", alpha=0.5)
#### Out[9]: <AxesSubplot: xlabel='station_london', ylabel='station_paris'>
#### plt.show()
#### In [11]: [
#### ....:     method_name
#### ....:     for method_name in dir(air_quality.plot)
#### ....:     if not method_name.startswith("_")
#### ....: ]
#### ....: 
#### Out[11]: 
#### ['area',
#### 'bar',
#### 'barh',
#### 'box',
#### 'density',
#### 'hexbin',
#### 'hist',
#### 'kde',
#### 'line',
#### 'pie',
#### 'scatter']