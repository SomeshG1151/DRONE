# 🛠️ Assembly Instructions & Guidance

## Step-by-Step Assembly Guide

### 1. **Frame Assembly**
- Attach the four arms to the central hub using the provided screws.
- Ensure the arms are oriented correctly (typically, two red arms for the front, two white for the rear).

### 2. **Motor Mounting**
- Secure each brushless motor to the end of each arm using the supplied screws.
- Double-check that the motors are firmly attached and wires are accessible.

### 3. **ESC Installation**
- Mount one ESC on each arm, close to the motor, using zip ties or double-sided tape.
- Connect each ESC’s three output wires to the corresponding motor wires (match colors if possible).

### 4. **Power Distribution Board (PDB)**
- Fix the PDB to the frame’s center.
- Solder the ESC power leads (red and black) to the PDB.
- Solder the battery connector (XT60 or similar) to the PDB.

### 5. **Flight Controller Mounting**
- Attach vibration-damping pads to the Pixhawk 2.4.8 flight controller.
- Mount the flight controller on the frame’s center, ensuring the arrow points forward.

### 6. **Wiring Connections**
- Connect ESC signal wires to the Pixhawk’s main output ports (typically 1–4 for quadcopters).
- Connect the PDB’s power output to the Pixhawk’s power module port.
- Attach the GPS/compass module to the dedicated Pixhawk port and mount it away from power wires to reduce interference.

### 7. **Propeller Installation**
- Install propellers only after all wiring and calibration are complete.
- Attach CW and CCW propellers to the correct motors (refer to motor layout diagram).

### 8. **Receiver & Telemetry**
- Connect the RC receiver to the Pixhawk’s RC IN port.
- Mount the receiver securely and route antennas away from power wires.
- (Optional) Connect telemetry module to the TELEM port for ground station communication.

### 9. **Battery & Buzzer**
- Secure the LiPo battery to the frame using Velcro straps.
- Connect the battery to the PDB.
- Attach the buzzer to the Pixhawk’s buzzer port and mount it where it’s audible.

### 10. **Cable Management**
- Use zip ties and Velcro to tidy up all wires.
- Ensure no wires are loose or can contact spinning propellers.

---

## Initial Setup & Calibration

1. **Install Mission Planner or QGroundControl** on your computer.
2. **Connect Pixhawk via USB** and follow the software’s setup wizard.
3. **Calibrate the radio transmitter, accelerometer, compass, and ESCs** as prompted.
4. **Check motor directions** using the software and swap any two motor wires if a motor spins the wrong way.
5. **Set failsafe options** for loss of signal and low battery.

---

## First Flight Guidance

- Perform all pre-flight checks.
- Arm the drone in a safe, open area.
- Gradually increase throttle and observe stability.
- Land immediately if you notice abnormal behavior.
- Fine-tune PID settings in Mission Planner for optimal flight performance.

---

**Tip:** Take photos during each assembly step for future reference and troubleshooting.



