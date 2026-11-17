# 🔌 Smart Plug: Energy Monitoring & Automation

Project proposal for a **smart plug** that measures the energy used by connected devices in real time, reports it to a database, and lets users monitor and control their consumption from a simple dashboard.

Freshman engineering project (ISS196) at MedTech – South Mediterranean University, by a team of 5. Alongside it, the course was an introduction to **Python** and **Raspberry Pi GPIO** programming.

## Objectives

- Let users **monitor and control** the energy consumption of their devices
- Protect devices with a **voltage regulator** and a **current-limiting resistor**
- Provide a **dashboard** with consumption curves grouped by category (appliances, screens, air conditioning…)
- Support **automation scenarios**, e.g. a "sleep mode" that switches off all appliances and screens

## Planned design

| Component | Purpose |
|---|---|
| Microcontroller | Runs the measurement and automation logic |
| Current & voltage sensors | Measure real-time energy consumption |
| Wi-Fi / Bluetooth module | Sends data to the database and app |
| Relay module | Switches the connected device on/off |
| Voltage regulator + current-limiting resistor | Power regulation and protection |
| Power indicator LED | Status feedback |
| Web / mobile app | Dashboard and automation scenarios |

## Target users

Households and energy-conscious users, including home-automation enthusiasts.

## Challenges identified

1. **Energy efficiency:** the plug itself must not become a significant consumer.
2. **Firmware:** choosing a microcontroller with enough resources and programming it in Arduino.
3. **Sensors & regulation:** calibrating sensors for accuracy and following good design practice for the regulator and current sensing.

📄 [Full project proposal](docs/project-proposal.pdf)

## Team

Amine Ben Nasrallah · Azza Guidara · Adem Arroum · Eya Khangui · Ghassen Siala
