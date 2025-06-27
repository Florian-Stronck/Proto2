# Node-RED Weather Display and RGB LED Project

This project uses Node-RED running on a Raspberry Pi to:

- Retrieve live temperature data from a weather API
- Display the current temperature on an LCD screen
- Change the color of an RGB LED based on the temperature

## Features

- Fetches live weather data from OpenWeatherMap
- Displays temperature on the LCD of a digi lab
- RGB LED changes color based on temperature:
  - Blue for temperatures below 10°C
  - Green for temperatures between 10°C and 20°C
  - Red for temperatures above 20°C
- Refreshes When button is pressed

## Hardware Requirements

- Raspberry Pi (with GPIO and I²C support)
- DigiLab
