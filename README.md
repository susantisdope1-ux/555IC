# STAR 555

**A four-point star PCB powered by a single LM555 timer.**

No microcontroller. No programming. Just a classic timer IC, a few passive components, and a custom PCB designed in EasyEDA Pro.

---

## Project Images

### Schematic

<p align="center">
  <img width="1235" height="772" alt="image" src="https://github.com/user-attachments/assets/5ac45b34-b641-4e34-83a9-79213ab659c9" />

</p>

---

### PCB Layout (2D)

<p align="center">
 <img width="698" height="673" alt="image" src="https://github.com/user-attachments/assets/9e6b5d73-cc12-4d04-a740-04fad1cb86a9" />

</p>

---

### PCB 3D View

<p align="center">
 <img width="732" height="617" alt="image" src="https://github.com/user-attachments/assets/4a79e44d-c4b5-476a-8fe2-f9c381704761" />

</p>

---

# Reason For Designing It

I just wanted to make something that would be unique in terms of shape, yet simple enough and not your typical rectangle-shaped PCB. The LM555 timer is one of the most used timer ICs ever produced, and a good choice to get familiar with designing the PCB without coding.

Designing this PCB allowed me to practice the entire process of making PCB designs including schematic, routing, making my own PCB outline, and generating the production-ready files.

---

# Highlights

- Four-pointed star PCB
- 10 LEDs
- Uses LM555 timer
- 5V power supply
- Hand solderable
- Unique Silkscreen
- Designed using EasyEDA Pro

---

# Specifications

| Item | Value |
|------|-------|
| Supply Voltage | 5V DC |
| Timer IC | LM555CMX |
| LEDs | 10 × 5 mm |
| Input | 2-Pin Terminal Block |
| Design Software | EasyEDA Pro |
| PCB Shape | Four-point Star |

---

# How It Works

The LM555 is set up in an astable oscillator mode. The output is connected to ten LEDs using separate 470Ω resistors for each LED.

Using the given timing elements, the output frequency is sufficient for the LEDs to seem continuously lit. Using a larger timing capacitor (such as 10µF) will reduce the frequency and cause the LEDs to blink.

---

# Cost and Parts

| Item | Qty | LCSC Part | Unit Cost (USD) | Total Cost (USD) | Link |
|------|----:|-----------|----------------:|-----------------:|------|
| LM555CMX Timer IC | 1 | C7960 | $0.0413 | $0.0413 | https://www.lcsc.com/product-detail/C7960.html |
| 100nF Capacitor (0402) | 1 | C60474 | $0.0008 | $0.0008 | https://www.lcsc.com/product-detail/C60474.html |
| 470Ω Resistor (0603) | 10 | C2907172 | $0.0003 | $0.0030 | https://www.lcsc.com/product-detail/C2907172.html |
| 2-Pin Terminal Block | 1 | C5157827 | $0.3590 | $0.3590 | https://www.lcsc.com/product-detail/C5157827.html |
| 100nF Capacitor (C2) | 1 | Not Assigned | Placeholder | Placeholder | — |
| 1kΩ Resistor | 1 | Not Assigned | — | — | — |
| 5kΩ Resistor | 1 | Not Assigned | — | — | — |
| 5mm LEDs | 10 | Not Assigned | Placeholder | Placeholder | — |
| **Estimated Component Cost** | | | | **≈ $8.99** | |
| PCB (JLCPCB) | 1 | — | — | $12.00 | |
| FedEx Express Shipping | 1 | — | — | $27.10 | |
| **PCB + Shipping** | | | | **$39.10** | |
| **Estimated Total Project Cost** | | | | **≈ $48.09** *(before customs and taxes)* | |

> **Note:** Some parts in the exported BOM do not have LCSC part numbers, so placeholder prices are used. Your final cost may vary depending on the selected components and shipping destination.

---

# Assembly

1. Solder the SMD resistors and capacitors.
2. Solder the LM555 Timer IC.
3. Solder the terminal blocks.
4. Insert all the 10 LEDs keeping in mind the polarity.
5. Apply regulated 5V power to the circuit.
6. Test your board.

---

#### 

# Tools Required

- EasyEDA Pro
- JLCPCB
- LCSC

---

#### 

# Credits

Designed by **Sugam Pathak**.
