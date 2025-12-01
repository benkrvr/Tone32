# Tone32
The Universal Music Microcontroller: For pedals, synths, and beyond!

---

## Project Description
Tone32 is a purpose-built microcontroller platform for all musical applications: from guitar pedals to Eurorack modules, samplers, and MIDI controllers.  
It’s designed to be:

- Reliable and low-latency
- Audio-first with clean analog paths
- Expandable for DIY and professional setups
- Arduino IDE compatible for easy programming

Whether you’re building effects, synthesizers, or experimental instruments, Tone32 provides the hardware foundation and software framework you need.

---

## Features

### Core
- ESP32-S3 dual-core microcontroller
- Native USB (MIDI, audio, serial)
- Arduino IDE compatible

### Audio
- High-quality stereo I2S codec (24-bit, up to 96kHz)
- Optional preamp for instrument-level signals
- Low-noise regulators for clean analog audio

### MIDI & USB
- 5-pin DIN MIDI in/out
- USB-MIDI support

### Expansion & UI
- I²C, SPI, UART headers
- OLED / LCD support
- Buttons, encoders, and LEDs for direct control
- MicroSD slot for samples, presets, and firmware storage

### Power
- 9V pedalboard friendly
- Reverse polarity protection and low-noise regulation

### Software / Firmware
- Built-in DSP utilities: filters, delay, reverb, LFO, envelope followers
- Ready-to-use examples: pedals, synth modules, MIDI controllers
- OTA updates and web configuration support

---

## Philosophy / Purpose
Tone32 is designed to be **open for learning and experimentation**, while **protecting the commercial integrity** of the platform.  
My goal is to create a community around building musical appliances without risking instant mass-produced clones undercutting the project.

I encourage hobbyists, educators, and developers to:
- Learn from the design
- Modify it for personal or educational projects
- Contribute firmware or examples

---

## Licensing

### Hardware (PCB / Schematics / CAD)
- Licensed under **CC-BY-NC 4.0**
- You may use, modify, and experiment with the design for personal, educational, or research purposes
- Commercial use requires a paid license. Contact: ben@krvr.nl

---

## Quick Start / Examples
1. Install Arduino IDE
2. Add Tone32 board package (instructions TBD)
3. Connect your Tone32 via USB-C
4. Start hacking your own musical appliance!

---

## Community / Contribution
- Fork the repo for experimentation
- Submit firmware examples or fixes via pull requests
- Share your mods for non-commercial projects
- 
---

## Branding & Attribution
If you use Tone32 in a project, please credit the original hardware design:  
“Hardware based on Tone32 https://github.com/benkrvr/Tone32”

Do not use the Tone32 logo or name in any commercial product without permission.
