## Circuit Design

This solar-powered battery charger and power bank's circuit design comprises several critical components, each contributing to the system's intelligent charging, power regulation, communication, and battery management. Here's an overview of these essential circuit blocks:

### Power Supply Regulation Circuit
At the heart of our charging system lies the power supply regulation circuit. We have integrated the MP2013A IC to ensure efficient and stable power distribution to various components. This integrated circuit plays a pivotal role in converting the input voltage to a regulated output, maintaining the desired voltage level with precision. This regulation is crucial to ensure consistent and reliable charging and power distribution throughout the device.
![Power regulation](https://github.com/RavinduMPK/Power-Bank-Project/assets/68577937/4f088bf7-ad0b-4e08-8f10-b538718e5b26)

### PD Controller Circuit
The PD (Power Delivery) controller circuit incorporates the CCG3PA IC, which is responsible for intelligently managing the USB Type-C power delivery protocol. This protocol ensures optimal power negotiation and distribution between devices, enabling fast and safe charging. The CCG3PA IC handles communication between our charger and connected devices, adapting power levels and profiles to deliver an optimized charging experience.
![PD controller](https://github.com/RavinduMPK/Power-Bank-Project/assets/68577937/a8e2d9dd-5186-4a88-af0d-234c084720a1)

### USB Type-C Interface
The inclusion of a USB Type-C interface signifies the modern and versatile approach of our charger. The USB Type-C interface allows bidirectional power and data transfer, ensuring compatibility with a wide range of devices. Its reversible design eliminates the hassle of inserting the connector in a specific orientation, enhancing user convenience.
![Type-C interface](https://github.com/RavinduMPK/Power-Bank-Project/assets/68577937/bd08450b-21ce-43a8-a289-1b4c4e3921fb)

### Battery Management System
For safe and efficient battery charging and management, we have integrated the MP2651 Battery Management System (BMS) IC. The BMS IC monitors and controls various aspects of battery charging, including voltage, current, and temperature. It ensures proper charging profiles, protects against overcharging, and enhances the overall safety and performance of the Li-ion battery pack.
![BMS_1](https://github.com/RavinduMPK/Power-Bank-Project/assets/68577937/8d13cb92-283f-4815-bce9-92b8ec4c39a7)
![BMS_2](https://github.com/RavinduMPK/Power-Bank-Project/assets/68577937/b0c92d1a-0a4e-46fb-9f34-a9f9bb14aa23)

### Microcontroller Unit
To facilitate intelligent control, monitoring, and user interaction, we've incorporated the ATtiny 85 microcontroller unit. This microcontroller serves as the brain of our system, overseeing the charging process, displaying relevant information on the LCD display, and executing the smart charging algorithm. Its programmable nature allows us to tailor the charging behavior to maximize battery life and efficiency.
![MCU](https://github.com/RavinduMPK/Power-Bank-Project/assets/68577937/24f96785-498c-44d1-9487-d7a5591a5a5f)
