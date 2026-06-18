# Smart Thermostat: Automated Climate Control System

An automated smart thermostat built using an STM32F103 microcontroller and STM32CubeIDE. This project reads analog temperature data, processes it using firmware logic, and controls physical actuators to maintain temperature thresholds.

## Features
- Real-Time Monitoring:Processes analog data from a TMP36 temperature sensor via ADC.
- Automated Cooling:Triggers a cooling fan and an LED warning alarm when temperatures exceed 40°C.
- Interactive User Interface: Includes an LCD screen and a hardware-debounced push-button to toggle display units between Celsius and Fahrenheit.
- Serial Data Logging: Transmits live telemetry data via UART to a Virtual Terminal for remote debugging.

## System Architecture & Simulation
The complete circuit design and firmware execution were simulated and validated using the Proteus Design Suite. 

![Proteus Simulation View](your-screenshot-name.png)

## Tech Stack & Peripherals
- Language: Embedded C
- IDE: STM32CubeIDE
- Hardware Abstraction: STM32 HAL Library
- Simulation Tool: Proteus Design Suite
- Microcontroller Peripherals: ADC1 (Channel 1), GPIO (Inputs/Outputs), USART2 (9600 Baud)
