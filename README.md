# FTTech SAMD Boards - Professional Arduino SDK

![Arduino IDE Support](https://img.shields.io/badge/Arduino-IDE%20Support-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-SAMD51%20(Cortex--M4F)-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

This repository contains the official **FTTech** hardware package for boards based on the SAMD51 (Cortex-M4F) microcontroller. Designed for industrial applications and high-performance IoT, this SDK provides full support for the Arduino ecosystem.

---

## 🚀 Supported Boards

### SmartNode 3S Family
*   **SmartNode 3S V9:** Industrial flagship featuring the SAMD51J20A.
*   **SmartNode 3S V8:** Robust version for process control.
*   **SmartNode 3S V1/V0:** Legacy versions with continuous support.

### SmartNode 1S Family
*   **SmartNode 1S:** Compact and efficient for remote sensing.
*   **SmartNode Swarm:** Special edition optimized for mesh networks and low power consumption.

---

## 🛠️ Installation (Arduino IDE)

To use FTTech boards in your development environment, follow the steps below:

1.  Open the **Arduino IDE**.
2.  Go to **File > Preferences**.
3.  In the **Additional Boards Manager URLs** field, paste the following URL:
    ```text
    https://raw.githubusercontent.com/FTTechBrasil/CustomBoardsPublic/master/IndexFiles/package_fttech_index.json
    ```
4.  Go to **Tools > Board > Boards Manager**.
5.  Search for **"FTTech"** and click **Install**.

---

## ✨ Version 3.0.0 Highlights

*   **Optimized Architecture:** Lightweight package with automatic tool dependency management.
*   **Industrial-Grade Documentation:** Variants documented using Doxygen standards.
*   **High Performance:** Native support for overclocking (up to 200MHz) and Instruction Cache.
*   **Modern Bootloader:** Supports **UF2** (drag-and-drop) updates and corrected status LED pinouts.
*   **USB Stacks:** Choose between the standard Arduino stack or **Adafruit TinyUSB**.

---

## 📋 Technical Specifications (SAMD51)

| Feature | Specification |
| :--- | :--- |
| **Core** | ARM Cortex-M4F with FPU (Floating Point Unit) |
| **Clock** | 120 MHz (Native) up to 200 MHz (Configurable) |
| **Flash** | Up to 1 MB |
| **SRAM** | Up to 256 KB |
| **Interfaces** | SERCOM (UART, SPI, I2C), QSPI, ADC, DAC, PWM |
| **Operating Voltage** | 3.3V |

---

## 🔧 Support and Development

If you encounter any issues or have suggestions for improvement:

1.  Check the [Official Documentation](https://www.fttech.com.br).
2.  Open an **Issue** in this repository.
3.  Contact us at [contato@fttech.com.br](mailto:contato@fttech.com.br).

---

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file (if available) or file headers for more details.

Copyright © 2026 **FTTech - Soluções em Tecnologia**. All rights reserved.
