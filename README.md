

# Quadcopter Drone Project

## Overview

This project details the construction and configuration of a quadcopter using the Pixhawk 2.4.8 flight controller. Designed for hobbyists, students, and enthusiasts, it provides a practical introduction to flight control, calibration, and autonomous drone capabilities. The platform leverages open-source tools and modular hardware for a stable, customizable, and scalable flying experience.

---

## System Architecture

- **Pixhawk 2.4.8**: Central flight controller managing stabilization and motor control.
- **RC Transmitter/Receiver**: Enables manual piloting.
- **ESCs (Electronic Speed Controllers)**: Regulate motor power via PWM signals from Pixhawk.
- **GPS Module**: Supports advanced features such as Loiter and Return to Launch (RTL).
- **Telemetry Module (optional)**: Provides real-time flight data to a Ground Control Station (e.g., Mission Planner, QGroundControl).

---

## Hardware Requirements

- Pixhawk 2.4.8 Flight Controller
- F450 Quadcopter Frame
- 4 × A2212 1000KV Brushless Motors
- 4 × 30A ESC (SimonK/BLHeli)
- 2 × CW + 2 × CCW 1045 Propellers
- 3S LiPo Battery (11.1V, 2200–3000mAh)
- Power Module (XT60)
- FlySky FS-i6X Transmitter + iA6B Receiver
- uBlox NEO-M8N GPS with Compass
- 433MHz Telemetry Module
- Active Buzzer
- Micro USB Cable
- Foam Pads / Dampers for Vibration Isolation

---

## Key Features

- **Manual and Assisted Flight Modes**: Supports Stabilize, Altitude Hold, Loiter, and RTL (with GPS).
- **GPS-Based Navigation**: Enables position hold, RTL, and autonomous mission planning.
- **Telemetry and Live Data**: Real-time monitoring of altitude, battery, mode, and RC signals via telemetry.
- **Power Monitoring**: Battery voltage and current draw monitored through the Pixhawk power module.
- **Safety Mechanisms**: Failsafe landing or RTL on RC signal loss or low battery; buzzer alerts for critical events.

---

## Circuit Connections

1. **ESC to Motor & Pixhawk**
    - ESC signal wires to Pixhawk MAIN OUT 1–4.
    - Power wires to PDB or battery.
    - Motors in quad X configuration.
2. **Receiver to Pixhawk**
    - Connect via PPM/S.Bus to RC IN.
    - Channel mapping in Mission Planner.
3. **GPS Module**
    - Connect to GPS/Compass port on Pixhawk.
    - Provides positioning and heading.
4. **Power Module**
    - XT60 from battery to Power Module.
    - Power Module to Pixhawk POWER IN.
5. **Buzzer and USB**
    - Buzzer for alerts.
    - Micro USB for firmware upload and calibration.

---

## Flight Controls

| Channel | Function                |
|---------|------------------------|
| CH3     | Throttle (Ascend/Descend) |
| CH4     | Yaw (Rotate Left/Right)   |
| CH2     | Pitch (Forward/Backward)  |
| CH1     | Roll (Left/Right Tilt)    |
| CH5     | Mode (Stabilize/AltHold/Loiter/RTL) |

---

## Additional Notes

This project is ideal for learning about:

- Sensor calibration
- PID tuning
- GPS-based flight modes
- Autonomous mission planning

The platform is expandable and compatible with companion computers (e.g., Raspberry Pi, Jetson Nano) for advanced applications.

---

## Repository Structure

- `photos_videos/`: Drone images and flight footage
- `components_hardware/`: Parts list, wiring diagrams, datasheets
- `phases_tests/`: Progress logs and test results
- `assembly_manual/`: Step-by-step build instructions


## Project Roadmap

Further documentation, features, and enhancements will be added as the project evolves. Stay tuned for updates on advanced flight modes, integration with companion computers, and expanded autonomous capabilities.



---