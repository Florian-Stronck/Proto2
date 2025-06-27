# Node-RED Weather Display and RGB LED Project

This project uses Node-RED running on a Raspberry Pi to:

- Retrieve live temperature data from a weather API
- Display the current temperature on an I²C LCD screen
- Change the color of an RGB LED based on the temperature

## Features

- Fetches live weather data from OpenWeatherMap
- Displays temperature on a 16x2 or 20x4 I²C LCD
- RGB LED changes color based on temperature:
  - Blue for temperatures below 10°C
  - Green for temperatures between 10°C and 20°C
  - Red for temperatures above 20°C
- Refreshes automatically every 10 minutes (configurable)

## Hardware Requirements

- Raspberry Pi (with GPIO and I²C support)
- I²C LCD Display (16x2 or 20x4)
- RGB LED (Common Cathode recommended)
- 3 x 220Ω resistors
- Jumper wires and a breadboard

## Node-RED Dependencies

Install the required Node-RED package:

```bash
npm install node-red-contrib-i2c-lcd
