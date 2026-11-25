
# IoT Motion Detection Dashboard

A web-based, real-time monitoring dashboard for an
IoT motion detection and alarm system.

Developed as part of the Group 4 IoT practical project
at the Open University of Kenya (OUK).

## Overview

The dashboard receives motion detection events from
an ESP32-based alarm system via MQTT and displays
the current motion status and event history.

## Features

- Real-time motion detection monitoring
- MQTT connectivity and subscription status
- Motion event history
- Persistent event history using browser local storage
- Integration with Wokwi ESP32 simulation
- Browser-based interface with no backend required

## System Architecture

ESP32 + PIR Sensor → MQTT Broker → Web Dashboard

The ESP32 detects motion using a PIR sensor,
activates an LED and buzzer, and publishes motion
events to the MQTT broker.

## Technologies

- ESP32
- PIR Motion Sensor
- MQTT
- HTML, CSS and JavaScript
- Wokwi Simulator

## Wokwi Simulation

[Open Wokwi Project](https://wokwi.com/projects/481560410195812353)

## Getting Started

1. Start the Wokwi simulation.
2. Open `index.html` in your browser.
3. Wait for "Connected and subscribed".
4. Click the PIR sensor and select "Simulate motion".
5. Observe the LED, buzzer and dashboard status.
6. Check the motion event history.
7. Refresh the dashboard to verify history persistence.

## Repository Structure

    IoT-motion-dashboard/
    ├── index.html
    └── README.md

## Security Notice

This project uses a public MQTT test broker for
educational and demonstration purposes only.
Do not transmit sensitive or personal data.

## Project

- Institution: Open University of Kenya (OUK)
- Course: CSC 823 - Internet of Things
- Team: Group 4
- Purpose: Academic practical demonstration


## Live Dashboard

[Open Dashboard](https://kiplongu.github.io/IoT-motion-dashboard/)