# ESP32 Bluetooth-Controlled Multi-Mode LED System

## Overview

Designed and developed a Bluetooth-enabled embedded control system using the ESP32 microcontroller to demonstrate wireless device control, real-time GPIO management, and menu-driven firmware architecture.

The system allows users to interact with the ESP32 through Bluetooth Classic (SPP) and execute multiple LED control modes including individual LED control, sequential LED chasing, and synchronized blinking patterns.

This project highlights key embedded systems concepts such as peripheral interfacing, serial communication, state-based control logic, and hardware-software integration.

---

## Key Highlights

✔ Bluetooth Serial Communication (SPP)

✔ Menu-Driven Firmware Design

✔ Real-Time LED Control

✔ Multi-Mode Operation

✔ GPIO Configuration and Management

✔ Modular Embedded Software Development

✔ Scalable Architecture for Future IoT Applications

---

## System Architecture

```text
Smartphone
(Bluetooth Terminal)
          │
          ▼
Bluetooth Communication
          │
          ▼
ESP32 Firmware
          │
 ┌────────┼────────┐
 ▼        ▼        ▼
Mode 1   Mode 2   Mode 3
LED      Chasing  Blinking
Control
          │
          ▼
GPIO Driver Layer
          │
          ▼
LED Hardware Interface
```

---

## Technical Specifications

| Parameter | Description |
|------------|-------------|
| Controller | ESP32 |
| Programming Language | Embedded C/C++ |
| Communication Protocol | Bluetooth Classic (SPP) |
| Development Environment | Arduino IDE |
| Operating Voltage | 3.3V |
| Output Devices | 4 LEDs |

---

## Hardware Configuration

| Component | Quantity |
|------------|-----------|
| ESP32 Development Board | 1 |
| LEDs | 4 |
| 220Ω Resistors | 4 |
| Breadboard | 1 |
| Jumper Wires | As Required |

### GPIO Allocation

| LED | GPIO |
|------|------|
| Red | GPIO14 |
| Blue | GPIO27 |
| Green | GPIO13 |
| White | GPIO12 |

---

## Functional Features

### Mode 1 – Individual LED Control

Provides direct user control over each LED through Bluetooth commands.

Supported Commands:

- R / r → Red LED ON/OFF
- B / b → Blue LED ON/OFF
- G / g → Green LED ON/OFF
- W / w → White LED ON/OFF

### Mode 2 – Sequential LED Chasing

Implements a running-light pattern where LEDs are activated sequentially to simulate motion.

### Mode 3 – Synchronized LED Blinking

Activates all LEDs simultaneously in periodic ON/OFF cycles.

---

## Firmware Workflow

```text
System Initialization
         │
         ▼
Bluetooth Initialization
         │
         ▼
Menu Generation
         │
         ▼
User Command Reception
         │
         ▼
Mode Selection
         │
         ▼
LED Control Logic
         │
         ▼
GPIO Output Update
```

---

## Engineering Concepts Demonstrated

- Embedded Firmware Development
- Bluetooth Communication
- Serial Data Processing
- GPIO Driver Control
- State-Based Application Design
- Hardware Interfacing
- Real-Time Event Handling
- Embedded Debugging Techniques

---

## Applications

- Home Automation Systems
- Wireless Lighting Control
- Industrial Status Indication Systems
- Educational Embedded Platforms
- IoT Device Prototyping

---

## Future Enhancements

- FreeRTOS-Based Task Scheduling
- Mobile Application Interface
- PWM-Based Brightness Control
- Voice Command Integration
- Wi-Fi and MQTT Connectivity
- Cloud-Based Monitoring Dashboard

---

## Project Outcome

Successfully developed a Bluetooth-enabled embedded control system capable of executing multiple operational modes while maintaining reliable wireless communication and responsive GPIO control.

The project strengthened practical knowledge in firmware development, communication protocols, embedded debugging, and system-level design.

---

## Author

Shaik

Embedded Systems | Firmware Development | IoT

Skills:
C | Embedded C | ESP32 | UART | SPI | I2C | GPIO | Bluetooth | Firmware Development
