# 🌤️ Weather App

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Language](https://img.shields.io/badge/Language-Kotlin-blue)
![UI](https://img.shields.io/badge/UI-Jetpack%20Compose-orange)
![Architecture](https://img.shields.io/badge/Architecture-MVVM-purple)
![API](https://img.shields.io/badge/API-WeatherAPI-yellow)

A modern Android application built using **Kotlin** and **Jetpack Compose** that provides real-time weather updates for locations worldwide.

This project demonstrates **clean architecture (MVVM)**, **REST API integration**, and **reactive UI design** using the latest Android tools.

---

## 🚀 Features

- 🌍 Real-time weather data (temperature, humidity, UV index, wind speed)
- 🔍 Search weather by city or region
- ⚡ Reactive UI with ViewModel & LiveData
- 🎨 Fully built with Jetpack Compose
- 🖼️ Async image loading using Coil
- 🔄 Clean state management (Loading, Success, Error)

---

## 📸 Screenshots

| Search Screen | Loading State | Weather Details |
|--------------|-------------|----------------|
| *(Add Image)* | *(Add Image)* | *(Add Image)* |

> 💡 Tip: Upload screenshots to GitHub and replace placeholders with image links.

---

## 🛠️ Tech Stack

| Layer            | Technology Used              |
|------------------|----------------------------|
| Language         | Kotlin                     |
| UI Framework     | Jetpack Compose            |
| Architecture     | MVVM                       |
| Networking       | Retrofit + Gson            |
| Image Loading    | Coil                       |
| State Handling   | ViewModel + LiveData       |
| Build System     | Gradle (Kotlin DSL)        |

---

## 📁 Project Structure
```
com.example.weather
│
├── api/
│ ├── WeatherApi
│ ├── RetrofitInstance
│ └── NetworkResponse
│
├── ui/
│ ├── theme/
│ ├── WeatherViewModel
│ └── WeatherPage
│
└── MainActivity
```
---

## ⚙️ Setup & Installation
### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Rohitkumarpradhan/Weathring.git
```
### 2️⃣ API Key Setup

This project uses WeatherAPI.

Sign up at https://www.weatherapi.com/

Generate your API key

Replace it in:
```
com.example.weather.api.Constant.kt
```
### 3️⃣ Run the App
Open project in Android Studio (Ladybug or newer)
Sync Gradle
Run on Emulator or Physical Device

---------

## 🌐 Future Scope
📍 Location-based weather (GPS integration)

📅 7-day / hourly forecast

🌙 Dark mode support

🔔 Weather alerts & notifications

🌐 Web version (for browser users)

-----------
## 🤝 Contributing

Contributions are welcome!
### Fork the repo
### Create new branch
```
git checkout -b feature/AmazingFeature
```
### Commit
```
git commit -m "Add AmazingFeature"
```
### Push
```
git push origin feature/AmazingFeature
```
------
Built with ❤️ using Kotlin & Jetpack Compose
---
