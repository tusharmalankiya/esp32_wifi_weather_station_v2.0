
# 🌤️ ESP32 Wi-Fi Weather Station

This project uses an ESP32 microcontroller to fetch and display real-time weather information from the OpenWeatherMap API on an OLED display. Additionally, the ESP32 functions as a web server, hosting a responsive web-based weather dashboard accessible over the local network.

---

## 📌 Features

- Connects to Wi-Fi
- Fetches current weather data (temperature, humidity, and condition)
- Displays data on a 128x64 OLED screen
- Updates automatically every 30 seconds
- Simple web dashboard


## 🧰 Tools Used

- [ESP32](https://www.espressif.com/en/products/socs/esp32)
- [Wokwi Simulator](https://wokwi.com/)
- VS Code + PlatformIO
- SSD1306 OLED Display (I2C)
- OpenWeatherMap API

## Data Source
Weather data is obtained from OpenWeatherMap.