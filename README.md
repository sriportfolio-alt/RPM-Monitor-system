# 🚀 DC Motor Monitoring Dashboard using LabVIEW

A beginner-friendly Human Machine Interface (HMI) developed in **NI LabVIEW** for monitoring the operating parameters of a DC motor. The dashboard simulates real-time motor behavior by calculating electrical and thermal parameters from the motor RPM.

---

## 📷 Project Preview

<img width="1913" height="982" alt="Screenshot " src="https://github.com/user-attachments/assets/40a8b8fd-3456-4546-b728-6b1e50a845bf" />


---

# ✨ Features

- Real-time RPM monitoring
- RPM Waveform Chart
- RPM Waveform Graph
- Motor ON/OFF Control
- Adjustable RPM Slider
- Current Calculation
- Temperature Calculation
- Voltage Monitoring
- Power Calculation
- Analog Gauges
- Thermometer Indicator
- Adjustable Update Delay
- Continuous Real-Time Monitoring

---

# 🛠 Technologies Used

- NI LabVIEW 2026
- Graphical Programming (G Language)

---

# 📊 Parameters Monitored

| Parameter | Description |
|------------|-------------|
| RPM | Motor Speed |
| Voltage | Motor Supply Voltage |
| Current | Motor Current |
| Temperature | Simulated Motor Temperature |
| Power | Electrical Power Consumption |

---

# ⚙ Working Principle

The dashboard simulates the operating characteristics of a DC motor.

The user controls the motor speed using the RPM slider.

The application continuously calculates:

- Current
- Temperature
- Power

based on the selected RPM.

The calculated values are displayed on:

- Numeric Indicators
- Analog Gauges
- Thermometer
- Waveform Chart
- Waveform Graph

---

# 📐 Equations Used

### Current

Current = 0.5 + (RPM / 1000)

### Temperature

Temperature = 25 + (RPM / 60)

### Voltage

Voltage = 24 − (Current × 0.2)

### Power

Power = Voltage × Current

---

# 🖥 Front Panel

The dashboard includes

- RPM Slider
- Motor ON/OFF Switch
- Voltage Gauge
- Current Gauge
- Power Gauge
- Thermometer
- RPM Chart
- RPM Graph
- Delay Control
- Stop Button

---

# 🔄 Program Flow

Start

↓

User Turns ON Motor

↓

Read RPM

↓

Calculate Current

↓

Calculate Temperature

↓

Calculate Voltage

↓

Calculate Power

↓

Update Indicators

↓

Update Charts

↓

Repeat

---

# 🎯 Learning Outcomes

This project demonstrates

- LabVIEW Programming
- While Loop
- Case Structure
- Numeric Operations
- Waveform Charts
- Waveform Graphs
- Gauges
- Thermometer Indicators
- HMI Design
- Real-Time Monitoring
- Basic Industrial Dashboard Development

---

# 🚀 Future Improvements

- UART Communication with STM32
- Real Motor Monitoring
- Data Logging to CSV
- Alarm System
- Fault Detection
- Motor Efficiency Calculation
- CAN Bus Communication
- PID Speed Control
- DAQ Integration

---

# 👨‍💻 Author

**Sriram**

Embedded Systems | PCB Design | IoT | STM32 | ESP32

GitHub: https://github.com/sriportfolio-alt

LinkedIn: www.linkedin.com/in/sriram-ganesan-a1a171226

---

# ⭐ If you found this project useful, consider giving it a Star!
