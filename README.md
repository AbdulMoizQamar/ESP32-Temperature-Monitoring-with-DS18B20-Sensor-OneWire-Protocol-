# ESP32-Temperature-Monitoring-with-DS18B20-Sensor-OneWire-Protocol-
This Arduino sketch interfaces the DS18B20 digital temperature sensor with an ESP32 using the OneWire communication protocol. It reads and prints temperature values in both Celsius and Fahrenheit to the Serial Monitor.

📝 Description:
This Arduino sketch interfaces the DS18B20 digital temperature sensor with an ESP32 using the OneWire communication protocol. It reads and prints temperature values in both Celsius and Fahrenheit to the Serial Monitor.

✅ Features:
Uses the DallasTemperature and OneWire libraries
Reads temperature in ºC and ºF
Easy sensor setup on GPIO 4
5-second interval temperature readings
Simple and compact code for learning OneWire sensors

📦 Requirements:
ESP32 development board
DS18B20 temperature sensor

Arduino IDE
Libraries:
OneWire
DallasTemperature

🔌 Wiring:
DS18B20 Pin	ESP32 Pin
VCC	3.3V or 5V
GND	GND
DATA	GPIO 4 (with a 4.7kΩ pull-up resistor to VCC)

