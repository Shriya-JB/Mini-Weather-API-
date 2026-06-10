# Mini-Weather-API-
A simple web-based weather application that fetches real-time weather data using WeatherAPI based on user-entered city names. It displays current temperature, weather conditions, and location in a clean and responsive interface.



# 🌦️ Weather App (HTML, CSS, JavaScript)

## 📄 Description

A responsive and beginner-friendly weather application that fetches real-time weather data using WeatherAPI. Users can enter any city name to view current temperature, weather conditions, and location details in a clean and interactive UI.

This project demonstrates core frontend concepts such as API integration, asynchronous JavaScript, DOM manipulation, and dynamic UI updates without page reload.

---

## 🚀 Features

- Search weather by city name  
- Real-time temperature display (°C)  
- Weather condition description (sunny, cloudy, rainy, etc.)  
- Weather icon support  
- Clean dark-themed UI  
- Error handling for invalid input and API failures  
- Lightweight (no frameworks used)

---

## 🧠 How It Works

1. User enters a city name  
2. JavaScript captures input  
3. API request is sent using `fetch()`  
4. JSON response is received  
5. Required data is extracted  
6. UI updates dynamically with weather information  

---

## 🌐 API Used
This is the API endpoint provided by WeatherAPI, used to connect the application and retrieve weather data for performing required operations: 

http://api.weatherapi.com/v1/current.json?key=906111169c4b437e9d971536261006&q=London&aqi=yes



Weather App
│
├── index.html → UI structure
├── style.css → Styling
└── script.js → Logic (API + DOM handling)
