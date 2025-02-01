# Live Weather Forecast using Python

## Overview
This Weather App is a Python-based desktop application developed with PyQt5. It enables users to access real-time weather data for any location by integrating with the World Weather Online API. The application provides crucial weather details, including temperature, weather conditions, humidity, wind speed, and visibility.

## Features
- **Intuitive GUI**: Built with PyQt5 for a smooth user experience.
- **Real-Time Weather Data**: Fetches the latest weather updates.
- **Detailed Weather Information**:
  - Temperature
  - Weather conditions
  - Humidity
  - Wind speed
  - Visibility
- **Search Functionality**: Easily look up weather conditions for different locations.
- **Lightweight & Responsive**: Optimized for efficiency and performance.

## Installation
### Prerequisites
Ensure Python is installed on your system along with the required dependencies.


### Install Dependencies
```sh
pip install -r requirements.txt
```

## Usage
Run the application using:
```sh
python weather_app.py
```
### Steps:
1. Enter a location in the input field.
2. Click the "Search" button.
3. View the real-time weather details displayed on the screen.

## API Key
To use this application, you need an API key from World Weather Online. Replace the placeholder API key in the script with your own:
```python
api_key = "your_api_key_here"
```

## Dependencies
- **Python 3.x**
- **PyQt5** (for GUI)
- **Requests** (for API calls)

To install manually, run:
```sh
pip install PyQt5 requests
```


