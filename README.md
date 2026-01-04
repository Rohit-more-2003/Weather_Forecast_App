# Weather Forecast App 🌤️📈

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-ff4b4b)
![OpenWeather](https://img.shields.io/badge/API-OpenWeatherMap-orange)
![Status](https://img.shields.io/badge/Status-Active-success)

An interactive **weather forecast web application** built with **Streamlit** that displays temperature trends or sky conditions for the next few days using live data from the **OpenWeatherMap API**.

---

## 📌 Project Overview

This project allows users to:
- Enter a city name
- Select the number of forecast days (1–5)
- Choose between **temperature trends** or **sky conditions**
- Visualize the forecast using interactive charts or images

The application fetches real-time forecast data from OpenWeatherMap, processes it using Python, and presents it through a clean Streamlit interface.

---

## 🚀 Features

- City-based weather forecasting
- Forecast range selection (1 to 5 days)
- Temperature visualization using Plotly line charts
- Sky condition visualization using icons
- Real-time data fetched via REST API
- Graceful handling of invalid city names

---

## 🛠️ Tech Stack

| Category | Technology |
|--------|------------|
| Language | Python |
| Frontend | Streamlit |
| Data Visualization | Plotly |
| Backend | Requests (REST API) |
| Weather API | OpenWeatherMap |

---

## 📂 Project Structure

```text
Weather_Forecast_App/
├── main.py             # Streamlit application (UI + visualization)
├── backend.py          # API interaction and data processing
├── requirements.txt
├── images/             # Weather condition icons (clear, cloud, rain, snow)
├── README.md
```

---

## ⚙️ Installation & Setup

git clone <repository_url><br>
cd Weather_Forecast_App

python -m venv venv<br>
source venv/bin/activate      # Linux / macOS<br>
venv\Scripts\activate         # Windows

pip install -r requirements.txt

---

## ▶️ Run the Application

Start the Streamlit app using:

streamlit run main.py
