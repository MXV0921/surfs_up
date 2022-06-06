# Surfs Up Challenge

## Overview of the analysis: 

Using Jupyter Notebook we utilized Python coding, specifically SQLAlchemy to create an engine and extract data to review weather statistics.  We filtered the session by writing a query that utilized the extract function to view our data by selected months.

## Results: 

### June Results
* Our results from June retrieved 1700 temperatures taken from 2010-2017.
* There was fairly consistent temperatures record, the lowest was 64 and the maximum was 85.
* The interquartile range only had a 4 degree variance, 73-77

![June_Descriptor](https://github.com/MXV0921/surfs_up/blob/main/June_describe.png)
![June_Histogram](https://github.com/MXV0921/surfs_up/blob/main/June_histogram.png)

### December Results
* Our results from December retrieved 1517 temperatures taken from 2010-2016
* There is a larger temperature variance in December, the lowest was 56 and the max was 83.
* After plotting a histogram we see that there was a very large spike of days with almost 350 days of 71 degree temperatures.
![Dec_Descriptor](https://github.com/MXV0921/surfs_up/blob/main/Dec_describe.png)
![Dec_Histogram](https://github.com/MXV0921/surfs_up/blob/main/Dec_histogram.png)

## Overview of the statistical analysis:

Our customer is looking for a weather analysis when looking to open a surf and ice cream shop for tourists in Hawaii.  We are utlizing local weather data for the island of Oahu to help determine success of this venture.

## Results:
* There is a small variance of average temperature throughout the year.  ~75 degrees in the June  and ~71 degrees in December.
* The weather recorded is between 70-75 degrees for a large portion of the dates taken.
* The maximum recorded temperature only changed by 2 degrees.

## Summary:

This initial study that we performed gave promising results however we would need to investigate our data more by looking deeper into the dataset we have.  
* While Oahu is not a large island, it would be prudent for us to utilize additional filters to see where the best weather would be best for us to open.
* By looking at the data we are only seeing a daily result.  If we are opening an ice cream stand it is important to look at the time of day that these temperatures were taken.  Temperatures taken overnight or during the morning would have little impact on our sales.
