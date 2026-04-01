# 🌍 Angular Country & Weather App

## Project Overview

This is a simple Angular application that allows users to:

* Search for countries
* View detailed country information
* Fetch and display weather information for the capital city

This project is built to practice **Angular basics**, **REST API integration**, and **TypeScript** development.

---

## 🛠 Technologies Used

* **Angular** – Frontend framework
* **TypeScript** – Application logic
* **HTML/CSS** – UI design
* **REST APIs** – For fetching country and weather data

---

## 🚀 Features

1. **Countries List**

   * Fetches a list of countries from a public API
   * Displays country name, flag, and region

2. **Search**

   * Filter countries dynamically using an input box and `ngModel`

3. **Routing**

   * Navigate between countries list and country details page

4. **Country Details Page**

   * Displays capital, population, and currency

5. **Weather Information**

   * Fetch weather data for the capital city
   * Display temperature and weather conditions

6. **Error Handling**

   * Displays user-friendly messages for API errors

7. **UI Improvements**

   * Loader while fetching data
   * Card layout for countries and weather info

---

## 📦 Installation & Setup

1. **Install Angular CLI**

   ```bash
   npm install -g @angular/cli
   ```

2. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd country-weather-app
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Run the application**

   ```bash
   ng serve
   ```

   Open in browser: `http://localhost:4200`

---

## ⚙ API Endpoints Used

* **Countries API:**
  `https://restcountries.com/v3.1/all`

* **Weather API:**
  Example: `https://api.openweathermap.org/data/2.5/weather?q={capital}&appid={API_KEY}`

> Note: Replace `{API_KEY}` with your OpenWeatherMap API key.

---

## 🖼 Screenshots

*(Add screenshots of your app here)*

---

## 📁 Project Structure

```
src/
 ├─ app/
 │   ├─ components/
 │   │   ├─ countries-list/
 │   │   ├─ country-details/
 │   │   └─ weather/
 │   ├─ services/
 │   │   ├─ country.service.ts
 │   │   └─ weather.service.ts
 │   └─ app-routing.module.ts
 ├─ assets/
 └─ styles.css
```

---

## 💡 Bonus Features (Optional)

* Favorites countries list
* Enhanced UI/UX with Material or Bootstrap
* Extra weather info (humidity, wind, sunrise/sunset)

---

## ✅ Submission Checklist

* [x] Working Angular app
* [x] Clean, modular code
* [x] README file with setup instructions

---

## 👨‍💻 Author

* Vani Mekala
