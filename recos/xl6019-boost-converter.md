---
layout: project
title: "XL6019 Boost Converter Module | FullyAutomatix"
description: "Why the XL6019 is the go-to boost converter for stepping up voltage in hobby projects"
---

{:.kicker}
Recommended Gear

# XL6019 Boost Converter Module

{:.lead}
A high-efficiency boost converter module for stepping up voltage — perfect for running 12V devices from batteries, solar panels, or USB power banks.

![XL6019 Boost Converter]({{ '/images/recos/xl6019-module.jpg' | relative_url }}){:.hero-image}

## Why It's So Good

The XL6019 is my go-to boost converter module. Here's what makes it stand out:

- **Wide Voltage Boost Range** — Step up from 3-32V input to 5-35V output. Run 12V devices from a 5V USB power bank or boost 12V to 19V for a laptop.
- **High Current Capacity** — Up to 4A continuous output (with proper cooling). Enough for most hobby electronics and small motors.
- **Adjustable Output** — Onboard potentiometer lets you dial in the exact voltage you need. No external components required.
- **High Efficiency** — 94% typical efficiency. Minimal power loss means longer battery runtime and less heat.
- **Overcurrent Protection** — Built-in current limiting protects against shorts and overload conditions.
- **Compact PCB** — Small form factor fits inside project enclosures easily.
- **LED Indicator** — Power LED confirms operation at a glance.
- **Rock-Solid Reliable** — XL6019 IC is proven in thousands of projects. Very few failures in the field.
- **Budget-Friendly** — Around $1-2 USD. Incredible value for the capability.

## Technical Specs

| Feature | Specification |
|---------|--------------|
| IC | XL6019 boost converter |
| Input Voltage | 3-32V DC |
| Output Voltage | 5-35V DC (adjustable) |
| Output Current | 4A max (with heatsink) |
| Switching Frequency | 400 kHz |
| Efficiency | Up to 94% |
| Operating Temperature | -40°C to +85°C |
| Dimensions | ~43mm × 21mm × 14mm |
| Typical Cost | USD 1-2 |

## Perfect For

**Battery-Powered Projects:**
- Running 12V devices from 9V batteries
- Boosting USB 5V to 12V for fans, pumps, or LED strips
- Solar panel voltage regulation
- Portable power supply projects

**Voltage Conversion:**
- 5V to 12V conversion for automotive accessories
- 12V to 19V for laptop power from car battery
- Stepping up LiPo battery voltage (3.7V → 5V or 12V)
- Multi-voltage power distribution systems

**Portable Devices:**
- USB-powered 12V devices
- Battery-powered LED lighting
- Mobile robot power management
- Field equipment power adapters

**Arduino/ESP Projects:**
- Powering 12V peripherals (relays, motors, solenoids)
- Step-up for Neopixel/WS2812 LED strips
- Sensor modules requiring higher voltage
- Multi-rail power supplies

## How to Use

**Basic Setup:**
1. Connect input voltage source (3-32V)
2. Measure output voltage with multimeter
3. Adjust potentiometer until desired output voltage is reached
4. Connect load (ensure current draw is within spec)
5. Add heatsink if running >2A continuously

**Important:**
- Input voltage must be **lower** than desired output (boost only, not buck)
- Use thick wires for high-current applications (16-18 AWG)
- Add input/output capacitors for noisy loads (100µF-1000µF)
- Don't run at max current continuously without heatsinking

## Common Applications

**5V USB to 12V:**
- Input: 5V USB power bank (ensure it can supply 2A+)
- Output: Set to 12V
- Use case: Portable 12V fans, LED strips, small pumps

**LiPo (3.7V) to 5V:**
- Input: Single-cell LiPo battery
- Output: Set to 5V
- Use case: Powering Arduino, ESP8266, sensors from LiPo

**12V to 19V:**
- Input: 12V car battery or power supply
- Output: Set to 19V
- Use case: Running laptop or monitor from car/RV battery

## Pro Tips

- **Heatsinking:** The XL6019 IC can get hot at high currents. Add a small heatsink or thermal pad for currents above 2A.
- **Input filtering:** Add a 100µF capacitor across the input for stable operation with noisy power sources.
- **Output filtering:** Add a 220µF capacitor at the output for loads with spiky current draw (motors, relays, LEDs).
- **Voltage adjustment:** Use a multimeter, not just the onboard LED, to set precise output voltage.
- **Current limit:** Calculate input current = (output voltage × output current) / (input voltage × efficiency). Don't exceed your source capability.

## Where to Buy

Available from:
- AliExpress (best prices, bulk packs)
- eBay (various sellers)
- Amazon (faster shipping, slightly higher cost)
- Banggood

**Pro tip:** Buy a multi-pack (5-10 units). Great to have on hand for quick power supply prototypes.

---

*Part of the FullyAutomatix recommended tools collection — gear that actually gets used in the workshop.*
