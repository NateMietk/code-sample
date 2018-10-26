## Code Sample
### Created by Nathan Mietkiewicz
### October 26, 2018

#### General Flow and Purpose
This code sample is intended to be a reproducible example of downloading, processing, and visualizing climate time series across the conterminous US.  In this code we will explore a monthly time series of precipitation data from the GridMET data product (http://www.climatologylab.org/gridmet.html). We will transform these raw precipitation data into precipitation anomalies, which is just a simple deviation from the long term mean. By transforming into anomalies we can better understand how much increase of decrease precipitation is occurring across space and time, and how different those deviations are from the long term mean. At the very end we will extract the mean precipitation anomalies across defined regions in the conterminous US and create a series of time series plots.
