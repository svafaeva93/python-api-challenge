# Python-API - Weather Analysis and Choosing a Vacation Location  

Background
In this assignment, I was aksed to use my knowledge of Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"
Even though the answer may seem obvious, here I have used a detailed approach to answer this question. 

Part 1: WeatherPy
In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and some problem-solving skills to make a representative model of weather across cities. 

I made some scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Next, I computed the linear regression for each relationship and created linear regression plots, including these: 

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

Part 2: VacationPy

In this deliverable, I used my weather data skills to plan out future vacations. Using Jupyter notebooks, the geoViews Python library, and the Geoapify API I created map visualizations.

Here's the map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point displays the humidity in each city.
![Map_1](https://user-images.githubusercontent.com/124627601/231825880-344fba74-9fe6-49ee-b7a7-679ae25cac64.png)
