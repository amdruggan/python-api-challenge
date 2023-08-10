# Python API Challenge

Welcome to the Python API Challenge repository! This repository contains Jupyter Notebook projects that utilize APIs to gather and analyze weather and location data. The two main deliverables in this repository are `WeatherPy.ipynb` and `VacationPy.ipynb`. These notebooks showcase the use of APIs, data analysis, visualization, and more to explore and make sense of various weather and geographical aspects.

## Contents

### WeatherPy.ipynb

In this Jupyter Notebook, you'll find an in-depth analysis of weather data from various cities around the world. The notebook covers the following:

- Generating a list of cities using the `citipy` library.
- Retrieving weather data from the OpenWeatherMap API for each city.
- Storing the weather data in a pandas dataframe and exporting it to a CSV file.
- Creating scatter plots and linear regression analysis for relationships like latitude vs. temperature, humidity, cloudiness, and wind speed.

This notebook provides insights into how weather variables change based on geographical latitude and includes graphical representations of the data.

### VacationPy.ipynb

The `VacationPy.ipynb` notebook extends the analysis from the `WeatherPy.ipynb` notebook and explores ideal vacation spots based on specific weather preferences. Key features of this notebook include:

- Generating a world map with city points scaled by humidity using `hvplot`.
- Filtering cities based on user-defined weather preferences to find ideal vacation destinations.
- Creating a hotel dataframe using the Geoapify API to find the closest hotels to the selected cities.
- Mapping these hotels on a world map and enabling hover functionality for detailed information.

This notebook demonstrates how to combine weather data, user preferences, and geographical information to identify potential travel destinations.

## Getting Started

To use these notebooks, make sure you have the required API keys for OpenWeatherMap and Geoapify. Create a `api_keys.py` file in the main directory and store your API keys as `weather_api_key` and `geoapify_key`.

Feel free to explore, analyze, and modify these notebooks to learn more about data analysis with APIs and geographical data.

## Resources used

These notebooks were generated using code found in StackOverflow, code modified from chat.openai.com, and various other sources, as well as code written by the author. 
