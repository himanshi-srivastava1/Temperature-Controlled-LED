# Temperature-Controlled LED with Op-Amp

An automated hardware sensing system designed to monitor environmental thermal changes and provide a real-time visual indicator using analog electronics.

## 📌 Overview
This project utilizes an **LM358 Operational Amplifier** as a voltage comparator. By integrating an **NTC Thermistor**, the circuit detects when a specific temperature threshold is reached and triggers an LED. It serves as a low-cost, efficient alternative to microcontroller-based monitoring systems for applications like overheat alarms or climate control.

## 🚀 Features
* **Precision Sensing:** Uses a Negative Temperature Coefficient (NTC) thermistor for sensitive thermal detection.
* **Customizable Threshold:** Includes a 10kΩ potentiometer to manually calibrate the exact "trip point" for the LED.
* **Autonomous Operation:** Works entirely on analog logic without the need for programming or microcontrollers.
* **Versatile Applications:** Can be modified to trigger cooling fans or buzzers for industrial safety.

## 🛠️ Hardware Components
| Component | Quantity | Purpose |
| :--- | :--- | :--- |
| **IC LM358** | 1 | Operational Amplifier (Comparator) |
| **10kΩ NTC Thermistor** | 1 | Temperature Sensor |
| **10kΩ Potentiometer** | 1 | Threshold Calibration |
| **LED (Green/Red)** | 1 | Visual Indicator |
| **Resistors** | 1kΩ, 4.7kΩ | Current Limiting & Biasing |
| **Power Supply** | 5V | Circuit Power |

## ⚙️ Working Principle
1.**Sensing:** The NTC thermistor's resistance decreases as the ambient temperature increases.
2.**Comparison:** This change in resistance alters the voltage at the Op-Amp's inverting input.
3.**Triggering:** When this voltage crosses the reference threshold set by the potentiometer, the LM358 switches its output state to HIGH.
4. **Output:** The HIGH signal flows through a current-limiting resistor to turn the LED ON.

## 🔌 Circuit Diagram
(https://github.com/himanshi-srivastava1/Temperature-Controlled-LED/main/circuit-diagram.png)

## 📂 Project Structure
* `/docs`: Contains the project proposal.

## 🤝 Contributors
* **Himanshi Srivastava** 
* **Hima Sai Sankar Vidya Sagar** 
