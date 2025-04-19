Weather and Temperature Conversion App
Overview
This is a simple yet functional weather and temperature converter application built using HTML, CSS, and JavaScript. It allows users to:

Check real-time weather information for any city using the OpenWeatherMap API.

Convert temperature values between Celsius and Fahrenheit.

Features
1. Weather Checker (index.html)
Users can input a city name to fetch current weather data.

Displays:

City Name

Temperature in Celsius

Humidity Level

Weather Description

A symbolic representation (using Unicode characters) of weather conditions

2. Temperature Converter (temp.html)
Users can enter a temperature value and choose:

Convert from Celsius to Fahrenheit

Convert from Fahrenheit to Celsius

Clean design and quick results

File Structure
index.html: Main weather application

temp.html: Temperature conversion utility

Weather data is fetched using the OpenWeatherMap API


Uses Fetch API for retrieving data from OpenWeatherMap

Notes
The weather display uses simple Unicode icons instead of images.

The app performs basic error handling if the API fails or the input is empty.

Temperature from the API is returned in Kelvin and converted to Celsius manually.
