# Module-6-Challenge_python-api-challenge

WeatherPy problem
----------------------------
Created a Python script using Jupyter Notebook within VS Code for the WeatherPy problem that read in the citipy data, connected to the OpenWeatherMap API, and performed the following analysis:

* Used OpenWeatherMap API to retrieve weather data for city list
* Created Scatter Plots for the followng:
  * Latitude vs. Temperature
  * Latitude vs. Humidity
  * Latitude vs. Cloudiness
  * Latitude vs. Wind Speed
* Computed Linear regression for the following relationships:
  * Northern Hemisphere: Temperature vs. Latitude
  * Southern Hemisphere: Temperature vs. Latitude
  * Northern Hemisphere: Humidity vs. Latitude
  * Southern Hemisphere: Humidity vs. Latitude
  * Northern Hemisphere: Cloudiness vs. Latitude
  * Southern Hemisphere: Cloudiness vs. Latitude
  * Northern Hemisphere: Wind Speed vs. Latitude
  * Southern Hemisphere: Wind Speed vs. Latitude

VacationPy problem
----------------------------
Created a Python script using Jupyter Notebook within VS Code for the VacationPy problem that read in the cities.csv file, connected to the Geoapify API, and performed the following analysis:

* Created a map that displays every city in the city_data_df DataFrame, where the size of the point is the humidity in each city
* Paired down the city_data_df DataFrame to ideal weather conditions
* Used Geoapify API to find the first hotel located within 10,000 meters of each city in paired down list
* Created a map with the previous city/hotel list
