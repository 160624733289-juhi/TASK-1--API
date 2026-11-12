# 🌤️ SkyCast – Smart Weather & Tech Dashboard

**SkyCast** is a responsive web application that provides real-time weather information and the latest technology news in one place. It uses public APIs to fetch and display dynamic data, making it easy for users to stay updated with weather conditions and technology trends.

## 🚀 Features

- 🌤️ **Live Weather Updates** – Get real-time weather information for any city.
- 📍 **Location Detection** – Automatically fetch weather based on your current location.
- 🌡️ **Temperature Conversion** – Switch between Celsius (°C) and Fahrenheit (°F).
- 📅 **5-Day Weather Forecast** – View upcoming weather conditions.
- 💧 **Humidity Information** – Check the current humidity percentage.
- 💨 **Wind Speed** – Get real-time wind speed details.
- 📰 **Latest Tech News** – Read trending technology headlines.
- 🔄 **Refresh News** – Reload the latest technology news.
- 🏙️ **Quick City Search** – Quickly check weather in popular cities.
- 📱 **Responsive Design** – Compatible with desktops, tablets and mobile devices.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the webpage |
| CSS3 | Styling and responsive design |
| JavaScript | Functionality and API integration |
| Fetch API | Fetching data from external APIs |
| Open-Meteo API | Weather information and forecasts |
| Hacker News API | Latest technology news |

## 🔗 APIs Used

**1. Open-Meteo API**

Used to retrieve:
- Current temperature
- Humidity
- Wind speed
- Weather conditions
- 5-day weather forecast

API: https://open-meteo.com/

**2. Hacker News API**

Used to retrieve the latest technology-related headlines.

API: https://github.com/HackerNews/API

The project contains HTML, CSS and JavaScript in a single file for easy development and execution.

## ⚙️ How to Run the Project

1. Clone this repository

2. Open the project folder in VS Code.

3. Open `index.html`.

4. Right-click and select **Open with Live Server**.

5. The SkyCast dashboard will open in your browser.

**Note:** An active internet connection is required to fetch live data from the APIs. No API key is required.

## 💡 How It Works

1. The user enters a city name or selects the location detection option.
2. The application uses the Open-Meteo Geocoding API to identify the city's coordinates.
3. The coordinates are passed to the Open-Meteo Weather API.
4. Weather information is fetched and displayed dynamically.
5. The Hacker News API retrieves the latest technology headlines.
6. JavaScript handles API requests, data processing and webpage updates.

## 🎯 Project Objective

The main objective of SkyCast is to demonstrate practical knowledge of API integration, asynchronous JavaScript, dynamic data fetching and responsive web development.

## 🔮 Future Enhancements

- Weather alerts and notifications.
- Hourly weather forecasts.
- Air quality monitoring.
- Weather-based activity recommendations.
- Dark and light mode switching.

## 👩‍💻 Developed As Part Of

**CODTECH Internship – Task 1: API Integration**

**Project:** SkyCast – Smart Weather & Tech Dashboard
