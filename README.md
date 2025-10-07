# Project
A Smart Monitoring Framework for Three-Phase Induction Motor  Developed a microcontroller-based system for real-time monitoring and control of a three-phase induction motor using  IoT. The system enables fault detection, data acquisition, and remote control via Wi-Fi, supporting efficient and  economic communication for industrial applications.
# Smart Monitoring Framework for Three-Phase Induction Motor

## 📘 Overview

This project presents a **microcontroller-based smart monitoring system** designed for **real-time monitoring, fault detection, and remote control** of a **three-phase induction motor** using **IoT technologies**. The system is intended to improve the **efficiency, safety, and reliability** of industrial motor operations by enabling **remote access**, **data logging**, and **predictive maintenance capabilities**.

## ⚙️ Key Features

- 📡 **IoT-Enabled Monitoring**: Real-time data acquisition and wireless transmission via Wi-Fi.
- 🚨 **Fault Detection**: Identifies and flags operational anomalies such as overvoltage, undervoltage, phase loss, and overheating.
- 📊 **Data Logging & Visualization**: Sensor data such as voltage, current, temperature, and motor status is collected and can be visualized or stored for later analysis.
- 🌐 **Remote Control**: Motor start/stop operations can be triggered remotely through a web or mobile interface.
- 💡 **Energy Efficient & Cost-Effective**: Optimized communication protocols for low power and minimal network load.

## 🧰 Hardware Used

- 🧠 **Microcontroller**: ESP32 / Arduino-compatible MCU with Wi-Fi support
- 🔌 **Sensors**:
  - Voltage sensor (for each phase)
  - Current sensor (ACS712 / Hall-effect)
  - Temperature sensor (e.g., LM35 / DS18B20)
- 🔧 **Relay Module**: For motor ON/OFF control
- 🖥️ **Motor**: Three-phase Induction Motor
- 🌐 **Wi-Fi Module**: (Integrated on ESP32 or via ESP8266 for Arduino)

## 🧠 Software Components

- 📦 **Firmware**: Written in C/C++ using Arduino IDE or PlatformIO
- ☁️ **IoT Platform**: (e.g., Blynk, ThingsBoard, or custom server) for cloud-based monitoring and control
- 🧩 **Communication Protocols**: MQTT / HTTP
- 📱 **Mobile App or Web Dashboard**: For user interaction and visualization

## 🛠️ Installation & Setup

1. **Clone the Repository**:
    
   git clone https://github.com/your-username/smart-induction-motor-monitoring.git
   Hardware Assembly:

Connect sensors and relays to the microcontroller according to the provided schematic (see /hardware/ folder).

Ensure proper safety and insulation when working with high voltage systems.

Firmware Upload:

Open the .ino file in Arduino IDE.

Select the correct board (ESP32/ESP8266).

Upload the code after configuring the Wi-Fi credentials and MQTT/HTTP settings.

IoT Platform Configuration:

Set up your preferred IoT dashboard.

Create widgets for displaying temperature, voltage, current, and motor status.

Enable remote control functionality.

📁 Repository Structure
/smart-induction-motor-monitoring/
│
├── /firmware/               # Microcontroller code
├── /hardware/               # Circuit diagram, wiring schematics
├── /docs/                   # Documentation and project report
├── README.md                # Project overview (this file)
└── LICENSE

🚨 Safety Warning

This project involves working with high voltage AC systems. Ensure that you follow all electrical safety procedures and regulations. Only trained personnel should operate or assemble the hardware.

📈 Potential Improvements

AI/ML-based predictive fault detection

Integration with industrial PLC systems

Mobile notification alerts

Energy consumption analysis and forecasting

🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests if you have improvements, bug fixes, or suggestions.

📄 License

This project is licensed under the MIT License
.

✍️ Authors

[Your Name]

[Collaborators if any]

📬 Contact

For questions, collaborations, or support, feel free to open an issue or reach out at [your-email@example.com
].


---

### ✅ Notes:
- Replace placeholders like **`your-username`**, **`your-email@example.com`**, and specific sensor names or platforms (like Blynk, ThingsBoard) according to your implementation.
- You can add screenshots, hardware schematics, or GIFs of the working dashboard in the README using:
  ```markdown
  ![Dashboard Screenshot](docs/dashboard.png)
