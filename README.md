# 🌤️ Weather Report Web App  

This is a simple **Weather Report Web App** built using **HTML, CSS, and JavaScript**. It fetches real-time weather data using the **OpenWeatherMap API** and displays current weather conditions.  

## 🌍 Live Demo  
🔗 [Weather Report Web App](https://weather-vamsis-projects-7248c4d1.vercel.app/)  

## 📌 Features  
✅ Search for weather details by city name  
✅ Displays temperature, humidity, wind speed, and weather conditions  
✅ User-friendly and responsive UI  
✅ Data fetched from **OpenWeatherMap API**  

## 🚀 Technologies Used  
- **HTML** – Structure of the app  
- **CSS** – Styling for a clean and responsive design  
- **JavaScript** – Fetching and displaying weather data  
- **OpenWeatherMap API** – Provides real-time weather updates  

## 🛠️ How to Use  
1. Open the [live demo](https://weather-vamsis-projects-7248c4d1.vercel.app/).  
2. Enter the name of a city in the search bar.  
3. Click the **Search** button to get the latest weather details.  

## 🔑 API Integration  
This project uses the **OpenWeatherMap API** to fetch weather data. To use it locally, you need an API key:  

1. Sign up at [OpenWeatherMap](https://openweathermap.org/) and get your API key.  
2. Replace `"YOUR_API_KEY"` in your JavaScript code:  
   ```js
   const apiKey = "YOUR_API_KEY";
   const apiUrl = `https://api.openweathermap.org/data/2.5/weather?q=city_name&appid=${apiKey}`;
