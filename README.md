# Python API - What's the Weather Like?

## Part I - WeatherPy

In this part, I created a Python script to visualize the weather of 500+ cities across the world, at varying distances from the equator. 

* Temperature (F) vs. Latitude
![tempvslat](WeatherPy/output_data/LatVsTempPlot.png)

* Humidity (%) vs. Latitude
![humidityvslat](WeatherPy/output_data/LatVsHumidityPlot.png)

* Cloudiness (%) vs. Latitude
![cloudinessvslat](WeatherPy/output_data/LatVsCloudinessPlot.png)

* Wind Speed (mph) vs. Latitude
![windvslat](WeatherPy/output_data/LatVsWindSpeedPlot.png)

The second requirement is to run linear regression on each relationship. This time, the plots are separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Temperature (F) vs. Latitude - Northern Hemisphere
![tempvslatnh](WeatherPy/output_data/TempVsLatPlotNH.png)

* Temperature (F) vs. Latitude - Southern Hemisphere
![tempvslatsh](WeatherPy/output_data/TempVsLatPlotSH.png)

* Humidity (%) vs. Latitude - Northern Hemisphere
![humidityvslatnh](WeatherPy/output_data/HumidityVsLatPlotNH.png)

* Humidity (%) vs. Latitude - Southern Hemisphere
![humidityvslatsh](WeatherPy/output_data/HumidityVsLatPlotSH.png) 

* Cloudiness (%) vs. Latitude - Northern Hemisphere
![cloudinessvslatnh](WeatherPy/output_data/CloudinessVsLatPlotNH.png)

* Cloudiness (%) vs. Latitude - Southern Hemisphere
![cloudinessvslatsh](WeatherPy/output_data/CloudinessVsLatPlotSH.png) 

* Wind Speed (mph) vs. Latitude - Northern Hemisphere
![windvslatnh](WeatherPy/output_data/WindSpeedVsLatPlotNH.png)

* Wind Speed (mph) vs. Latitude - Southern Hemisphere
![windvslatsh](WeatherPy/output_data/WindSpeedVsLatPlotSH.png) 


## Part II - VacationPy

Used jupyter-gmaps and the Google Places API for this part of the assignment.

To complete this part of the assignment, I did the following:

* Created a heat map that displays the humidity for every city from Part I.

* Narrowed down the DataFrame to find ideal weather condition. 

* Used Google Places API to find the first hotel for each city located within 5000 meters of that coordinates.

* Plotted the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

