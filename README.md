# 25011102007_FIoT_Lab
# Fundamentals of Internet of Things (IoT) – Laboratory

**Course:** 25CS2741 – Fundamentals of Internet of Things + Lab  
**University:** Shiv Nadar University Chennai  
**Registration Number:** 25011102007  
**Repository:** `25011102007_FIoT_Lab`

---

## About This Repository

This repository contains the laboratory experiments, source code, circuit diagrams, implementations, and documentation completed as part of the **Fundamentals of Internet of Things (IoT)** course.

The experiments focus on understanding microcontroller-based embedded systems, hardware interfacing, embedded C programming, and communication protocols used in IoT applications.

The repository is organized into two major sections based on the microcontroller platforms:

- **8051 Microcontroller**
- **STM32 Microcontroller**

Each experiment is organized into its respective CAT folder. The documentation includes the experiment objective, hardware setup, circuit diagrams, implementation details, and observations or inference.

## Repository Structure

```text
25011102007_FIoT_Lab/
│
├── 8051/
│   ├── CAT1/
│   ├── CAT2/
│   ├── CAT3/
│   ├── CAT4/
│   ├── CAT5/
│   ├── CAT6/
│   ├── CAT7/
│   └── README.md
│
├── STM32/
│   ├── CAT8/
│   ├── CAT9/
│   ├── CAT10/
│   ├── CAT11/
│   ├── CAT12/
│   ├── CAT13/
│   ├── CAT14/
│   └── README.md
│
├── .gitignore
└── README.md
```

## Platforms and Hardware

### 1. 8051 Microcontroller

The 8051 section focuses on embedded C programming and peripheral interfacing using the AT89S52 microcontroller.

Topics include:

- GPIO programming and LED interfacing
- Timers and interrupt handling
- Matrix keypad interfacing
- Seven-segment display interfacing
- UART serial communication
- 16×2 LCD interfacing
- Stepper motor control and PWM

### 2. STM32 Microcontroller

The STM32 section focuses on embedded programming using STM32 development boards and the STM32 Hardware Abstraction Layer (HAL).

Topics include:

- GPIO configuration and LED control
- Timer-based operations
- UART communication
- ESP8266 Wi-Fi interfacing
- HTTP communication
- BME280 sensor interfacing using I²C
- MQTT communication

## Software and Development Tools

The laboratory experiments use the following development tools and software:

- **Keil µVision / Keil MDK** – Embedded C development
- **STM32CubeMX** – STM32 peripheral configuration
- **STM32 HAL** – Hardware abstraction layer
- **Arduino IDE Serial Monitor** – Serial communication and debugging
- **Bosch BME280 API** – Environmental sensor interfacing
- **ESP8266 Libraries and APIs** – Wi-Fi and IoT communication

## Documentation Format

Each experiment is documented using a consistent structure:

1. Experiment Number and Date
2. Name of the Experiment
3. Hardware Setup / Platform
4. Task Number
5. Circuit Diagram
6. Core Logic / Pseudocode / Code
7. Inference

Experiments containing multiple tasks are organized into separate task folders wherever applicable.

## How to Navigate This Repository

- Open the `8051` folder to explore experiments related to the AT89S52 microcontroller.
- Open the `STM32` folder to explore STM32-based experiments.
- Navigate to the respective CAT folder to access experiment files and documentation.
- Refer to the README files for experiment details and implementation explanations.

## Learning Outcomes

Through these laboratory experiments, the repository demonstrates practical understanding of:

- Microcontroller architecture and embedded C programming
- GPIO, timers, and interrupts
- Hardware and sensor interfacing
- UART serial communication
- Wi-Fi communication using ESP8266
- IoT protocols such as MQTT
- Sensor data acquisition and transmission
- Embedded application development and debugging

---

**Note:** This repository documents the laboratory work completed as part of the Fundamentals of Internet of Things course. Hardware configurations and implementation details are specific to the respective experiments.
