# Home-Automation-System-IoT-Based-

# 💡 Simple Light/Fan Control using ESP32 + Relay (Wi-Fi/Bluetooth)

This project allows you to wirelessly control a light or fan using an **ESP32 or Arduino**, a **relay module**, and either **Wi-Fi or Bluetooth**. Perfect for basic home automation demos.

---

## 🔧 Features

- 🕹️ Control appliances remotely via mobile or web interface
- ⚡ Supports both Wi-Fi (ESP32) or Bluetooth (HC-05 + Arduino)
- 🔌 Relay controls AC light or fan
- 🔐 Safe and isolated control system

---

## 🧰 Components Used

- ESP32 or Arduino Uno + HC-05 Bluetooth
- Relay module (5V)
- AC light or fan
- Jumper wires
- Smartphone (for control via app/web)

---

## 🔌 Wiring Diagram
circuit diagram

*(Relay IN to GPIO, VCC to 5V, GND to GND, Load through NO and COM)*

---

## 🚀 How It Works

### 📶 Option 1: Using ESP32 (Wi-Fi)
- Upload code to ESP32
- Connect to Wi-Fi and access web page to toggle light/fan
- ESP32 triggers relay ON/OFF

### 🔵 Option 2: Using Arduino + HC-05 (Bluetooth)
- Upload Bluetooth control code
- Use a mobile app (like Bluetooth Terminal or custom app)
- Send commands (`ON`, `OFF`) to control relay


> A tiny step toward smart homes 🚪💡
