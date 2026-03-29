# 🌱 Smart Irrigation System Simulator

## 🚀 Overview

This project is a real-time irrigation simulation dashboard built
using Streamlit and Plotly.\
It simulates multiple plants, monitors soil moisture, and automatically
controls watering pumps.

------------------------------------------------------------------------

## 🎯 Features

-   🌿 Multi-plant monitoring (Tomato, Tulsi, Cactus, etc.)
-   💧 Automatic irrigation system (Pump ON/OFF)
-   🌡️ Real-time environment simulation (Temp, Humidity, Light, Wind)
-   📊 Interactive charts using Plotly
-   🧠 Smart logic based on thresholds
-   🎛️ Adjustable controls (threshold, drain speed, water rate)
-   📜 Event logging system

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   Python
-   Streamlit
-   Plotly
-   Random simulation logic

------------------------------------------------------------------------

## 📦 Installation

### 1. Install dependencies

``` bash
python -m pip install streamlit plotly
```

### 2. Run the app

``` bash
python -m streamlit run app.py
```

------------------------------------------------------------------------

## ⚙️ How It Works

1.  Each plant has a moisture level
2.  Moisture decreases over time (evaporation)
3.  If moisture \< threshold → Pump ON
4.  Pump adds water until safe level → Pump OFF
5.  All activity is logged

------------------------------------------------------------------------

## 📊 Dashboard Sections

-   Hero Section → Overview stats
-   Plant Dashboard → Individual plant cards
-   Analytics → Graphs & charts
-   Statistics → Insights & usage
-   Event Log → System activity

------------------------------------------------------------------------

## 💡 Use Cases

-   Smart Farming simulation
-   IoT learning project
-   College mini-project
-   Research prototype

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Real sensor integration (Arduino / ESP32)
-   Mobile alerts
-   Cloud data storage
-   AI-based irrigation prediction

------------------------------------------------------------------------

## 👨‍💻 Author

Made for learning + project purposes 😄
