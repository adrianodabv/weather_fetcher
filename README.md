# Weather Fetcher
Python code using Open Weather API to check the current weather for over 200 cities in the world

## Overview
The Weather Fetcher is a Python script that retrieves current weather information for a specified city using the OpenWeatherMap API. The script provides a simple way to check the weather conditions and temperature in Celsius.

## Features
- Fetches real-time weather data based on user input.
- Displays the weather description with the first letter capitalized.
- Converts the temperature from Kelvin to Celsius.

## Requirements
- `requests` library

## Installation
   ```bash
  pip install requests

**Usage**
1. Run the code
2. When prompted, enter the name of the city you want to check the weather for.
3. The script will display the current weather description and temperature in Celsius.

**Example**
Choose a city to check its weather now: London
Weather: Clear sky
Temperature: 15 Celsius

**API Key
This script uses the OpenWeatherMap API, which requires an API key for access. You can obtain a free API key by signing up at OpenWeatherMap. Replace the API_KEY constant in the script with your own API key.
