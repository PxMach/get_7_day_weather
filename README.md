Paris Weather Analysis 🌤️📊:

A small Python project that retrieves weather data from the past 7 days for Paris using the free Open-Meteo API.
The data is processed with pandas, visualized with matplotlib, and saved to a CSV file.

📌 Features:

-Fetch weather data from an API

-Analyze minimum and maximum temperatures

-Generate a temperature chart

-Save data to a CSV file

-Organize data using a pandas DataFrame

🛠 Technologies Used:

-Python

-requests

-pandas

-matplotlib

-Open-Meteo API

📂 Project Structure

get_7_day_weather
│
├── main.py
├── weather_chart.png
├── README.md
│
└── data
    └── paris_weather.csv

⚙️ Installation

Clone the repository:
-git clone https://github.com/your-username/get_7_day_weather.git
-cd get_7_day_weather

Install the required dependencies:
-pip install requests pandas matplotlib

🚀 Usage

Run the program:
-python main.py

The program will:

1-Fetch temperature data from the past 7 days for Paris

2-Generate a temperature chart

3-Save the data to a CSV file

4-Display the data in the terminal

📊 Generated Chart

The program generates a file:
-weather_chart.png

This chart shows:

-Maximum temperature

-Minimum temperature

-Over the past 7 days

📁 Saved Data

The data is saved in:
-data/paris_weather.csv

Example:
date,max_temp,min_temp
2026-03-08,15,7
2026-03-09,16,8
2026-03-10,14,6

🌍 API Used:
This project uses the free API:
Open-Meteo:

https://open-meteo.com/

No API key is required.

🚀 Possible Improvements

-Add multiple cities

-Include additional weather data (wind, humidity)

-Create an interactive dashboard

-Automate daily data collection