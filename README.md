# 6G-Oriented Smart Home: A Synergy of Energy Harvesting and AI-Driven Automation

![Hardware Setup](hardware-setup.jpg)

## Overview

This project proposes a 6G-oriented smart home that combines green 
energy harvesting with AI-driven automation. The system first 
harvests green energy — solar and piezoelectric — for power, and 
stores it in batteries and capacitors. AI is then used to continuously 
take input from sensors and automate the home accordingly.

The project aims to strike a balance between green energy and 
automation, making the smart home not just "smart" but also 
environmentally friendly and energy-efficient — both of which matter 
for the environment. Since the future lies in 6G, the system is 
designed to be adaptable to 6G networks. Even though the project does 
not currently have 6G connectivity, it is built to adapt to it through 
continuous energy harvesting, fast response times, and an 
environmentally friendly design.

## Architecture

![Block Diagram](block-diagram.png)

The system is structured as follows:
- **Energy Input:** Solar panel and piezoelectric sensors feed 
  harvested energy into a supercapacitor and battery
- **Sensors:** Temperature sensor, PIR sensor, object detection, and 
  LDR (Light Dependent Resistor) provide real-time environmental data
- **Processing Unit:** Arduino Nano reads sensor data and controls 
  outputs accordingly
- **Outputs:** Fan, light, and ventilation fan are automated based on 
  sensor readings
- **Monitoring Layer:** A webcam feeds into a PC (processed using 
  PyCharm) for person detection, enabling digital visualization and 
  energy monitoring

## Digital Twin

![Digital Twin Dashboard](digital-twin-dashboard.png)

The digital twin dashboard mirrors the physical system in real time — 
showing live temperature readings and the current status of connected 
devices (fan, light). This allows the physical and virtual systems to 
stay synchronized, so the setup can be monitored and controlled 
remotely instead of only in person.

## Features

- **Solar Energy Harvesting** — captures ambient solar energy to 
  supplement power supply
- **Piezoelectric Energy Harvesting** — converts mechanical 
  vibration/pressure into usable electrical energy
- **AI-Driven Automation** — automates fan, light, and ventilation 
  control based on real-time sensor data
- **Digital Twin Monitoring** — real-time virtual replica of the 
  physical system for remote visualization
- **Person & Object Detection** — webcam-based detection feeding into 
  the automation logic for energy-aware decisions

## Technology Used

**Hardware:**
- Arduino Nano (ATmega328 microcontroller)
- Solar panel
- Piezoelectric sensors
- Temperature sensor, PIR sensor, LDR sensor
- 18650 Li-ion batteries
- Supercapacitors
- LCD display (16x2)
- L298N motor driver
- DC cooling fans

**Software/Tools:**
- Embedded C / Arduino IDE
- Python (PyCharm) for object/person detection

**Concepts:**
- IoT (Internet of Things)
- Green energy harvesting
- AI-based automation
- Digital twin technology

## Outcomes

- Achieved real-time synchronization between the physical prototype 
  and its digital twin
- Demonstrated energy-efficient automation using harvested (solar + 
  piezoelectric) power instead of relying purely on grid electricity
- Enabled remote monitoring and person-aware automation through 
  webcam-based detection

**Advantages:**
- Free from full dependency on grid power
- Environmentally friendly and energy-efficient
- Adaptable to 6G connectivity concepts for the future
- Real-time energy monitoring helps predict energy levels and grid 
  utilization

## Skills Gained

- Familiarity with microcontrollers, specifically the ATmega328 
  (Arduino Nano)
- Sensor integration — working with temperature, PIR, object 
  detection, and LDR sensors
- Embedded systems and Embedded C / Arduino IDE programming
- Testing, troubleshooting, and debugging, circuit wiring

## Future Scope

- Integrate additional renewable energy sources (e.g. wind or thermal 
  harvesting) to further reduce grid dependency
- Extend the digital twin to support multi-room or full-house monitoring
- Incorporate actual 6G connectivity once infrastructure becomes 
  widely available, for lower-latency remote control
- Add mobile app integration for user-friendly remote access
- Improve AI automation with machine learning models trained on 
  historical usage data

## Status

Academic project built as part of my B.E. in Electronics and 
Communication Engineering.

