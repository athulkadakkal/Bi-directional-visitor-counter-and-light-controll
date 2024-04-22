# Bi-Directional Visitor Counter

## Overview
This project uses Arduino and a pair of IR sensors to monitor the entry and exit of individuals in a room, displaying the count on an OLED display. It incorporates a relay to manage lighting, turning it off when no one is present and on when the count is above zero, promoting energy efficiency.

## Features
- **Visitor Tracking:** Monitors the number of individuals entering and exiting.
- **Display Output:** Current count is shown on an OLED display.
- **Light Management:** Controls room lighting based on occupancy, using a relay.

## Components
- Arduino Uno (or compatible board)
- 2 x IR sensors
- OLED display
- Relay module
- Connecting wires

## Setup Instructions
1. **Assemble the Hardware:** Connect IR sensors, OLED display, and relay module to the Arduino.
2. **Software Installation:** Install necessary libraries in Arduino IDE, including Adafruit_SSD1306 for the OLED display.
3. **Upload and Execute:** Upload the Arduino sketch that processes the IR sensor input to display the count and control the relay based on occupancy.

## Operation
The system increases the count when someone enters and decreases it when someone exits. The room's lights are controlled automatically: off when the room is empty and on when occupied. This setup is ideal for managing resources in spaces like conference rooms or classrooms.
