# 🌦️ SkyCast - Android Weather App

SkyCast is a simple and clean Android weather app built with **Kotlin** using **Retrofit** and **OpenWeatherMap API**. It fetches real-time weather data for any city and provides current temperature, weather condition, humidity, wind speed, pressure, and sunrise/sunset times.

![Made with Kotlin](https://img.shields.io/badge/Made%20with-Kotlin-7F52FF.svg?style=for-the-badge&logo=kotlin)


---

## 📱 Screenshots

<img width="200" alt="Screenshot 2025-06-06 at 11 04 06 AM" src="https://github.com/user-attachments/assets/1dec9eef-ffc1-4bb6-a401-35519c267cef" /> &nbsp;&nbsp;&nbsp;
<img width="200" alt="Screenshot 2025-06-06 at 11 04 11 AM" src="https://github.com/user-attachments/assets/c83cfdaa-585d-4adc-98ac-1191a1063deb" /> &nbsp;&nbsp;&nbsp;
<img width="200" alt="Screenshot 2025-06-06 at 11 05 17 AM" src="https://github.com/user-attachments/assets/ca4013ec-aaae-499b-b85e-3857928d92fe" />

---

## 🚀 Features

- Search weather by city name
- Displays:
  - Temperature (current, min, max)
  - Weather condition
  - Humidity
  - Wind speed
  - Sea level pressure
  - Sunrise & sunset times
- Automatically sets background and animation based on weather condition
- Clean UI with day and date info

---

## 🔧 Tech Stack

- **Kotlin**
- **Retrofit2** for API calls
- **Gson** for JSON parsing
- **Lottie** for weather animations
- **View Binding**
- **OpenWeatherMap API**

---

## 🔑 API Reference

Weather data is powered by [OpenWeatherMap](https://openweathermap.org/api)

- Base URL: `https://api.openweathermap.org/data/2.5/`
- Required parameters:
  - `q` = City name
  - `appid` = Your API key
  - `units` = `metric`
  - 
---

## 🛠️ Setup & Run Locally

1. Clone the repository.
2. Add your OpenWeatherMap API key inside `fetchWeatherData()` function:
   ```kotlin
   val response = retrofit.getWeatherData(cityName, "YOUR_API_KEY", "metric")
3. Run the app on an Android emulator or physical device.

---

## 💬 Contact & Support

For any queries or feedback, feel free to connect:

📧 Email: [badalsh908@gmail.com](mailto:badalsh908@gmail.com)  
🐙 GitHub: [github.com/badalm06](https://github.com/badalm06)



