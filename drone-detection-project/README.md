# 🚁 Autonomous Drone Detection and Neutralization System  
### 🔐 For Security Applications using Deep Learning & Edge Computing

This project is a real-time drone detection and neutralization system designed to detect unauthorized UAVs using deep learning models deployed on edge hardware like the ESP32-CAM. The system is lightweight, cost-effective, and fully autonomous—making it ideal for security-sensitive zones like airports, borders, and critical infrastructure.

---

## 📦 Components Used

| Component                            | Description                                                    |
|---------------------------------|-------------------------------------------------|
| ESP32                                     | Main microcontroller for system logic           |
| ESP32-CAM                            | Captures live video for drone detection        |
| 16x2 LCD Display                   | Displays real-time status and alerts               |
| Buzzer                                    | Provides audible warning upon detection     |
| Servo Motor                          | Used to simulate drone neutralization           |
| 12V 5A Adapter                     | Powers the entire setup                                  |

---

## 🎯 Features

- 🤖 **AI-powered detection** using YOLOv5 (INT8 quantized) on ESP32-CAM
- 📸 **Real-time camera inference** for drone object detection
- 🔊 **Audible alerts** via buzzer for immediate attention
- 📟 **Visual alerts** on LCD display
- 🔄 **Servo-based tracking** to simulate neutralization of drone
- 🌐 **Edge computing** (no internet/cloud dependency)
- ⚡ **Low power consumption** for portable field deployments

---

## 🧠 Project Architecture

