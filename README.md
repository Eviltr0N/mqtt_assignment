# Job Test: Firmware Developer

## Task Overview:
As part of the hiring process for the Firmware Developer position at Nistantritech
Private Limited, we have designed a practical task to evaluate your skills in firmware
development, communication protocols, and IoT integration. This test involves reading
sensor data using I2C or One-Wire communication and posting the data to ThingsBoard
using MQTT.

## Solution

### Hardware Setup
* ESP-32
* DS18B20 temperature sensor
* 1k Resistor
* Jumper Wires/Breadboard

### Circuit Digram
![Circuit Digram](https://github.com/Eviltr0N/mqtt_assignment/raw/main/circuit.png)

### Libraries Used
* Wifi.h
* OneWire.h
* DallasTemperature.h
* PubSubClient.h

### Arduino Code & Explanation

[Click Here](https://github.com/Eviltr0N/mqtt_assignment/blob/main/temp_sensor_assign.ino)
