# Weather App using Python

## Overview

This Weather App is a simple Python project that retrieves real-time weather information for a user-specified city using a weather API. The application demonstrates how to work with APIs, send HTTP requests, parse JSON responses, and display weather data in a user-friendly format.

## Features

- Search weather by city name
- Display current temperature
- Display humidity level
- Show weather conditions
- Handle invalid city names and API errors
- Demonstrates API integration and JSON parsing

## Technologies Used

- Python 3
- Requests Library
- OpenWeatherMap API
- JSON Data Format

## Prerequisites

Before running the project, ensure you have:

- Python 3 installed
- Internet connection
- OpenWeatherMap API key

## Installation

1. Clone or download the project.

2. Install the required package:

```bash
pip install requests
```

3. Get a free API key from OpenWeatherMap.

4. Replace:

```python
API_KEY = "YOUR_API_KEY"
```

with your actual API key.

## Project Structure

```text
weather-app/
│
├── weather.py
├── README.md
```
## How It Works

1. User enters a city name.
2. The program sends a request to the OpenWeatherMap API.
3. The API returns weather information in JSON format.
4. The JSON response is parsed using Python dictionaries.
5. Weather details are displayed on the console.

## Example Output

```text
Enter city name: Hyderabad

Weather Information
-------------------
City: Hyderabad
Temperature: 31.2 °C
Humidity: 68 %
Condition: clear sky
```

## Concepts Demonstrated

- API Integration
- HTTP Requests
- JSON Parsing
- Exception Handling
- User Input Handling
- Data Extraction from Dictionaries

## Future Enhancements

- Graphical User Interface (GUI)
- Weather forecast for multiple days
- Current location weather detection
- Weather icons and visualizations
- Save weather history

## Author

Developed as a Python mini-project for learning APIs and JSON parsing.
