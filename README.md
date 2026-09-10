# StatClock
An IoT-based ESP32 clock/status system with 4 OLED displays, 16×2 LCD, Wi-Fi connectivity, and remote web-based control, designed for real-time monitoring and future modular expansion.

The project started as a dedicated clock/status system, but is designed to be expandable into a small standalone ESP32 computer with additional input modules, sensors, buttons, and other hardware.

---

## Overview

StatClock uses an ESP32 as the central controller for:

- 4 SSD1306 128×64 OLED displays
- A 16×2 I2C LCD
- Wi-Fi connectivity
- Browser-based control interface
- Clock, date and temperature display
- Rotating bitmap images
- Remotely editable LCD text

The goal is to keep the system expandable so that additional hardware and functionality can be added without redesigning the entire project.
