# Python API Challenge - What's the Weather Like?

## Background

Created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator by utilizing [Python library - citipy](https://pypi.python.org/pypi/citipy), and the [OpenWeatherMap API](https://openweathermap.org/api), to create a representative model of weather across world cities.

The script does the following : 

* Randomly selects **at least** 500 unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Includes a print log of each city as it's being processed with the city number and city name.
* Saves a CSV of all retrieved data and a PNG and JPEG image for each scatter plot.

## Part I - WeatherPy
Created a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
<br clear = "all">
<table><tr><td>
![](https://github.com/V-MalM/python-api-challenge/blob/main/WeatherPy/output_plots/city_lat_vs_Max_Temp.jpeg">
!(https://github.com/V-MalM/python-api-challenge/blob/main/WeatherPy/output_plots/city_lat_vs_Max_Temp.jpeg">
!(https://github.com/V-MalM/python-api-challenge/blob/main/WeatherPy/output_plots/city_lat_vs_Max_Temp.jpeg">
!(https://github.com/V-MalM/python-api-challenge/blob/main/WeatherPy/output_plots/city_lat_vs_Max_Temp.jpeg">
</td></tr>
</table>
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

The note book "WeatherPy.ipynb" has detailed explanation on what the code is analyzing.

Created a linear regression on each relationship. Created seperate sets of plots for Northern Hemisphere and Southern Hemisphere:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, find explanation on what the linear regression is modeling and other observations, if any.
