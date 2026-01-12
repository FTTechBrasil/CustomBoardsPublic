# FTTech SAMD Boards - Professional Arduino SDK

![Arduino IDE Support](https://img.shields.io/badge/Arduino-IDE%20Support-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-SAMD51%20(Cortex--M4F)-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Este repositório contém o pacote oficial de hardware da **FTTech** para placas baseadas no microcontrolador SAMD51 (Cortex-M4F). Projetado para aplicações industriais e de IoT de alta performance, este SDK oferece suporte completo ao ecossistema Arduino.

---

## 🚀 Placas Suportadas

### Família SmartNode 3S
*   **SmartNode 3S V9:** Flagship industrial com SAMD51J20A.
*   **SmartNode 3S V8:** Versão robusta para controle de processos.
*   **SmartNode 3S V1/V0:** Versões legadas com suporte contínuo.

### Família SmartNode 1S
*   **SmartNode 1S:** Compacta e eficiente para sensores remotos.
*   **SmartNode Swarm:** Edição especial otimizada para redes mesh e baixo consumo.

---

## 🛠️ Instalação (Arduino IDE)

Para utilizar as placas FTTech no seu ambiente de desenvolvimento, siga os passos abaixo:

1.  Abra o **Arduino IDE**.
2.  Vá em **File > Preferences** (Arquivo > Preferências).
3.  No campo **Additional Boards Manager URLs**, cole a seguinte URL:
    ```text
    https://raw.githubusercontent.com/FTTechBrasil/CustomBoardsPublic/master/IndexFiles/package_fttech_index.json
    ```
4.  Vá em **Tools > Board > Boards Manager** (Ferramentas > Placa > Gerenciador de Placas).
5.  Pesquise por **"FTTech"** e clique em **Install**.

---

## ✨ Destaques da Versão 3.0.0

*   **Arquitetura Otimizada:** Pacote leve com gerenciamento automático de dependências.
*   **Documentação Industrial:** Variantes documentadas com padrão Doxygen.
*   **Alta Performance:** Suporte nativo a overclock (até 200MHz) e Cache de Instruções.
*   **Bootloader Moderno:** Suporte a atualização via **UF2** (arrastar e soltar) e LEDs de status corrigidos.
*   **Stacks USB:** Escolha entre a stack padrão do Arduino ou a **Adafruit TinyUSB**.

---

## 📋 Especificações Técnicas (SAMD51)

| Característica | Especificação |
| :--- | :--- |
| **Core** | ARM Cortex-M4F com FPU (Unidade de Ponto Flutuante) |
| **Clock** | 120 MHz (Nativo) até 200 MHz (Configurável) |
| **Flash** | Até 1 MB |
| **SRAM** | Até 256 KB |
| **Interfaces** | SERCOM (UART, SPI, I2C), QSPI, ADC, DAC, PWM |
| **Tensão de Operação** | 3.3V |

---

## 🔧 Suporte e Desenvolvimento

Se você encontrar algum problema ou tiver sugestões de melhoria:

1.  Verifique a [Documentação Oficial](https://www.fttech.com.br).
2.  Abra uma **Issue** neste repositório.
3.  Entre em contato via [contato@fttech.com.br](mailto:contato@fttech.com.br).

---

## 📄 Licença

Este projeto é licenciado sob a licença MIT - consulte o arquivo `LICENSE` (se disponível) ou os cabeçalhos dos arquivos para mais detalhes.

Copyright © 2026 **FTTech - Soluções em Tecnologia**. Todos os direitos reservados.
