🛸 What is This Drone Project?
This is a basic quadcopter built using the Pixhawk 2.4.8 flight controller. It’s designed as an entry-level drone project for hobbyists, students, and tinkerers to learn the fundamentals of flight control, calibration, and autonomous capabilities.

It combines open-source tools and modular components to create a stable and customizable flying platform for both manual and assisted flight.

🎮 How Does It Work?
- **Pixhawk 2.4.8** acts as the brain of the drone, managing stabilization and motor control.
- The **RC transmitter/receiver** lets the pilot manually fly the drone.
- The **ESCs** regulate power to the motors based on Pixhawk’s PWM signals.
- The **GPS module** enables positioning features like Loiter and Return to Launch.
- Optional **telemetry module** allows real-time flight data on a Ground Control Station (like Mission Planner or QGroundControl).

📦 Hardware Requirements
- ✅ Pixhawk 2.4.8 Flight Controller
- ✅ F450 Quadcopter Frame
- ✅ 4 × A2212 1000KV Brushless Motors
- ✅ 4 × 30A ESC (SimonK/BLHeli)
- ✅ 2 × CW + 2 × CCW 1045 Propellers
- ✅ 3S LiPo Battery (11.1V, 2200–3000mAh)
- ✅ Power Module (with XT60)
- ✅ FlySky FS-i6X Transmitter + iA6B Receiver
- ✅ uBlox NEO-M8N GPS with Compass
- ✅ 433MHz Telemetry Module
- ✅ Active Buzzer
- ✅ Micro USB Cable
- ✅ Foam Pads / Dampers for Vibration Isolation

📜 Features and Functionalities

🔄 Manual and Assisted Flight Modes  
Fly using standard **Stabilize** mode or switch to **Altitude Hold**, **Loiter**, and **RTL** if GPS is enabled.

🛰️ GPS-Based Navigation 
With GPS, unlock **position hold**, **RTL**, and **autonomous mission planning** via Ground Control Station.

📊 Telemetry and Live Data
Real-time flight data (altitude, battery, mode, RC signals) can be viewed on Mission Planner or QGroundControl using a telemetry module.

🔋 Power Monitoring  
Monitor **battery voltage and current draw** through the Pixhawk power module.

🚨 Safety Features  
- **Failsafe landing** or **Return to Launch** on RC signal loss or low battery.
- **Buzzer alerts** for arming/disarming, GPS lock, and failsafe events.

🛠️ Circuit Connections
1️⃣ **ESC to Motor & Pixhawk**
- ESC signal wires connected to Pixhawk MAIN OUT 1–4.
- Power wires to the PDB or directly from the battery.
- Motors connected in quad X configuration.

2️⃣ **Receiver to Pixhawk**
- Connected via PPM/S.Bus to RC IN.
- Channels mapped in Mission Planner.

3️⃣ **GPS Module**
- Connected to GPS/Compass port on Pixhawk.
- Provides positioning and heading data.

4️⃣ **Power Module**
- XT60 from battery to Power Module.
- Power module connects to Pixhawk POWER IN port.

5️⃣ **Buzzer and USB**
- Buzzer for alerts.
- Micro USB for firmware upload and calibration.

🕹️ Flight Controls (Mode-dependent)
- **Throttle (CH3)**: Ascend/Descend  
- **Yaw (CH4)**: Rotate Left/Right  
- **Pitch (CH2)**: Forward/Backward  
- **Roll (CH1)**: Left/Right Tilt  
- **Mode (CH5)**: Stabilize / AltHold / Loiter / RTL  

---

🧭 Note:
This drone is a great starting point for learning:
- Sensor calibration
- PID tuning
- GPS-based modes
- Autonomous missions

It’s expandable and compatible with companion computers (like Raspberry Pi or Jetson Nano) for future upgrades.

📁 Explore the folders:
- `photos_videos/`: Real drone images and flight footage  
- `components_hardware/`: Parts list, wiring, datasheets  
- `phases_tests/`: Step-by-step progress, testing logs  
- `assembly_manual/`: Full build instructions  

Happy flying! 🚁✨