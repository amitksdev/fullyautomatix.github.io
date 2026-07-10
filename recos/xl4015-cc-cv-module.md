---
layout: project
title: "XL4015 CC/CV Power Supply Module | FullyAutomatix"
description: "Why the XL4015 is the best budget constant-current/constant-voltage power supply module"
---

{:.kicker}
Recommended Gear

# XL4015 CC/CV Power Supply Module

{:.lead}
A buck converter module with adjustable constant-current and constant-voltage modes — perfect for battery charging, LED drivers, and bench power supply projects.

![XL4015 CC/CV Module]({{ '/images/recos/xl4015-module.jpg' | relative_url }}){:.hero-image}

## Why It's Great

The XL4015 module punches way above its weight class. Here's why it's a staple in my parts bin:

- **Constant Current & Constant Voltage** — Both CC and CV modes in one module. Set current limit for LED drivers or charge controllers, voltage for powering projects.
- **High Current Output** — Up to 5A continuous output. Enough for most hobby projects and prototype power supplies.
- **Wide Input Range** — Accepts 4-38V input, outputs 1.25-36V. Great for powering projects from 12V or 24V sources.
- **Efficient Switching Regulator** — 96% efficiency at optimal load. Runs cool, wastes minimal power.
- **Onboard Trimpots** — Adjust voltage and current limit with onboard potentiometers. No external components needed.
- **Overcurrent Protection** — Current limiting kicks in automatically. Protects your circuits during testing.
- **LED Indicators** — Shows CC/CV mode status. Know what's happening at a glance.
- **Incredibly Affordable** — Around $1-2 USD per module. Buy a handful for different projects.

## Technical Specs

| Feature | Specification |
|---------|--------------|
| IC | XL4015 buck converter |
| Input Voltage | 4-38V DC |
| Output Voltage | 1.25-36V DC (adjustable) |
| Output Current | 5A max (with heatsink) |
| Switching Frequency | 180 kHz |
| Efficiency | Up to 96% |
| Operating Temperature | -40°C to +85°C |
| Dimensions | ~54mm × 34mm × 14mm |
| Typical Cost | USD 1-2 |

## Perfect For

**Power Supplies:**
- DIY bench power supply modules
- Adjustable voltage regulators
- Battery charging circuits
- Voltage/current-limited test supplies

**LED Drivers:**
- High-power LED projects (1W-3W LEDs)
- LED strip drivers
- Constant-current LED arrays
- Grow light controllers

**Battery Charging:**
- Li-Ion/LiPo chargers (with proper BMS)
- Lead-acid battery maintainers
- NiMH/NiCd charge controllers
- Solar charge controllers

**Project Power:**
- Powering 12V projects from 24V sources
- Regulating voltage for Arduino/ESP projects
- Current-limited supplies for testing
- Mobile robot power supplies

## How to Use

**Basic Setup:**
1. Connect input voltage (4-38V)
2. Adjust output voltage with CV potentiometer
3. Set current limit with CC potentiometer (use short circuit or ammeter)
4. Connect load
5. Module automatically switches between CC and CV modes

**For Battery Charging:**
- Set CV to battery max voltage (e.g., 4.2V for Li-Ion)
- Set CC to desired charge current (typically 0.5-1C)
- Add BMS for safe charging (XL4015 alone is NOT a complete charger)

**For LED Driving:**
- Set CC to LED forward current
- Set CV slightly above LED forward voltage
- Add heatsinking for high-current operation

## Important Notes

- **Heatsinking required** for currents above 3A
- **Not a complete battery charger** — needs additional protection circuitry
- **Buck converter only** — output voltage must be lower than input
- **Use shielded inductors** — unshielded can cause EMI

## Where to Buy

Available from:
- AliExpress (best prices, bulk options)
- eBay (various sellers)
- Amazon (faster shipping)
- Banggood

**Pro tip:** Buy a 5-10 pack. They're so cheap and versatile, you'll use them in multiple projects.

---

*Part of the FullyAutomatix recommended tools collection — gear that actually gets used in the workshop.*
