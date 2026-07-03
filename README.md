# Fiber Optic VOC Sensor

## Overview

This project presents a low-cost **Fiber Optic Volatile Organic Compound (VOC) Sensor** developed using **Arduino UNO**, an **LDR (Light Dependent Resistor)**, and a **16×2 LCD**. The system detects changes in light intensity transmitted through an optical fiber when exposed to volatile organic compounds (VOCs).

An LDR placed at the receiving end measures the transmitted light. As VOC exposure changes the optical properties of the sensing region, the amount of received light changes, resulting in a variation in the LDR resistance. The Arduino calculates this resistance using the voltage divider principle and displays the measured value on the LCD.

---

## Features

- Fiber optic-based VOC sensing
- Light intensity measurement using an LDR
- Resistance calculation using Arduino ADC
- Real-time LCD display
- Low-cost sensing solution
- Portable prototype for environmental monitoring

---

## Hardware Used

- Arduino UNO
- LDR (Light Dependent Resistor)
- Optical Fiber
- LED Light Source
- 16×2 LCD Display
- 470Ω Reference Resistor
- Breadboard
- Jumper Wires
- Power Supply

---

## Software Used

- Arduino IDE
- Embedded C

---

## Working Principle

1. An LED transmits light through the optical fiber.
2. The sensing region of the optical fiber is exposed to VOC gases.
3. VOC exposure changes the transmitted light intensity.
4. The LDR placed at the receiving end detects the change in light.
5. The Arduino reads the LDR voltage using its Analog-to-Digital Converter (ADC).
6. The resistance of the LDR is calculated using the voltage divider equation.
7. The calculated resistance is displayed on the 16×2 LCD.

---

## Formula Used

The resistance is calculated using the voltage divider equation:

R₁ = R₂ × ((Vin / Vout) − 1)

Where:

- **R₁** = LDR Resistance
- **R₂** = 470Ω Reference Resistor
- **Vin** = 5V
- **Vout** = Measured Output Voltage

---

## Hardware Block Diagram

```
LED
   │
   ▼
Optical Fiber
   │
   ▼
VOC Sensing Region
   │
   ▼
LDR Receiver
   │
   ▼
Arduino UNO
   │
   ▼
16×2 LCD Display
```

---

## Applications

- Environmental Monitoring
- Air Quality Monitoring
- Industrial Safety
- Chemical Laboratories
- Smart Sensor Systems
- Research and Educational Projects

---

## Project Files

```
Fiber-Optic-VOC-Sensor/
│── voc_sensor.ino
│── Circuit_Diagram.jpg
│── README.md
```

---

## Skills Demonstrated

- Embedded C Programming
- Arduino Programming
- Analog-to-Digital Conversion (ADC)
- Optical Fiber Sensing
- Sensor Interfacing
- LCD Interfacing
- Voltage Divider Circuits
- Embedded Hardware Prototyping

---

## Future Improvements

- OLED Display
- ESP32 Wi-Fi Monitoring
- Cloud Data Logging
- Mobile Application
- Real-Time Graph Visualization
- Wireless Sensor Network Integration

---

## Author

**Ravichandran C S**

GitHub: https://github.com/Ravi-eng17

LinkedIn: https://linkedin.com/in/ravi-chandran-cs-3923811b3
