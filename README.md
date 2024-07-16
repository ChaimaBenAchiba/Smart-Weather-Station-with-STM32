# Smart Weather Station with STM32

![image](https://github.com/user-attachments/assets/5ee56c48-a414-4ed7-ad48-e38783fa175f)



# Overview
This project implements a smart weather station using STM32F407VGT6 microcontroller, BMP180 sensor for pressure and temperature measurement, DHT11 sensor for humidity measurement, and SSD1306 OLED display for real-time data visualization. Data is also visualized using the ThingSpeak platform.

# Features
STM32F407VGT6 Microcontroller: High-performance ARM Cortex-M4 processor.

BMP180 Sensor: Measures barometric pressure and temperature.

DHT11 Sensor: Measures humidity.

SSD1306 OLED Display: Displays real-time weather data.

ESP8266-01 Module: Provides WiFi connectivity

ThingSpeak Integration: Cloud platform for data visualization.

# Hardware Requirements

STM32F407VGT6 Development Board

BMP180 Sensor

![image](https://github.com/user-attachments/assets/f6e65878-16b8-46b0-9df7-ed018bb41ecd)


DHT11 Sensor

SSD1306 OLED Display

ESP8266 AT Firmware for WiFi communication

ESP8266 Module

Breadboard and connecting wires

# Software Requirements

STM32CubeIDE for firmware development

![image](https://github.com/user-attachments/assets/7fea093b-f2e1-43ea-ad05-54a7d62fc7d8)


ThingSpeak account for data visualization

![image](https://github.com/user-attachments/assets/c83b67a3-38ee-4695-86c6-c3244d408ee6)


# Setup Instructions

-->Hardware Setup:

Connect STM32F407VGT6 to BMP180 and DHT11 sensors.

![image](https://github.com/user-attachments/assets/be5343f0-7f99-4d7b-bfe5-1edfaee47dae)


Wire SSD1306 OLED display for data output.

![image](https://github.com/user-attachments/assets/087ad1ea-5982-4603-942a-b619b641cbbf)


Connect ESP8266 module to STM32 for WiFi connectivity.

![image](https://github.com/user-attachments/assets/4a3f71ec-1957-4371-9033-715e9e98ea48)


-->Software Setup:

Install STM32CubeIDE and set up project for STM32F407VGT6.

Configure sensors and OLED display in the STM32CubeMX tool.

Flash ESP8266 with AT firmware for WiFi communication.

# Operation: 

Power on the weather station.

Real-time weather data (pressure, temperature, humidity) will be displayed on the OLED screen.

![image](https://github.com/user-attachments/assets/7adbb2f1-4549-42b5-9b49-be21d633165f)


Data is also uploaded to ThingSpeak for remote monitoring.

![image](https://github.com/user-attachments/assets/46557e34-472f-4c42-af46-edc9128ec46d)


# Contributing

Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

# License

This project is licensed under the MIT License.

# Acknowledgments

Mariem Hkimi: Led the project from conception to realization, overseeing the integration of STM32 microcontroller, BMP180 and DHT11 sensors, SSD1306 OLED display, and ESP8266 module.Mariem's expertise in embedded systems and project management ensured the successful implementation of real-time data visualization and integration with ThingSpeak platform.

I contributed to the design and implementation of the sensor integration and data visualization algorithms, leveraging my expertise in software development and debugging to ensure the system's reliability and performance.

Aziz Mokrani: Played a key role in the hardware setup and the integration of the ESP8266-01 module for WiFi connectivity. Aziz's skills in electronics and network configuration significantly enhanced the project's communication capabilities.

Thanks to Mariem Hkimi and Aziz Mokrani for their contributions to this project.
