# NRF54L15_IOT_Board

This repository contains the full schematic for a compact and modular sensor interface board based on the **Nordic NRF54L15 SoC**. The design integrates essential peripherals for embedded and IoT development, offering a flexible foundation for prototyping, low-power sensing, and wireless applications.

---

## 🔧 Key Features

### 🔹 NRF54L15 Core
- Main system-on-chip with integrated BLE and processing
- Includes power filtering, decoupling caps, 32MHz crystal, and antenna matching network
- Optimized for low-power wireless applications

### 🔹 GPIO Expansion
- Headers available for ports **P0**, **P1**, and **P3**
- Ideal for connecting external sensors, displays, or digital I/O modules

### 🔹 External Flash Interface
- SPI flash interface with level-select jumper
- Supports 3V-compatible memory chips
- Decoupled and ESD-protected

### 🔹 Barcode Reader Input
- 6-pin JST interface for TTL barcode modules (e.g., 1D/2D)
- Features pull-up resistors and ESD diodes
- Compatible with serial-output readers

### 🔹 Buzzer Control
- Transistor-switched output
- Enable pin routed to GPIO
- Supports active and passive buzzers

### 🔹 Debug Interface
- SWD (Serial Wire Debug) header
- For programming and real-time debugging via standard ARM tools

### 🔹 Voltage Divider
- Basic analog voltage-sensing setup
- Can monitor battery voltage or signal levels via ADC

### 🔹 Motor Driver
- Dual-channel H-bridge motor driver
- For small DC motors or actuators
- Protection components (diodes, resistors) included

### 🔹 PIR Sensor Connector
- 3-pin JST header compatible with **HC-SR501** and similar sensors
- Provides clean 3.3V power and GPIO input for motion detection

### 🔹 Power Supply
- Onboard **LDO regulator** (e.g., AMS1117-3.3 or similar)
- Converts battery input to stable 3V output
- Proper input/output decoupling and filtering included

### 🔹 Switch Interface
- Tactile push-button with pull-up configuration
- Debounced and routed to MCU GPIO

---

## 🧩 Design Highlights

- 📐 **Board Size**: 45mm × 45mm
- 🔌 All connectors are **JST type** for plug-and-play integration
- 📏 Modular, clearly labeled layout for clean routing and testability
- 🛠️ Includes power planes, debug points, and optional configuration jumpers

---

## 📂 Repository Contents

- `nrf54l15_iot_board.sch` – Complete schematic (KiCad format)  
- `nrf54l15_iot_board.pdf` – Printable schematic overview  
- `board_layout.png` – Visual layout reference  
- `docs/` – Additional documentation and test instructions (optional)

---

## 📦 Applications

- Wireless sensor nodes  
- Portable IoT data loggers  
- BLE-connected automation modules  
- Educational embedded systems kits  
- Rapid prototyping platforms for embedded R&D

---

## 👨‍💻 Author

**Muddessir Arif**  
📞 +92 340 0586446  
📧 [muddessirarif140174@gmail.com](mailto:muddessirarif140174@gmail.com)

---

> ⚠️ This project is intended for prototyping, testing, and development. Ensure safe handling of power inputs and follow datasheet guidelines for the NRF54L15 and all connected modules.
