# 🏓 Dura-Paddle  
*A device to evaluate pickleball paddle degradation by measuring the Coefficient of Restitution (COR)*  

---

## 📖 Overview  
Pickleball is one of the fastest growing sports in the U.S., but paddle degradation is a major issue.  
When a paddle loses stiffness and power, players’ gameplay is impacted.  

**Dura-Paddle** is a portable device that:  
- ⚡ Measures the *Coefficient of Restitution (COR)* based on USA Pickleball standards.  
- 📊 Quantifies paddle condition with an Arduino, ultrasonic sensor, LEDs, and 3D-printed housing.  
- 🛡️ Helps players extend paddle life, reduce waste, and maintain consistent gameplay.  

---

## 🛠️ Build Process  
1. 🔍 **Sensor Selection:**  
   - Used an **HC-SR04 Ultrasonic Sensor** for impact detection.  
   - Powered by a 9V battery.  

2. 🧰 **Prototyping & Circuitry:**  
   - Arduino Uno controls measurement + LED indicators.  
   - Red LED = low COR (bad), Green LED = good COR (usable).  

3. 🧾 **3D Printing & Assembly:**  
   - Custom PLA shell designed and printed.  
   - Sensor & LED holes precision-fitted, glued with hot glue.  

---

## 📈 Testing & Results  
- Tests compared different paddles (wood, graphite, fiberglass, carbon fiber).  
- **Key Finding:**  
  - GARyE Carbon Fiber paddles consistently achieved the **highest COR values**, indicating longer lifespan.  
  - Older fiberglass paddles showed lower, less consistent COR.  

---

## 🎯 Objectives & Constraints  
**Objectives**  
- ✅ User-friendly paddle degradation tester.  
- ✅ Reliable & accurate (>90%).  
- ✅ Portable & accessible for all skill levels.  

**Constraints**  
- 💲 Cost ≤ $20-$30  
- 🤚 Handheld size  
- 🔋 Battery powered  

---

## 🚀 Future Improvements  
- Replace ultrasonic with **time-of-flight (ToF)** or **piezoelectric sensor** for higher precision.  
- Add **OLED screen** for real-time COR display.  
- Implement **calibration mode** for user-defined paddle baselines.  

---

## 📦 Tech Stack  
![C++](https://img.shields.io/badge/Arduino-C++-blue?logo=arduino)  
![3D Printing](https://img.shields.io/badge/3D--Printing-PLA-orange?logo=3dprint)  
![Electronics](https://img.shields.io/badge/Electronics-Arduino%20Uno-green?logo=arduino)  
![Sensors](https://img.shields.io/badge/Sensors-Ultrasonic-yellow)  

- **Arduino IDE** – Core programming  
- **HC-SR04 Ultrasonic Sensor** – COR measurement  
- **LEDs + 9V Battery** – Visual indicator + power supply  
- **3D-Printed PLA Housing** – Enclosure  

---

## 📚 References  
- Farnsworth, 2024 – *Degradation of Pickleball Paddles*  
- USA Pickleball Association Standards  
- ASTM Testing Guidelines  

---

## 👩‍💻 Team  
- Rhett Armentrout  
- Mohammad Bhuiyan  
- Ananya Dandemraju  
- Eduardo Garcia  
- Thomas Wiktorowicz  

University of Virginia – School of Engineering & Applied Science  
