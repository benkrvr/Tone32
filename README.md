# Tone32
The Universal Music Microcontroller: For pedals, synths, and beyond!

---

## Project Description
Tone32 is a purpose-built microcontroller platform for all musical applications: from guitar pedals to synth modules, samplers, and MIDI controllers.

It’s designed to be:

- Reliable and low-latency
- Audio-aware with a dedicated ADC/DAC for simple input/output
- Expandable for DIY experimentation
- Arduino IDE compatible for easy programming

This **v0.1** board provides a solid foundation: a microcontroller with headers and a single dedicated audio input/output, giving you a **taste of musical interactivity** without overcomplicating the design.

---

## Features (v0.1)

### Core
- ESP32-S3 dual-core microcontroller
- Arduino IDE compatible
- USB-C for programming and serial interface

### Audio
- **Dedicated AUD1 input**: 16-bit ADC for line/CV/instrument signals
- **Dedicated AUD1 output**: 12–16 bit DAC (via simple I²S codec)
- Minimal passive components for clean analog path

### Expansion & UI
- General-purpose GPIO header (2×12 pins)
  - Some pins pre-labeled for I²C, SPI, and ADC/DAC signals
- Easy connection for buttons, LEDs, or encoders

### Power
- 3.3 V regulated rail from USB or external supply
- Common ground for audio and peripherals

### Software / Firmware
- Fully Arduino IDE compatible
- Examples included for reading AUD1_IN and outputting audio to AUD1_OUT
- Placeholder for DSP or audio processing libraries (to be added in later iterations)

---

## Philosophy / Purpose
Tone32 is designed to be **open for learning and experimentation**, while **protecting the commercial integrity** of the platform.

I encourage hobbyists, educators, and developers to:

- Learn from the design
- Modify it for personal or educational projects
- Contribute firmware examples

This v0.1 is a **starting point**: it demonstrates audio-capable ESP32 hardware while leaving room for expansion in future versions.

---

## Licensing

### Hardware (PCB / Schematics / CAD)
- Licensed under **CC-BY-NC 4.0**
- You may use, modify, and experiment with the design for personal, educational, or research purposes
- Commercial use requires a paid license. Contact: ben@krvr.nl

### Firmware / Software
- MIT license (Arduino examples and code snippets)

---

## Quick Start / Examples
1. Install Arduino IDE
2. Add Tone32 board package (instructions TBD)
3. Connect your Tone32 via USB-C
4. Use example sketches to read AUD1_IN or output audio via AUD1_OUT

---

## Community / Contribution
- Fork the repo for experimentation
- Submit firmware examples or fixes via pull requests
- Share mods for **non-commercial projects**

---

## Branding & Attribution
If you use Tone32 in a project, please credit the original hardware design:

> “Hardware based on Tone32 https://github.com/benkrvr/Tone32 ”

Do **not** use the Tone32 logo or name in any commercial product without permission.
