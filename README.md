# 🔌 PlugJuice: IoT Smart Plug for Energy Monitoring

**PlugJuice** is a smart plug that **tracks the energy used by connected devices in real time**, protects them from **voltage spikes**, and can be **controlled remotely**. A dashboard shows each device's consumption so users can understand and cut their energy use.

Freshman engineering project (ISS196, 2024) at MedTech – South Mediterranean University, built by a team of 5.

## What we built

- **Smart plug hardware:** current and voltage sensing, relay switching, a voltage regulator and current-limiting protection against spikes, all wired and integrated on a microcontroller
- **Remote control:** switch connected devices on and off from the app
- **Monitoring dashboard** (JavaScript & Python): real-time and historical consumption per device, grouped by category (appliances, screens, air conditioning…)
- **Automation scenarios:** for example a "sleep mode" that switches off all appliances and screens at once
- **3D-printed enclosure** designed in **SolidWorks**

## Components

| Component | Purpose |
|---|---|
| Microcontroller | Measurement, control and automation logic |
| Current & voltage sensors | Real-time energy consumption |
| Wi-Fi / Bluetooth module | Sends data to the dashboard and receives commands |
| Relay module | Switches the connected device on/off |
| Voltage regulator + current-limiting resistor | Power regulation and spike protection |
| Power indicator LED | Status feedback |

## Challenges

1. **Energy efficiency:** the plug itself must not become a significant consumer.
2. **Firmware:** choosing a microcontroller with enough resources and programming it.
3. **Sensors & regulation:** calibrating sensors for accurate readings and following good design practice for the regulator and current sensing.

## Tech stack

IoT · Microcontroller · Sensors · JavaScript · Python · SolidWorks

## Slides & reports

- 📊 [Presentation slides](docs/PLUG%20JUICE.pdf)
- 📄 [Original project proposal](docs/project-proposal.pdf) ([.docx](docs/project-proposal.docx))

## Team

Amine Ben Nasrallah · Azza Guidara · Adem Arroum · Eya Khangui · Ghassen Siala
