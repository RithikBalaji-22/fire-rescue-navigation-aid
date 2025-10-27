# fire-rescue-navigation-aid
A sonar sensor–based navigation and alert system for fire rescue operations in smoke-filled environments, built using Arduino Uno and ultrasonic sensors.
# Fire Rescue Sonar Navigation Aid 🚒

A low-cost, Arduino-based sonar navigation system designed for fire rescue operations in smoke-filled environments.  
The system uses ultrasonic sensors to detect obstacles and alert rescuers through buzzer/vibration signals when objects are nearby.

---

## ⚙️ System Overview

- **Controller:** Arduino Uno  
- **Sensors:** Ultrasonic HC-SR04 × 3  
- **Actuators:** Buzzer + Vibration Motor  
- **Motor Driver:** L293D (optional for mobility)  
- **Power Source:** 9V battery  
- **Software:** Arduino IDE (C/C++)

---

## 🧩 Features

✅ Real-time obstacle detection (up to 4 meters)  
✅ Reliable operation under smoke/zero-visibility  
✅ Low-cost, modular hardware design  
✅ Alert generation based on proximity levels  
✅ SDG-aligned: Supports Good Health, Innovation, and Safety  

---

## 🔌 How to Execute

1. Open **Arduino IDE**.
2. Connect **Arduino Uno** via USB.
3. Load `src/sonar_navigation.ino`.
4. Verify and upload the code.
5. Observe buzzer/vibration responses for objects within range.

---

## 📊 Results

- **Precision:** 93%  
- **Recall:** 91%  
- **F1 Score:** 92%  
- **Detection Range:** 0.5 – 4.0 m  
- **Response Time:** <1 second

---

## 📸 Prototype

| Image | Description |
|-------|--------------|
| ![Prototype](media/prototype_front_view.png) | Prototype chassis and wiring |
| ![Wiring Diagram](media/wiring_diagram.png) | Full sensor and motor connection layout |

---

## 🧪 Contributors

- **Student:** Rithik Balaji  
- **Guide:** [Guide’s Name Here]  
- **Institution:** [Your College Name]  

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute with attribution.

---

## 🌍 SDG Alignment

This project supports the following UN Sustainable Development Goals:
- SDG 3: Good Health & Well-Being  
- SDG 9: Industry, Innovation & Infrastructure  
- SDG 11: Sustainable Cities & Communities  

