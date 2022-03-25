# PyBer_Analysis
---
## Overview
---
### Purpose:

  PyBer, a Python-based ride sharing app company, has hired us to perform an analysis on ride sharing data in order to showcase: the relationship between the type of city and number of drivers and riders as well as the percentage of total fares, riders, and drivers by type of city. Our analysis and visualizations were then presented to the CEO, V. Isualize, in order to help improve access to ride sharing services and determine affordability for underserved neighborhoods. 

  After completing the exploratory analysis, V. Isualize has given us a new assignment to complete a more thorough inspection of the ride sharing data. We will now use Python programming in order to create a summary of the ride-sharing data by city type. From that summary table we will use Pandas and Matplotlib libraries to create a multiple-line graph that shows the total weekly fares for each city type. The new visualization will allow to us to report more observations for V. Isualize on how the data differs by city type and how those differences can be used by decision-makers at PyBer.

---
## Analysis
---
### Results:

  From the Pyber Summary DataFrame we can observe a negative correlation relating to population density and average fares. Urban city type, a more densely populated area, had more total drivers and total rides with each category outnumbering the closest city type, Suburban, by at least double its size. As a result of the largest supply of total drivers, Urban drivers had the lowest average fare per ride and earned the least compared to drivers in the other two city types.

  Consequently, on the other end of the density spectrum, Rural drivers had a tremendous advantage as it relates to average fares. Rural total rides and total drivers were both the smallest by a significant margin as compared to the other two city types. The lowest supply of total drivers enabled them to economically produce the highest average fare per driver.

Pyber Summary DataFrame

<img width="598" alt="PyBer_Summary_DataFrame" src="https://user-images.githubusercontent.com/99817571/160156024-ae019661-bf28-4b6f-b29a-9ea90b3ef059.png">

  From the Total Fare by City Type Graph, which charts total fares by city type for each week from January to May of 2019, we can observe a similar pattern as seen in our Pyber Summary DataFrame. Urban Total Fares were the highest throughout the entirety of the timeframe and Rural Total Fares were the lowest. However, for all three city types the total fares did not dramatically rise or drop throughout with each reaching its peak at the end of February and then oscillating below that peak until the end of April where the Suburban and Rural city types start to peak again.

![PyBer_fare_summary](https://user-images.githubusercontent.com/99817571/160158329-696ff9b7-a207-4da7-8089-a3c49cd5d7da.png)

---
## Summary
---
### Strategic Recommendations

  Based on the findings for each city type highlighted in our Summary DataFrame and Total Fares by City Type Chart the recommendatios are as followed:

  1. PyBer should focus on implementing a program that can incentivize drivers to work in Rural areas because of the large disparity between Urban and Rural city types, which has affected access to drivers for riders. 
  
  2. PyBer should conduct a subsequent study on Urban drivers and their earnings. There is a substantial pool of drivers in Urban areas compared to total rides, which may be affecting individual drivers’ ability to make livable wages.  If so, PyBer could look into increasing service fees to support drivers. 
  
  3. PyBer should conduct a larger scope analysis on average fares as it relates to months of the year over several years of data in order to better understand peak fares for each city type. From there Pyber could focus on creating media campaigns in order to maximize profits for drivers by enticing more riders to user their rider sharing app.

---
## Resources
---
Data Source: city_data.csv, ride_data.csv

Software: Python 3.7.6, Jupyter Notebook 6.4.5
