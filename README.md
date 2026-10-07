# Vinicius Pedrosa

**Embedded Linux / Kernel Engineer**

Low-level embedded systems in C, C++ and Rust: Linux platforms, RTOS firmware,
bootloaders and hardware bring-up.

## Current focus

- Linux kernel upstream work and mainline bring-up of the **Radxa Cubie A7Z (Allwinner A733, ARM64)**.
- Serial/UART drivers, Device Tree bindings, termios and clock debugging on real hardware.
- Embedded Linux platforms with Yocto / OpenEmbedded, alongside Zephyr RTOS firmware.

## Linux kernel upstream work

I contribute as **Vinicius Pedrosa** on the Linux mailing lists. My current
`8250_dw` / DesignWare APB UART patch series is under review.

- [Allwinner A733 UART support — patch series](https://lkml.iu.edu/2610.0/09102.html): UART driver and Device Tree binding changes, with Cubie A7Z console and termios testing.
- [BUSY-safe divisor programming](https://lkml.iu.edu/2610.0/09157.html): investigation of DLF detection, divisor hooks and lost UART interrupts.
- [DLF autodetection — review discussion and board tests](https://lkml.iu.edu/2610.0/10403.html): distinguishing the A733 RS485 register from a real DLF register.
- [A733 CCU — reboot and power-off validation](https://lkml.iu.edu/2610.0/09219.html): hardware observations shared during linux-sunxi clock review.

These links document submitted work and review discussions, rather than a claim
of merged kernel commits. Hardware validation is on the Cubie A7Z; testing on a
UART with a real DLF register remains outstanding.

## Selected projects

- [malleus-rtos](https://github.com/VinicKMx/malleus-rtos) — Experimental Rust RTOS design for ARM Cortex-M; manifest validation and timing analysis work today, while the kernel does not yet boot on hardware.
- [rampart-boot](https://github.com/VinicKMx/rampart-boot) — C/Rust secure firmware lifecycle work: image signing and verification tooling implemented; device boot, update and recovery flows in development.
- [gate-link](https://github.com/VinicKMx/gate-link) — C/Zephyr LoRa remote actuator protocol with authenticated commands, ACK/retry and replay protection; validated on an ESP32 bench pair.
- [coffee-roaster-controller-zephyr](https://github.com/VinicKMx/coffee-roaster-controller-zephyr) — STM32/Zephyr controller architecture separating temperature acquisition, heater control and safety authority; current default actuator is an LED mock.

## Technical areas

- **Systems:** Linux kernel / Embedded Linux, Device Tree, drivers, bootloaders, Zephyr RTOS.
- **Languages and hardware:** C / C++ / Rust; ARM / ARM64, STM32, ESP32.
- **Platforms and debugging:** Yocto / OpenEmbedded, GDB, serial consoles, logic analyzer and hardware debugging.
- **Industrial connectivity:** UART / RS-485, Modbus, MQTT and embedded networking.

## Contact

[LinkedIn](https://www.linkedin.com/in/vinicius-eduardo-alves-pedrosa/) · [GitHub](https://github.com/VinicKMx)
