# Surfs_up

Advanced Data Storage and Retrival to determine project feasibility

## Purpose

1.	Explain the structures, interactions, and types of data of a provided dataset.
2.	Differentiate between SQLite and PostgreSQL databases.
3.	Use SQLAlchemy to connect to and query a SQLite database.
4.	Use statistics like minimum, maximum, and average to analyze data.
5.	Design a Flask application using data.

## Overview

We are looking to start a Surf and Icecream shop in Oahu and investors interested in the business wants more data and results to make an informed decision. Their main concern is the precipitation in the weather as in the past due to heavy rain, their investments had failed. 

For analysing the data, we have used SQLAlchemy to extract data in python. 

## Results

  1. The temperatures in June is slightly higher at an average of 75 as compared to 71 in December. This can be seen in the table below. Similarly the high and low temperatures are also higher in June at 85 and 64 as compared to 83 and 56 respectively. Clearly December temperatures are lower posing a possible threat to the business.

![temperature](https://user-images.githubusercontent.com/108366412/188028271-ca07b913-fd24-4786-b454-4720dc71223a.png)

2.  Histograms showing temperatures in the month of June and December are shown below. It gives us a visual representation of the temperature over the month of June and December. For June, 75 is the temperature for maximum number of days followed by 80 and then 70. The graph is much more constrained between 70-to-80-degree temperatures. For December, 70 is the temperature for maximum number of days followed by 75. Graph is spread out between 65 to 80 and is spread evenly as compared to June month graph. 
  
![temperature_histogram](https://user-images.githubusercontent.com/108366412/188028286-a68850e2-cb2f-4421-a7f8-0b4bf263783d.png)

3. To clear out the doubts relating to precipitation, we ran precipitation data for the month of June and December along with temperatures. Following is the tables comparing June and December. From the table below, precipitation in the month of June is having a lower average at 0.136 as compared to December which is at 0.217. The Maximum precipitation level is also higher in December at 6.42 as against 4.43 in June.

![precipitation](https://user-images.githubusercontent.com/108366412/188028469-15f7619c-c4f0-4d28-92ab-c9353c3116c0.png)

Similar pattern can be seen in Histogram charts below showing more days with higher precipitation in December as compared to the month of June. Some days in December are having precipitation at 3,4,5 and 6 level. Whereas, Month of June has negligible days with precipitation between 2.5 and 4. 

![precipitation_histogram](https://user-images.githubusercontent.com/108366412/188028557-34139c6e-dbe9-44f4-bc58-b51cd90e6983.png)

## Summary

To summarise we ran a scatter plot with temperatures and precipitation for June and December and found that as the temperature goes higher, the precipitation goes down. Both the scatter plots show a downward trend i.e. as the temperature rises, level of precipitation decreases. Also the scatter plot for December is more spread out as compared to June which suggests that there is higher chance of days with high precipitation and more deviationand outliers in the month of December as compared to June. 

![scatter_comparison](https://user-images.githubusercontent.com/108366412/188028642-346be0e7-0d81-4da6-a172-5eea04f09da8.png)

Overall, there is not much difference in temperatures and precipitation in both months and deviations is also not that high. There should be less chance of the business being washed out due to rain. Results from the collected data totally support opening the Surfs and Icecream shop as the weather is favourable. 
