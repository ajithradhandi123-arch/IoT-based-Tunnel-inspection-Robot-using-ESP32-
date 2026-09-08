# IoT-based-Tunnel-inspection-Robot-using-ESP32-
IoT-Based-Tunnel-Inspection-Rover-using-ESP32
│
├── src
│   ├── main_controller.c
│   └── camera_controller.c
│
├── drivers
│   ├── motor_driver.c
│   ├── gas_sensor.c
│   ├── ultrasonic_sensor.c
│   └── dht_sensor.c
│
└── README.md

---

## Working Principle

1. The **ESP32 connects to WiFi** and communicates with the **Blynk IoT platform**.
2. Sensor data (gas levels, temperature, humidity, and distance) is continuously monitored.
3. If dangerous conditions are detected, alerts are sent to the **Blynk mobile application**.
4. The **ESP32-CAM streams live video** from the rover.
5. The rover can be controlled remotely through **Blynk virtual buttons**.

---

## Blynk Control Functions

| Virtual Pin | Function            |
| ----------- | ------------------- |
| V4          | Move Forward        |
| V5          | Move Backward       |
| V6          | Turn Right          |
| V7          | Turn Left           |
| V8          | Stop Motors         |
| V9          | Motor Speed Control |
| V11         | Distance Monitoring |
| V12         | Camera Stream Link  |

---

## Applications

* Tunnel inspection
* Industrial safety monitoring
* Hazardous gas detection
* Disaster rescue environments
* Underground mining safety

---

## Future Improvements

* Autonomous navigation
* AI-based obstacle detection
* Cloud data logging
* GPS tracking system
* Multiple camera integration

---

## Author

GUNAPRASANTH PASUPULETI

Embedded Systems / IoT Project