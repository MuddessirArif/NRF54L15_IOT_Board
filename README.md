# NRF54L15_IOT_Board
Compact sensor hub schematic using NRF54L15 SoC. Includes GPIO headers, flash, PIR, buzzer, motor driver, SWD, LDO regulator, and barcode reader interface. JST connectors, 45×45 mm layout, modular design for embedded and IoT applications. 

NRF54L15 Sensor Hub – Schematic Overview
This repository contains the complete schematic for a compact sensor interface board built around the Nordic NRF54L15. The design brings together several commonly used peripherals in a modular layout, making it ideal for prototyping and low-power embedded applications.
Key Features
•	NRF54L15 Core
Central SoC with all essential support components: power filtering, crystal, and antenna matching network.
•	GPIO Expansion
Breakout headers for GPIO ports (P0, P1, P3) to connect additional sensors or modules.
•	External Flash Interface
Flash memory circuit with voltage jumper for 3V compatibility and easy interfacing.
•	Barcode Reader Input
6-pin JST connector with pull-ups and ESD protection for TTL-level barcode modules.
•	Buzzer Control
Transistor-switched buzzer driver with enable line for simple audio feedback.
•	Debug Interface
Standard SWD (Serial Wire Debug) header for firmware flashing and debugging.
•	Voltage Divider
Basic analog input setup for battery or signal monitoring.
•	Motor Driver
Dual-channel motor driver for low-voltage DC motors, complete with protection components.
•	PIR Sensor Connector
3-pin JST interface designed for motion sensors like the HC-SR501.
•	Power Supply
Onboard LDO providing a clean 3V rail from battery input.
•	Switch Interface
Tactile micro switch input for user interaction or control logic.
Additional Notes
•	All connectors are JST type for plug-and-play wiring.
•	Layout is modular and organized for clean routing and easy testing.
•	Board dimensions: 45mm x 45mm.
•	Common elements like power planes, switch jumpers, and debugging points are included.
