# aqi-fires-california
Visualization of Air Quality Index (AQI) and fires in Northern California between 2002 and 2020.

**Files:**   
  In the GIFS file there are two .gif animations, one for [San Jose](https://github.com/sfamacochrane/aqi-fires-california/blob/main/GIFS/SanJose.gif) and one for [Sacramento](https://github.com/sfamacochrane/aqi-fires-california/blob/main/GIFS/Sacramento.gif).  
  The Data file contains the .csv files which run in the python code to create the GIFS. AQI data came from the EPA (https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI), and fire data came from wikipedia for each year (for example, https://en.wikipedia.org/wiki/2020_California_wildfires).   
  The Python code file contains jupyter notebooks with code for San Jose and Sacramento, and for both cities (1) a version that creates a gif (ends in GIF) and (2) a version that makes an animation in the jupyter notebook environment ('ANIMATION'). 

**Comments:**   
In the visualization, fires in Northern California are represented with light gray bars spanning the dates the fire was active. Darker gray indicates that more than one fire was active at that time; the darker the gray, the more fires were active on that date. Higher AQI is unhealthier, but the AQI data here do not distinguish between cause of the AQI reading (ozone, SO2, PM2.5, PM10, etc), so not all high AQI days are due to smoke. 

This visualization was created by Sally Fama Cochrane as a project for the Coursera course, "Applied Plotting, Charting, and Data Representation in Python" by the University of Michigan. You can reach me at cochrane.sally(at)gmail(dot)com.
