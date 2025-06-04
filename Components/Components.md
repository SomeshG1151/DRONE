# 🛸 Quadcopter Drone Project!

[alt text](./images/1000024351.jpg)

## Overview

This is a custom buildt quadcopter drone for the agricultural autonomus navigation and surrvillience purposes. It is controlled using an RC transmitter and is equipped with a flight controller, GPS, and electronic speed controllers for stable and reliable flight.
This is a basic quadcopter built using the Pixhawk 2.4.8 flight controller. It’s designed as an entry-level drone project for hobbyists, students, and tinkerers to learn the fundamentals of flight control, calibration, and autonomous capabilities.
It combines open-source tools and modular components to create a stable and customizable flying platform for both manual and assisted flight.

---

## 🧩 Components

### 1. **Frame**

* **Type**: X-Frame (Plastic composite, modular)
* **Description**: A standard X-type quadcopter frame with four arms (two red, two white) and a central hub to mount the flight controller, battery, and other electronics.
* **Purpose**: Provides structure and support for all mounted components.

### 2. **Propellers**

* **Type**: 1045 (10-inch, black plastic)
* **Quantity**: 4
* **Purpose**: Generates lift by rotating at high speed. Propeller direction must be matched to motor direction.

### 3. **Brushless Motors**

* **Model**: 2212 22000KV 
* **Quantity**: 4
* **Description**: Outrunner brushless DC motors, mounted at the ends of the arms.
* **Purpose**: Converts electrical power into mechanical rotation for the propellers.

### 4. **Electronic Speed Controllers (ESCs)**

* **Type**: 30A 
* **Quantity**: 4 (mounted beneath or on the arms)
* **Purpose**: Regulates the power supplied to each motor based on flight controller input.

### 5. **Flight Controller**

* **Model**: Pixhawk 2.4.8
* **Description**: Central control unit that manages flight dynamics using sensor data (accelerometer, gyroscope, magnetometer, barometer).
* **Features**:

  * Supports autonomous flight modes
  * GPS integration

### 6. **GPS Module**

* **Model**: Ublox Neo-M8N
* **Purpose**: Provides positional data for autonomous flight and failsafe return-to-home (RTH) features.

### 7. **Power Distribution Board (PDB)**

* **Description**: Distributes power from the LiPo battery to the ESCs and flight controller.

### 8. **Battery**

* **Type**: LiPo 3S or 4S (not visible, but required)
* **Purpose**: Supplies power to the entire system.

### 9. **RC Transmitter and Receiver**

* **Transmitter**: FlySky FS-i6
* **Receiver**: FS-iA6B 
* **Channels**: 6-channel
* **Purpose**: Manual control of the drone via 2.4GHz frequency.

### 10. **Telemetry Module (optional)**

* **Purpose**: Sends flight data to ground control software like Mission Planner (not clearly visible but often paired with Pixhawk).

### 11. **Buzzer**

* **Purpose**: Audible alerts for low battery, lost model, arming status.

### 12. **Mounting & Wiring**

* Zip ties and Velcro are used for clean cable management and vibration isolation.

---

##  Assembly Notes

* Ensure motors are wired correctly for clockwise (CW) and counterclockwise (CCW) rotations.
* Calibrate ESCs using flight controller tools.
* Secure all connectors and isolate exposed wires to avoid shorts.

---

##  Ground Control Software

* **Mission Planner** (Windows)
* **QGroundControl** (Cross-platform)
* Use this software to:

  * Calibrate sensors
  * Plan missions
  * Monitor live telemetry

---

##  Pre-Flight Checklist

*  Check motor rotation and prop direction
*  Calibrate compass and accelerometer
*  Arm the drone safely
*  Ensure GPS lock (if needed for mode)
*  Battery fully charged

---

##  Safety Tips

* Fly in open areas, away from people.
* Keep a safe distance during motor tests.
* Always disarm the drone before touching it.

---

Let me know if you want me to generate a PDF or DOCX version, or include wiring diagrams or ESC calibration steps.
