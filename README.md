# Vinicius - Embedded & Systems Engineer

Reliable embedded systems, real-time software, and low-level tooling.

**Rust, C, Zephyr, RTOS, ARM Cortex-M, ESP32**

My work sits across the embedded stack: registers and interrupts at one end, deployment and field behaviour at the other. I care about systems whose behaviour is established before they run and inspectable when they fail: static over dynamic, checked at build time over caught at runtime, observable over merely correct.

That costs flexibility, and there are problems where it is the wrong call. I aim it at systems that have to keep running unattended.

## Featured Work

### [Malleus RTOS](https://github.com/VinicKMx/malleus-rtos) - early, in active development

Rust-native RTOS built around constraints rather than features: hard real-time scheduling, MPU fault isolation, static task sets, no dynamic allocation, and timing analysis at build time.

I started it to answer a specific question: what architectural properties would make another RTOS worth existing? That answer is still being worked out in code.

### [ESP32 Lightning Terminal](https://github.com/VinicKMx/esp32-lightning-terminal)

Bitcoin Lightning payment terminal on ESP32-S3, written in Rust. Payment flow on a device with no filesystem, no allocator to lean on, and a user waiting at the counter.

### [Gate Link](https://github.com/VinicKMx/gate-link)

LoRa remote control on Zephyr, designed for a link that drops packets: ACK and retry, with duplicate-safe command execution so a repeated frame cannot actuate twice.

## Areas

Firmware architecture, real-time systems, reliability and fault tolerance, embedded security, RTOS design, industrial protocols, Embedded Linux and Yocto, OTA update paths, hardware/software interaction.

**Languages:** C, C++, Rust, Assembly  
**Tooling:** Python, Bash  
**Architectures / MCUs:** ARM Cortex-M, RISC-V, STM32, ESP32  
**RTOS:** Zephyr, FreeRTOS  
**Buses / Protocols:** SPI, I2C, UART, CAN, Modbus, MQTT, NATS

## What I Look For

Problems where understanding the whole system is the only way through: where stopping at the abstraction boundary still leaves you with the wrong answer.

Open to conversations about embedded Rust, real-time design, firmware security, and anything low-level enough to require reading the reference manual.
