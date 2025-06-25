# UART Communication with PIC16F877A

This project demonstrates simple **UART transmission** using the **PIC16F877A** microcontroller. A single character (`'A'`) is repeatedly sent over the UART TX pin at 9600 bps using polling mode.

## 👨‍💻 Author
**Edvin Jose Vakaparamban**  
📅 Created on: April 25, 2025

---

## 🧰 Hardware Requirements

- **PIC16F877A** Microcontroller
- USB-to-Serial Converter (e.g., FT232, CH340)
- Terminal software (e.g., PuTTY, Tera Term)
- Breadboard, wires, 16 MHz crystal

---

## 🔧 Description

- UART is initialized in asynchronous mode.
- Baud rate set to **9600 bps** using SPBRG = 104 and BRGH = 1.
- The program transmits character `'A'` every 250 ms.
- Transmission occurs using polling (`while(!TRMT)`).

---

## ⚙️ Configuration

| Parameter       | Value       |
|------------------|-------------|
| Baud Rate        | 9600        |
| TX Pin           | RC6         |
| RX Pin           | RC7 (unused)|
| Mode             | Asynchronous|
| Clock Frequency  | 16 MHz      |

---

