# Weather App (PyQt)

A clean and responsive desktop weather application built with **Python** and **PyQt5**, using the OpenWeatherMap API.

## Features
- Search for current weather by city name
- Displays temperature (°C), weather description, and an emoji representing the weather
- Handles common API errors (city not found, unauthorized, server issues)
- Simple, user-friendly interface
- Cross-platform desktop application

## Installation
1. Clone the repository:
  ```bash
  git clone https://github.com/rdesta1/Weather-app.git
  ```
2. Install dependencies:
  pip install -r requirements.txt

3. Add your OpenWeatherMap API key to the 'apikey' variable in main.py

4. Run the app:
  python weather_app.py

Usage:

Enter a city name and click Get Weather (or press Enter)
The temperature, weather description, and emoji will be displayed in the window

What I Learned:

Building GUI applications with PyQt5
Consuming REST APIs in Python
Handling network errors gracefully
Mapping API data to user-friendly output

Next Steps:

Add 5-day weather forecast
Save favorite cities
Improve UI with animations and responsive layout
