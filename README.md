<div align="center">

# Olá, eu sou MrStuani 👋

🌐 **Português** | [English](README.en.md)

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

Sou formado em Análise e Desenvolvimento de Sistemas (ADS). Programo em C,
Python e JavaScript, e a área que mais me prende é a de baixo nível:
firmware, protocolos USB, microcontroladores e medição. Gosto de abrir a
caixa e descobrir como as coisas realmente funcionam, e de conseguir provar
isso com números. Também uso Python para automatizar tarefas repetitivas do
dia a dia.

## 🎯 Projeto principal: Gamer Peripheral Latency Meter

Hoje estou dedicado ao **[gamer-latency-meter](https://github.com/MrStuani/gamer-latency-meter)**,
um medidor de latência fim a fim para periféricos gamer, com resolução de
~20 - 40 ns, feito com duas placas baratas e um navegador:

- **CH32V307**: host USB-HID a 8 kHz que converte os relatórios de
  mouse/teclado em bordas GPIO limpas.
- **Pico 2 (RP2350)**: registra o timestamp das bordas usando PIO
  (3 state machines).
- **App web com WebSerial**: sem dependências, sem build, disponível em
  **10 idiomas**.

> Este é um projeto **vibe coded**: boa parte do código foi gerada ou
> assistida por IA. A arquitetura, porém, é minha: o fluxo do sinal, as
> escolhas de hardware, o protocolo de medição e a divisão de
> responsabilidades entre as duas placas e o app. A IA me deu velocidade;
> o design é meu.

## 🐍 Automações em Python

- **[Download-Relatorio-Manuten-o](https://github.com/MrStuani/Download-Relatorio-Manuten-o)**:
  automação que simplifica a geração, a conversão e o envio de relatórios
  de manutenção.
- **[Chatbot-automation-selenium](https://github.com/MrStuani/Chatbot-automation-selenium)**:
  envio automatizado de mensagens com interface gráfica, usando Tkinter,
  Selenium e Google Sheets.

## 🛠 Stack

- **Firmware:** C (RP2350 / PIO) e C bare-metal (CH32V307, RISC-V `rv32imac`)
- **Automação:** Python, Selenium, Tkinter, Google Sheets
- **Hardware:** Raspberry Pi Pico 2, WCH CH32V307 / CH32V305, Arduino, RP2040
- **Web:** JavaScript vanilla, WebSerial, HTML/CSS
- **Ferramentas:** Arduino IDE, MounRiver Studio, gdb/openocd, osciloscópio,
  lupa e café

## 📬 Contato

- GitHub: [MrStuani](https://github.com/MrStuani)
