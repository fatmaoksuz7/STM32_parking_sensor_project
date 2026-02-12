# Ultrasonic Parking Sensor System
This project is an embedded system application developed as a part of my studies in **Electrical and Electronics Engineering**. It is designed to assist vehicle parking by measuring distance and providing feedback.

## 🚀 Overview
The system uses an ultrasonic sensor to detect obstacles and calculates the distance in real-time. Depending on the proximity, it triggers visual (LED) or audible (Buzzer) alerts to warn the driver.

## 🛠 Hardware Components
* **Microcontroller:** STM32 Nucleo-F303RE (ARM Cortex-M4)
* **Sensor:** HC-SR04 Ultrasonic Sensor
* **Indicators:** Buzzer and LEDs
* **Power:** USB or External Power Supply

## 💻 Technical Details
* **Language:** C
* **Environment:** STM32CubeIDE
* **Peripherals Used:**
  * **GPIO:** For controlling LEDs and Buzzer.
  * **TIM (Timers):** For precise microsecond delays and PWM signals.
  * **UART:** For debugging and sending distance data to the serial monitor.

## 📈 Future Improvements
* Integration with an **Industrial Automation** or **PLC** environment for warehouse safety.
* Adding an LCD screen to display the exact distance in centimeters.
* Implementing a mobile app interface via Bluetooth.

## 📝 License
This project is open-source and available for educational purposes.
