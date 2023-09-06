# Weather-Prediction
This Python project provides a simple command-line interface for retrieving weather forecasts for a specified location using the OpenWeatherMap API. It displays the current temperature in Celsius for the chosen location.

Features:
Retrieve current weather data for a given city.
Display the temperature in Celsius.
Error handling for invalid cities or network issues.
Utilizes the OpenWeatherMap API to fetch weather data.

Prerequisites:
Before you begin, ensure you have met the following requirements:

Python 3.x installed on your machine.
An API key from OpenWeatherMap to access their weather data.

Run the script with your API key and desired city name:

python weather.py --api-key YOUR_API_KEY --city "City Name"
Replace YOUR_API_KEY with your actual OpenWeatherMap API key and "City Name" with the name of the city you want to get the weather forecast for.

Enter the city name to know weather in the specific city and it will run and give you output like this:
-------------------------------------------------------------
Weather Stats for - Hyderabad  || 06 Sep 2023 | 06:20:24 PM
-------------------------------------------------------------
Current temperature is: 31.31 deg C
Current weather desc  : clear sky
Current Humidity      : 52 %
Current wind speed    : 2.3 kmph
