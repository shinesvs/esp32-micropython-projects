# ESP32 MicroPython Projects – Morse Code Blinker

This repository contains my ESP32 MicroPython experiments and mini-projects.  
I'm starting it with a simple **Morse Code LED blinker**, and I’ll continue adding more ESP32 + MicroPython projects here as I explore and learn.

---

## 📌 Current Project: Morse Code LED Blinker

This is a small learning project where I used an **ESP32-WROOM (Adafruit HUZZAH32)** with **MicroPython** to translate text into **Morse code LED pulses**.

Text typed into the MicroPython REPL is converted to Morse code, and the onboard LED blinks the corresponding dots and dashes.

---

## Features

- Runs on ESP32 with MicroPython  
- Reads text input from the MicroPython REPL  
- Converts letters (`a–z`) and spaces into Morse code  
- Implements standard Morse timing (dot, dash, letter gap, word gap)  
- Uses the onboard LED for visual output  

---

## Hardware

- ESP32-WROOM module on:
  - **Adafruit HUZZAH32** (tested)
  - Should work on other ESP32 dev boards with small pin changes  
- Onboard LED on GPIO 13 (adjust in code if needed)

---

## Software

- [MicroPython](https://micropython.org/) for ESP32  
- [Thonny IDE](https://thonny.org/) for flashing firmware and using the REPL  

---

## Getting Started

### 1. Flash MicroPython to the ESP32

1. Connect ESP32 to your computer  
2. In Thonny: `Tools → Options → Interpreter`  
3. Select **MicroPython (ESP32)** + correct port  
4. Use **Install or update MicroPython** if available  

---

### 2. Upload the project

1. Open `main.py` in Thonny  
2. Go to `File → Save as...`  
3. Select **MicroPython device**  
4. Save as `main.py`  

Reset the board — the program will start automatically.

---

## Usage

1. Open the Thonny **Shell** (REPL)  
2. When prompted:

   ```text
   Message: hello
