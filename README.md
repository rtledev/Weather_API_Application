A desktop weather application built with **Python** and **PyQt5** that allows users to enter a city name and retrieve real-time weather data using the **OpenWeatherMap API**.

## Features

- Desktop GUI built with **PyQt5**
- Real-time weather lookup by city
- Displays:
  - Temperature
  - Weather condition description
  - Weather emoji/icon representation
- Handles multiple HTTP and network-related errors
- Uses environment variables to protect API credentials

## Technologies Used

- **Python**
- **PyQt5**
- **Requests**
- **OpenWeatherMap API**
- **dotenv**

## Project Structure

This project is currently written in a **single Python file**.

```bash
Weather_API_App.py
```

## API Key Setup

This project uses the OpenWeatherMap API.

1. Create a free account at https://openweathermap.org/api
2. Generate an API key
3. Create a `.env` file in the project root
4. Add the following:

OPENWEATHERMAP_API_KEY=your_api_key_here
