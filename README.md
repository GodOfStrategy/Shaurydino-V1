
# Shaurdino-V1
A custom devboard tailored for small and medium applications.
I plan to use it to efficiently reduce electricity consumption in a voice recorder and announcer module of my own.

Key Features
Core MCU:

Raspberry Pi RP2040 dual‑core ARM Cortex‑M0+ processor.

Connected to a 12 MHz crystal oscillator for precise clocking.


USB Interface:

USB‑C connector with ESD protection (USBLC6‑2SC6).



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


Here is the 3D model of my PCB.
<img width="1584" height="892" alt="Screenshot 2025-12-19 182844" src="https://github.com/user-attachments/assets/f871791a-3a05-4a31-9932-0241d4228020" />

You can find the schematics in the repository as well as the PCB design and it's Gerber files.
Here are the PCB and Schematics Images for your reference here aswell:
<img width="926" height="653" alt="Screenshot 2025-12-13 184159" src="https://github.com/user-attachments/assets/acb29a58-dfae-4880-b8e9-1781f1ecc0db" />
<img width="735" height="558" alt="Screenshot 2025-12-17 222851" src="https://github.com/user-attachments/assets/7c90573e-26f5-4503-bf70-16d245196f12" />

The BOM for the project- [Blueprint_Project - Blueprint_Project (1).csv](https://github.com/user-attachments/files/25369597/Blueprint_Project.-.Blueprint_Project.1.csv)
