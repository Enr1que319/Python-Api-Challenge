# Weather Analysis

[![](Img/weather.jpg)]()    

## Introduction

In this project the climate was thoroughly analyzed in order to find patterns. This is divided into two:
- WeatherPy
- VacationPy

Each chart of each project have the conclusions in the jupyter notebooks

## Data

The data was provided by [OpenWeatherMap](https://openweathermap.org/api)

## WeatherPy

In this part of the project a python scripts were created to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this simple Python libraries were used, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

The objective is to build a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

After that the next step was run linear regression on each relationship and then separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

At the end this jupyter notebook  have:
- A selection of randomly 500 unique (non-repeat) cities based on latitude and longitude.
- A weather check on each of the cities using a series of successive API calls.
- A print log of each city as it's being processed with the city number and city name.
- A PNG image for each scatter plot.






