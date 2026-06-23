# Smart Irrigation System using STM32F103RB

## Overview

This project presents a Smart Irrigation System developed using the STM32F103RB (ARM Cortex-M3) microcontroller. The system continuously monitors soil moisture, temperature, humidity, rainfall, and ambient light conditions to automate irrigation decisions.

The objective is to reduce water wastage and improve irrigation efficiency by activating the water pump only when environmental conditions require it.

---

## Features

* Real-time soil moisture monitoring
* Temperature and humidity measurement using DHT11
* Rain detection for irrigation override
* Light intensity monitoring using LDR
* Automatic pump control using relay module
* Live system status display on 16×2 LCD
* Priority-based irrigation decision logic
* Low-cost and scalable smart farming solution

---

## Hardware Components

* STM32F103RB Microcontroller
* FC-28 Soil Moisture Sensor
* DHT11 Temperature & Humidity Sensor
* Rain Sensor Module
* LDR Sensor Module
* 16×2 LCD Display (I2C Interface)
* Relay Module
* Water Pump
* Power Supply Unit

---

## Software and Development Tools

* STM32CubeIDE
* STM32 HAL Libraries
* Embedded C
* ARM Cortex-M3 Architecture

---

## System Operation

The system continuously acquires data from multiple sensors and evaluates environmental conditions using predefined control logic.

### Irrigation Logic

1. If rain is detected, the pump remains OFF.
2. If insufficient light conditions are present, irrigation is avoided.
3. If soil moisture falls below the defined threshold, the pump is activated.
4. Once adequate moisture is achieved, the pump is turned OFF.

This approach minimizes unnecessary water consumption while maintaining suitable soil conditions.

---

## Key Functionalities

* Multi-sensor environmental monitoring
* Automated irrigation control
* Real-time parameter display
* Water conservation through intelligent decision-making
* Reliable operation using embedded firmware

---

## Results

The implemented system successfully automated irrigation based on real-time environmental conditions. Testing demonstrated stable operation, responsive pump control, and effective prevention of unnecessary irrigation during rainfall and unsuitable operating conditions.

Key observations include:

* Accurate soil moisture monitoring
* Reliable rain detection override
* Stable LCD operation
* Automated pump actuation
* Improved water management efficiency

---

## Future Scope

* IoT-based remote monitoring
* Cloud data logging and analytics
* Mobile application integration
* Solar-powered operation
* AI-driven irrigation scheduling
* Wireless sensor network expansion

---

## Authors

**Swapnil Saraswat**  
B.Tech Electronics & Communication Engineering  
Gati Shakti Vishwavidyalaya

**Amisha Singh**  
B.Tech Electronics & Communication Engineering  
Gati Shakti Vishwavidyalaya

