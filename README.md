# Shaurdino-V1
A custom devboard tailored for small and medium applications.
Board Overview
This design is a compact RP2040‑based microcontroller board built for embedded projects that need USB connectivity, external flash storage, and stable power regulation. It integrates all the essentials for a reliable development platform while leaving room for expansion through headers.

Key Features
Core MCU:

Raspberry Pi RP2040 dual‑core ARM Cortex‑M0+ processor.

Connected to a 12 MHz crystal oscillator for precise clocking.

Full SWD debug header for programming and development.

USB Interface:

USB‑C connector with ESD protection (USBLC6‑2SC6).

Direct USB D+/D– lines to the RP2040 for native USB device support.

Power Regulation:

NCP-1117 linear voltage regulator providing a clean 3.3 V rail.

Decoupling capacitors distributed across the board for stable supply.

Designed to accept 5 V from USB or a regulated external source.

Memory:

W25Q32JVSS QSPI flash for program and data storage.

Connected via dedicated QSPI pins for high‑speed access.

Connectivity & Expansion:

Dual 20‑pin headers, exposing GPIO0–GPIO29, ADC inputs, and power rails for running peripherals safely.

Breakout for SWCLK and SWDIO debug signals.

RUN pin with pull‑up for reset control.

Supporting Components:

Crystal oscillator network with capacitors and resistor for stable timing.

Multiple capacitors (C1–C17, C36–C39) for filtering and decoupling higher frequency  and low frequency smoothning.

Resistors for pull‑ups/pull‑downs and configuring certain components.

Design Intent
The board is structured as a general‑purpose development platform: small enough for prototyping, yet robust enough for integration into finished projects. With USB‑C power and data, onboard flash, and full GPIO breakout, it’s versatile for applications ranging from IoT nodes to custom controllers. The careful inclusion of ESD protection, decoupling, and regulated rails ensures reliable operation even in noisy environments.



You can find the schematics in the repository as well as the PCB design and it's Gerber files.
