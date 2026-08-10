# Vinicius - Embedded Systems Engineer

Aerospace Engineering background, now working across the embedded stack: registers and interrupts at one end, deployment and field behaviour at the other.

**Embedded / Systems Engineering - Rust, C, Zephyr, RTOS, ESP32, ARM Cortex-M**

Most of my technical choices come down to one preference: as much of a system's behaviour as possible should be established before it runs, and inspectable when it fails. Static over dynamic, checked at build time over caught at runtime, observable over merely correct.

The trade-off is real and I would rather name it: this approach costs flexibility, and there are problems where it is the wrong call. I aim it at systems that have to keep running unattended.

## Work

Firmware and microcontrollers, RTOSes, industrial communication protocols, Embedded Linux and Yocto, OTA update paths, edge computing, and the backend integration around it.

**Languages:** C, C++, Rust, Assembly  
**MCU / RTOS:** STM32, ESP32, Zephyr  
**Linux:** Embedded Linux, Yocto  
**Buses / Protocols:** SPI, I2C, UART, CAN, Modbus, MQTT, NATS

## Main Project

### [Malleus RTOS](https://github.com/VinicKMx/malleus-rtos)

My main open-source project: a Rust-native real-time operating system where the constraints are the point rather than the feature list.

Static task set. No dynamic allocation. Schedulability established at build time. Fault containment between tasks. Enough introspection to explain a failure after the fact instead of having to reproduce it.

It is early. I started it to answer a specific question: what architectural properties would make another RTOS worth existing? That answer is still being worked out in code rather than in a design document.

## Other Work

- [ESP32 Lightning Terminal](https://github.com/VinicKMx/esp32-lightning-terminal) - ESP32-S3 Bitcoin Lightning payment terminal in Rust.
- [GateLink](https://github.com/VinicKMx/GateLink) - Zephyr-based LoRa point-to-point gate remote with ACK/retry and duplicate-safe actuator triggering.
- [Bebop Thermal Android Compat](https://github.com/VinicKMx/bebop-thermal-android-compat) - Compatibility patch workflow for FreeFlight Thermal on newer Android devices.
- [uWatt](https://github.com/VinicKMx/uwatt) - Embedded energy observability and regression testing.

## What I Look For

Problems where understanding the whole system is the only way through: where stopping at the abstraction boundary still leaves you with the wrong answer.

Open to conversations about embedded Rust, real-time design, firmware security, and anything low-level enough to require reading the reference manual.
