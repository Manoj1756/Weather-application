# Weather Application

This is a simple weather application built using Django. The app allows users to search for the weather forecast of a specific location by entering the city name.

## Prerequisites

- Python 3.x installed on your machine.
- Django framework installed (use `pip install django` to install Django).

## Installation

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd weather_application`

## Usage

1. Run the development server:
2. Open your web browser and go to `http://localhost:8000/` to access the weather application.

## API Key

This weather application uses a weather API to fetch weather data. You'll need to sign up for an API key from a weather service provider (e.g., OpenWeatherMap, WeatherAPI) and include it in the application to make API requests.

Replace `'YOUR_API_KEY'` in the `views.py` file with your actual API key:

```python
# views.py

API_KEY = 'YOUR_API_KEY'
