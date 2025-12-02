<div align="center">

# 🌞 Light Following Solar Panel

### Arduino-Based Smart Solar Panel Alignment System

**An Arduino-based intelligent solar panel positioning system that automatically follows the direction of maximum light using LDR sensors and servo motors to improve energy efficiency.**

[🐛 Report Bug](https://github.com/TanayV24/Light_Following_SolarPanel/issues) | [💡 Request Feature](https://github.com/TanayV24/Light_Following_SolarPanel/issues)

</div>

---

## ✨ Features

- 🌞 **Automatic Sun Tracking** — Panel rotates toward the strongest light source  
- 🎯 **Improved Energy Efficiency** — Maximizes solar energy absorption  
- 🔦 **LDR-Based Light Detection** — Uses multiple Light Dependent Resistors  
- ⚙️ **Servo Motor Control** — Smooth panel movement using PWM  
- 🔁 **Real-Time Adjustment** — Continuously aligns with changing light direction  
- 🔌 **Low Power Consumption** — Optimized for energy-efficient operation  
- 🛠 **Beginner & Project Friendly** — Ideal for Arduino, IoT & renewable energy projects  

---

## 🛠 Tech & Hardware Stack

| Category | Component |
|----------|-----------|
| Microcontroller | Arduino UNO |
| Sensors | LDR (Light Dependent Resistor) |
| Actuator | Servo Motor |
| Power | Battery / External DC Supply |
| Programming | Arduino C / C++ |
| IDE | Arduino IDE |

---

## ⚙️ How It Works

1. LDR sensors detect light intensity from multiple directions  
2. Arduino continuously compares sensor readings  
3. The servo motor rotates the solar panel toward the strongest light  
4. This keeps the panel aligned with the sun (or light source) for maximum power generation  

---

## 🚀 How to Use the Code

1. Clone the repository:
```bash
git clone https://github.com/TanayV24/Light_Following_SolarPanel.git
````

2. Open the `.ino` file in **Arduino IDE**

3. Connect:

* LDRs to analog pins
* Servo motor to PWM pin
* Power supply to Arduino

4. Select:

* **Board:** Arduino UNO
* **Port:** Correct COM Port

5. Click **Upload**

6. Place the panel under a light source and watch it follow the light automatically ✅

---

## 🧪 Applications

* 🌱 Renewable Energy Systems
* 🧑‍🎓 Academic Mini & Major Projects
* 🤖 Robotics & Automation
* ⚡ Smart Energy Management
* 🛠 IoT & Embedded Systems Learning

---

## 🐛 Troubleshooting

<details>
<summary>Servo not moving</summary>

* Check if defined pin is a valid PWM pin
* Ensure adequate power supply
* Confirm servo wiring (VCC, GND, Signal)

</details>

<details>
<summary>Incorrect light tracking</summary>

* Calibrate LDR placement
* Adjust threshold values in code
* Avoid uneven shadowing on sensors

</details>

<details>
<summary>Arduino not detected</summary>

* Install correct USB drivers
* Select correct COM port
* Restart Arduino IDE

</details>


