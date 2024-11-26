# Module 6: Python APIs

## Overview
In this module, you explored the use of APIs to retrieve and analyze real-world data programmatically. APIs, or Application Programming Interfaces, allow applications to communicate and exchange data effectively. Using Python libraries like `requests` and JSON parsing techniques, you performed tasks such as obtaining weather data, visualizing data, and working with geospatial datasets.

## Learning Objectives
By the end of this module, you will be able to:
- Make `GET` requests using Python's `requests` library.
- Parse and process JSON data into Python dictionaries and DataFrames.
- Work with API documentation to understand endpoints and parameters.
- Use APIs like OpenWeatherMap, Geoapify, and the U.S. Census API for retrieving data.
- Handle exceptions and edge cases using `try-except` blocks.
- Create data visualizations using Matplotlib and GeoViews.

## Deliverables

### Part 1: WeatherPy
In this section, you used the OpenWeatherMap API and Python to analyze the weather data of over 500 cities worldwide.

#### Key Tasks:
1. **Create Scatter Plots:**
   - Latitude vs. Temperature
   - Latitude vs. Humidity
   - Latitude vs. Cloudiness
   - Latitude vs. Wind Speed

2. **Compute Linear Regression:**
   - For each relationship above, compute and display the linear regression model separately for the Northern and Southern Hemispheres.
   - Include the r² value and the regression equation on the plot.

#### Output:
- A series of scatter plots visualizing weather variables against latitude.
- Observations about trends, such as how weather variables correlate with geographic latitude.

---

### Part 2: VacationPy
In this section, you worked on identifying ideal vacation locations based on weather conditions and creating an interactive map.

#### Key Tasks:
1. **Identify Ideal Locations:**
   - Filter cities where:
     - Maximum temperature is between 21°C and 27°C.
     - Wind speed is below 4.5 m/s.
     - Cloudiness is 0%.

2. **Use Geoapify API:**
   - Retrieve nearby hotel names for the filtered cities using the Geoapify API.
   - Add the hotel name and country information to a new DataFrame.

3. **Create Interactive Maps:**
   - Use GeoViews and Python to display the locations on a map, where:
     - Point size indicates humidity.
     - Hover information shows city, hotel, and weather details.

#### Output:
- A map visualization showcasing ideal vacation spots with added hotel and weather data.

---

## Technologies Used
- **Python Libraries:**
  - `requests` for making API calls.
  - `json` for parsing API responses.
  - `pandas` for data manipulation.
  - `matplotlib` for data visualization.
  - `geopandas` and `GeoViews` for geospatial data visualization.
- **APIs:**
  - OpenWeatherMap API
  - Geoapify API
  - U.S. Census API

## Summary
This module focused on leveraging APIs to gather, analyze, and visualize data effectively. By working through WeatherPy and VacationPy, you enhanced your understanding of working with JSON data, creating meaningful plots, and handling geospatial datasets for practical applications.
