# 🌤️ Weather App

A responsive weather application built with **React** and **Vite** that provides current weather information for searched locations using the **OpenWeather API**.


## 🔗 Live Demo

[View Weather App](https://weather-appinfo.vercel.app/)


## ✨ Features

- 🌍 Search weather by city
- 🌡️ Displays current temperature
- ☁️ Displays current weather conditions
- 💧 Shows humidity
- 💨 Shows wind speed
- ⏳ Loading state while fetching weather data
- ⚠️ Error handling for invalid locations
- 📱 Responsive design


## 🛠️ Tech Stack

- React
- JavaScript
- Vite
- CSS
- OpenWeather API


## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/sayak027/weather-app.git
```

### 2. Navigate to the project directory

```bash
cd weather-app
```

### 3. Install dependencies

Install all the required dependencies for the project:

```bash
npm install
```

### 4. Configure the API key

Create a .env file in the project root directory and add your OpenWeather API key:

```text
VITE_WEATHER_API_KEY=your_api_key_here
```

🔒 Keep your API key private and never commit the .env file to GitHub.


### 5. Start the development server

Run the following command:

```bash
npm run dev
```

The terminal will provide a local development URL, usually:

```
http://localhost:5173
```

Open the URL in your browser to start using the application.


## 📦 Build for Production

Create an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```


## 🌐 API

This project uses the **OpenWeather API** to fetch current weather data based on the searched city.


## 🎯 Purpose

This project was built to practice and demonstrate:

- React development
- API integration
- Asynchronous JavaScript
- Loading and error handling
- Working with environment variables
- Responsive UI development


## 📁 Project Structure

```
weather-app/
├── public/
├── src/
├── .env
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── README.md
└── vite.config.js
```


⭐ If you find this project useful, consider giving it a star!


