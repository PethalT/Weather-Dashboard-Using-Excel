# Weather-Dashboard-Using-Excel
📘 **Project Overview**

This project automates the process of collecting, refreshing, and visualizing daily weather data using the **Visual Crossing Weather API** integrated into **Microsoft Excel**. The dashboard presents live updates for temperature, humidity, wind speed, and precipitation trends, helping users analyze daily and historical weather patterns through an interactive and visually engaging interface.

🚀 **Key Features**
* **API Integration:** Connects directly to the Visual Crossing Weather API for live data updates.
* **Auto Refresh Button**: A VBA-powered button refreshes all data queries instantly within Excel.
* **Dynamic Dashboard**: Interactive charts and KPI cards visualize temperature, humidity, wind speed, and weather conditions.
* **Power Query Automation**: Retrieves and cleans data automatically from the API in CSV format.

🧠 **Tech Stack**
* **Excel (Power Query + VBA)** – for data automation and dashboard creation
* **Visual Crossing Weather API** – for real-time weather data retrieval

⚙️ **How It Works**
1. Power Query fetches fresh weather data daily from the Visual Crossing API.
2. The Excel dashboard processes and visualizes the latest data.
3. A VBA button allows manual refresh on demand (`RefreshWeatherData` macro).
4. Optionally, auto-refresh triggers on file open to keep data current.

📊 **Dashboard Insights**
* **Temperature (°F):** Min, Max, and Average
* **Humidity (%):** Current and comparative analysis
* **Wind Speed (km/h):** Directional and speed trends
* **Precipitation:** Rainfall and weather condition distribution

