# FTTech SAMD Boards - Professional Arduino SDK

![Arduino IDE Support](https://img.shields.io/badge/Arduino-IDE%20Support-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-SAMD51%20(Cortex--M4F)-orange?style=for-the-badge)
![Version](https://img.shields.io/badge/Release-v3.0.1-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Official hardware package for **FTTech** SAMD51-based boards. Designed for high-performance industrial IoT and mission-critical applications.

---

## 🚀 Supported Boards

### SmartNode 3S Family (SAMD51J20A)
*   **SmartNode 3S V9:** The latest industrial flagship.
*   **SmartNode 3S V8:** Enhanced process control version.
*   **SmartNode 3S V1/V0:** Legacy versions with full support.

### SmartNode 1S Family (SAMD51G18A)
*   **SmartNode 1S:** Compact sensing node.
*   **SmartNode Swarm:** Optimized for mesh networks.

---

## ✨ Release 3.0.1 Highlights (Bugfix)

*   **Surgical Pin Mapping:** Fixed critical pin assignment inconsistencies for the SmartNode 3S family.
*   **V8 Restoration:** Expanded GPIO access up to **D53**, fully mapping Click 1-4 power controls and high-speed Serial pads.
*   **V9 Enhancements:** Added native mapping for 32kHz Crystal, JTAG/SWD debug pins, and the dedicated `WUSB` pin.
*   **Conflict Resolution:** Fixed Click 1 Power overlap with USB pins in V8 variant.

---

## 📍 Pin Assignment Reference (SmartNode 3S)

### SmartNode 3S V8 (Old)
| Function | Arduino Pin | Port | Notes |
| :--- | :--- | :--- | :--- |
| **Serial1 RX/TX** | D0 / D1 | PA13 / PA12 | Click 2 |
| **Serial2 RX/TX** | D9 / D16 | PA07 / PA04 | Click 4 |
| **Serial3 RX/TX** | D41 / D42 | PB30 / PB31 | Click 3 |
| **Serial4 RX/TX** | D13 / D11 | PA17 / PA16 | Click 1 |
| **I2C SDA / SCL** | D23 / D24 | PA22 / PA23 | Main Bus |
| **SPI MISO/MOSI/SCK** | D25/D26/D27 | PB11/PB12/PB13 | Main Bus |
| **CLICK_ONE PWR** | D43 | PA21 | Power Control |
| **CLICK_TWO PWR** | D49 | PB16 | Power Control |
| **CLICK_THREE PWR**| D50 | PB17 | Power Control |
| **CLICK_FOUR PWR** | D52 | PB22 | Power Control |
| **POWER_5V (All)** | D45 | PB07 | Master Click Power |

### SmartNode 3S V9 (New)
| Function | Arduino Pin | Port | Notes |
| :--- | :--- | :--- | :--- |
| **Serial1 RX/TX** | D13 / D7 | PA17 / PA16 | Click 1 |
| **Serial2 RX/TX** | D0 / D1 | PA13 / PA12 | Click 2 |
| **Serial3 RX/TX** | D9 / D10 | PB30 / PB31 | Click 3 |
| **Serial4 RX/TX** | D5 / D26(A3) | PA07 / PA04 | Click 4 |
| **I2C SDA / SCL** | D37 / D38 | PA22 / PA23 | Main Bus |
| **SPI MISO/MOSI/SCK** | D39/D40/D41 | PB11/PB12/PB13 | Main Bus |
| **CLICK_ONE PWR** | D11 | PA21 | Power Control |
| **CLICK_TWO PWR** | D18 | PB16 | Power Control |
| **CLICK_THREE PWR**| D19 | PB17 | Power Control |
| **CLICK_FOUR PWR** | D21 | PB22 | Power Control |
| **POWER_5V (All)** | D14 | PB07 | Master Click Power |
| **WUSB Pin** | D48 | PA27 | Special Function |

---

## 🛠️ Installation

1.  Add the following URL to your **Additional Boards Manager URLs**:
    ```text
    https://raw.githubusercontent.com/FTTechBrasil/CustomBoardsPublic/master/IndexFiles/package_fttech_index.json
    ```
2.  Search for **FTTech** in the Boards Manager and install.

---

## 📄 License

MIT License. Copyright © 2026 **FTTech - Soluções em Tecnologia**.
