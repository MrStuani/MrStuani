<div align="center">

# Hi, I'm MrStuani 👋

🌐 [Português](README.md) | **English**

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

I have a degree in Systems Analysis and Development (a Brazilian tech
degree). I write C, Python and JavaScript, and the area that hooks me the
most is low-level work: firmware, USB protocols, microcontrollers and
measurement. I like opening the box to see how things really work, and being
able to back it up with numbers. I also use Python to automate repetitive
day-to-day tasks.

## 🎯 Main project: Gamer Peripheral Latency Meter

I'm currently focused on **[gamer-latency-meter](https://github.com/MrStuani/gamer-latency-meter)**,
an end-to-end latency meter for gaming peripherals with ~8 ns resolution,
built with two cheap boards and a browser:

- **CH32V307**: 8 kHz USB-HID host that turns mouse/keyboard reports into
  clean GPIO edges.
- **Pico 2 (RP2350)**: timestamps the edges using PIO (3 state machines).
- **WebSerial web app**: no dependencies, no build step, available in
  **10 languages**.

> This is a **vibe coded** project: a good part of the code was generated or
> assisted by AI. The architecture, however, is mine: the signal flow, the
> hardware choices, the measurement protocol, and how responsibilities are
> split between the two boards and the app. AI gave me speed; the design
> is mine.

## 🐍 Python automations

- **[Download-Relatorio-Manuten-o](https://github.com/MrStuani/Download-Relatorio-Manuten-o)**:
  automation that streamlines generating, converting and sending
  maintenance reports.
- **[Chatbot-automation-selenium](https://github.com/MrStuani/Chatbot-automation-selenium)**:
  automated message sending with a graphical interface, built with Tkinter,
  Selenium and Google Sheets.

## 🛠 Stack

- **Firmware:** C (RP2350 / PIO) and bare-metal C (CH32V307, RISC-V `rv32imac`)
- **Automation:** Python, Selenium, Tkinter, Google Sheets
- **Hardware:** Raspberry Pi Pico 2, WCH CH32V307 / CH32V305, Arduino, RP2040
- **Web:** Vanilla JavaScript, WebSerial, HTML/CSS
- **Tools:** Arduino IDE, MounRiver Studio, gdb/openocd, oscilloscope,
  magnifier and coffee

## 📬 Contact

- GitHub: [MrStuani](https://github.com/MrStuani)
