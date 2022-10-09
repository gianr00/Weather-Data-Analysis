# Weather Data Analysis: What's the weather like as we approach the equator?

Author: Rosie Gianan, gianr00@gmail.com

Build With: Python, Python API’s, JSON, Pandas, Numpy, Matplotlib, API Requests 

## Goals:
1.    Visualize the weather of 500+ cities of varying distance from the equator using [simple Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api).  Create the representative model of weather across cities.
2.    Visualize the weather data to help plan for future vacations using Jupyter-gmaps and the Google Places API.

## Solutions:
1.    Build a visualization and plotting scripts for the 500 + cities of varying distance from the equator.
-    Create a random list of cities of varying distance from the equator and retrieves the weather data from OpenWeatherMap API for each city
-    Saves the city data into a dataframe and exports them into csv file.
-    Visualizes the weather of the list of cities using scatter plots and linear regression

Visualization Plots:

<img src="output_data/fig01_Latitude_vs_Temperature.png" width="400"> <img src="output_data/fig02_Latitude_vs_Humidity.png" width="400">
<img src="output_data/fig03_Latitude_vs_Cloudiness.png" width="400">
<img src="output_data/fig04_Latitude_vs_WindSpeed.png" width="400">
<img src="output_data/fig05_Northern_Max_Temp_vs_Latitude.png" width="400">
<img src="output_data/fig06_Southern_Max_Temp_vs_Latitude.png" width="400">
<img src="output_data/fig07_Northern_Humidity_vs_Latitude.png" width="400">
<img src="output_data/fig08_Southern_Humidity_vs_Latitude.png" width="400">
<img src="output_data/fig09_Northern_Cloudiness_vs_Latitude.png" width="400">
<img src="output_data/fig10_Southern_Cloudiness_vs_Latitude.png" width="400">
<img src="output_data/fig11_Northern_Wind_Speed_vs_Latitude.png" width="400">
<img src="output_data/fig12_Southern_Wind_Speed_vs_Latitude.png" width="400">
