# Project---1st-IoT-prototype

# Solar-Powered Smart Drip Watering System with IoT Weather Monitoring At BIT International College Annex

It's a prototype that monitors the weather, sends the data to a database, and controls the pump based on the data.

## Overview

The purpose of the prototype is to create a device capable of watering plants without human labor, transmitting sensor data over the Internet, and automatically adjusting its watering based on the plant's needs to reduce water waste.

The system addresses several problems: reducing the human labor required to water plants, determining how much water a plant needs, and minimizing unnecessary water consumption. If deployed on a larger scale, the system could also allow scientists and researchers to collect environmental and agricultural data from specific regions through the network of devices.

The plants are watered automatically based on data collected from the system's sensors. Users can also monitor the sensor readings and the system's status through a mobile application developed using MIT App Inventor.

## Features

- Feature 1
- Feature 2
- Feature 3
- Feature 4

## Hardware

| Component | Description |
|---|---|
| ESP32 | Main microcontroller |
| DHT22 | Temperature and humidity sensor |
| Soil Moisture Sensor | Measures soil moisture |
| Water Pump | Irrigation |
| Solar Panel | Power source |
| Battery | Energy storage |

## Software

- Arduino IDE
- C/C++
- Firebase
- MIT App Inventor

## System Architecture

Describe how the major components communicate.

```text
Solar Panel
     ↓
Charge Controller
     ↓
Battery
     ↓
Voltage Regulation
     ↓
ESP32
 ┌───┼───────────┐
 ↓   ↓           ↓
DHT22 Soil      Pump
     Sensors
       ↓
    Firebase
       ↓
  Mobile App
