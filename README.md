# Caeseura

**cae·sue·ra**
/siːˈzʊrə/

**noun**

1. a pause or break in the middle of a line of poetry, often used for emphasis or to create rhythm.
   - "Shall I compare thee to a summer's day? // Thou art more lovely and more temperate."*
2. a natural pause or interruption in speech or music.
   - "His sentence had a long caesura, as if he were searching for the right words."*
3. *(wordplay)* one who splits; something that divides or separates into two parts.

***etymology***

Altered spelling of *caesura*, intentionally adding **e** as wordplay, referencing the city of **Céüse** in France, the sword **Caesura** from *The Kingkiller Chronicle*, and the concept of splitting or dividing.

---

## Photos

| | |
|---|---|
| ![PCBs bare](photos/IMG_7707.jpeg) | ![Left PCB close-up](photos/IMG_7708.jpeg) |
| ![Right PCB](photos/IMG_7709.jpeg) | ![Hotswap sockets soldered](photos/IMG_7710.jpeg) |
| ![First switch test](photos/IMG_7711.jpeg) | ![Both halves with switches](photos/IMG_7715.jpeg) |
| ![Left half assembled](photos/IMG_7716.jpeg) | ![Right half assembled](photos/IMG_7717.jpeg) |
| ![Full board with keycaps outdoors](photos/IMG_7718.jpeg) | ![Finished build — front](photos/IMG_7722.jpeg) |
| ![Finished build — angle](photos/IMG_7723.jpeg) | ![Daily driver setup](photos/IMG_7724.jpeg) |
| ![Side profile](photos/IMG_7725.jpeg) | |

---

## Features

- **47 keys** — row-staggered layout with a traditional feel and a compact footprint
- **Split design** — two halves, place them wherever feels natural for your shoulders
- **MX & Choc compatible** — hotswap sockets support MX, Choc v1, and Choc v2 switches simultaneously; no resoldering needed to switch between them
- **Wireless** — powered by the [nice!nano v2](https://nicekeyboards.com/nice-nano/) and [ZMK firmware](https://zmk.dev/), completely cable-free between halves
- **Per-side batteries** — each half has its own JST PH 2-pin battery connector and SMD power switch; battery can be tucked under the PCB
- **SMD diodes** — SOD-123 footprint, one per key
- **Ergogen-designed PCB** — generated with [Ergogen](https://ergogen.xyz/) using the ceoloide footprint library; fully open source
- **3D printed case** — printed bottom, wall, and switch plate; STL/step files included in `cases/`
- **6 mounting holes per half** — M2 screws and standoffs for a solid, rattle-free build
- **Reset button** — through-hole, top accessible, no case disassembly needed
- **Open source** — PCB sources, case files, ZMK config, and Ergogen YAML all included

### Layout

The left half carries a standard row-stagger with modifier keys (Escape, Tab, Shift, Control, Super) sized at 1u–1.75u, plus a two-key thumb cluster. The right half mirrors the stagger with a seven-key top number row, standard alpha/symbol columns, a three-key arrow cluster, and a two-key thumb cluster.

---

## Bill of Materials (BOM)

This is the exact BOM used for the author's build. Total cost will vary depending on switch choice, shipping, and discounts.

| Item | Qty | Unit Price | Total | Link |
|---|---|---|---|---|
| nice!nano v2 | 2 | $25.00 | $50.00 | [Typeractive](https://typeractive.xyz/products/nice-nano) |
| Battery (PS3 controller replacement LiPo) | 1 | $15.49 | $15.49 | [Amazon](https://www.amazon.com/dp/B09726K2LC) |
| PCB (left + right) | 1 set | $27.00 | $27.00 | JLCPCB — new users get ~$6 off with global direct shipping |
| Switches (Choc) | 2 packs | $19.99 | $39.98 | [Amazon](https://www.amazon.com/dp/B0BLC9BKW8) |
| Silent Choc switches (Ambients) | 1 set | $66.00 | $66.00 | [Holykeebs](https://holykeebs.com/products/ambients-silent-choc-switches?variant=47849514860834) |
| Choc hotswap sockets (x10) | 5 packs | $1.50 | $7.50 | [Typeractive](https://typeractive.xyz/products/hotswap-sockets?variant=45742200324327) |
| MX hotswap sockets | 5 packs | $1.50 | $7.50 | [Typeractive](https://typeractive.xyz/products/hotswap-sockets?variant=45742200291559) |
| Reset switch (Panasonic EVQ-PUA02K) | 3 | $0.67 | $2.01 | [Digikey](https://www.digikey.com/en/products/detail/panasonic-electronic-components/EVQ-PUA02K/286334) |
| Power switch (SMD) | 2 packs | $1.50 | $3.00 | [Typeractive](https://typeractive.xyz/products/power-switch) |
| JST PH 2-pin battery connector | 2 | $0.10 | $0.20 | [Digikey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/S2B-PH-K-S/926626) |
| Keycaps | — | 3D printed | — | Print your own |
| SOD-123 diodes (1N4148W) | 50 | $0.0495 | $2.48 | [Digikey](https://www.digikey.com/en/products/detail/diotec-semiconductor/1N4148W/18833653) |
| Mill-Max 310 board sockets | 6 | $1.43 | $8.58 | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/310-47-112-41-001000/7364039) |
| Mill-Max 3320 pins | 65 | $0.0876 | $5.69 | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/3320-0-00-15-00-00-03-0/4147392) |
| Adhesive rubber feet | 1 pack | $6.99 | $6.99 | [Amazon](https://www.amazon.com/dp/B0DXH5D1FQ) |
| M2x6mm FHCS screws | 1 pack | $8.69 | $8.69 | [Amazon](https://www.amazon.com/dp/B01MYRN6A1) |
| M2x6mm Torx screws (alternative) | 1 pack | — | — | [Amazon](https://www.amazon.com/dp/B0F12R97BJ) |
| M2 heat-set inserts | 1 pack | $6.99 | $6.99 | [Amazon](https://www.amazon.com/dp/B0FJXLNMLM) |
| Metal rings (MagSafe compatibility) | 1 pack | $3.99 | $3.99 | [Amazon](https://www.amazon.com/dp/B0CY1ZB8YB) |

**Total keys: 47** (24 left + 23 right, including thumb clusters)

> **Note:** The battery used here is a PS3 controller replacement LiPo — affordable, the right shape, and fits neatly under the PCB. Always verify polarity before connecting.

---

## Build Guide

### Tools needed

- Soldering iron + solder (fine tip recommended for SMD work)
- Flux
- Tweezers
- Multimeter (optional but helpful for continuity testing)
- 3D printer or access to one (for case)
- M2 screwdriver

---

### Step 1 — Order the PCBs

Use the production files in `pcbs/leftsidev2_withSS.zip` and `pcbs/rightsidev2_withSS.zip`. Upload the appropriate zip to your PCB fab. Recommended settings:

- **Layers:** 2
- **Thickness:** 1.6mm
- **Finish:** HASL or ENIG
- **Color:** your choice

---

### Step 2 — Print the case

Print the files from the `cases/` folder. The case consists of a bottom plate, a wall, and a switch plate. Recommended print settings:

- **Material:** PLA or PETG
- **Layer height:** 0.2mm
- **Infill:** 20%+ for the walls
- **Supports:** may be needed for the wall piece depending on orientation

---

### Step 3 — Solder the SMD diodes

Solder one SOD-123 diode per switch position. Each diode is marked on the silkscreen — match the cathode stripe on the diode to the line on the footprint. The diodes are located 8mm below each switch position.

> **Tip:** Pre-tin one pad, place the diode, reflow, then solder the second pad.

---

### Step 4 — Solder the hotswap sockets

Install MX and/or Choc hotswap sockets depending on your switch preference. Both footprints are present on the PCB — you can populate both if you want to swap between switch types later, or just the ones you plan to use. Pre-tin one pad, hold the socket flush against the PCB, reflow, then solder the second pad.

---

### Step 5 — Solder the power switch and reset button

- **Power switch (SMD):** Solder the side-mount power switch. It connects `BAT_P` to `RAW`.
- **Reset switch (THT):** Insert the through-hole tactile switch from the top of the PCB and solder from the underside.

---

### Step 6 — Install the battery connector

Solder the JST PH 2-pin connector. Double-check polarity before connecting a battery — red to `+`, black to `GND`. The connector is positioned to allow the battery to sit under the PCB.

---

### Step 7 — Install the nice!nano

Socket the nice!nano using Mill-Max 315 sockets (strongly recommended) or solder it directly. The MCU sits face-up on the PCB. Pin 1 is marked on both the PCB silkscreen and the nice!nano.

---

### Step 8 — Flash ZMK firmware

1. Clone or fork the ZMK config from `zmk-config-caeseura/`
2. Set up ZMK following the [ZMK getting started guide](https://zmk.dev/docs/user-setup)
3. Put the nice!nano into bootloader mode by double-tapping the reset button — it will appear as a USB drive
4. Drag and drop the compiled `.uf2` file onto the drive
5. Repeat for the other half

---

### Step 9 — Test

Before assembling into the case, plug in the left half (the central/USB half) and test each key using a keyboard tester. Use tweezers to short each hotswap socket pair if switches aren't installed yet.

---

### Step 10 — Assemble the case

1. Insert the standoffs into the mounting holes on the PCB
2. Place the PCB into the case wall
3. Attach the bottom plate with M2 screws
4. Snap or screw the switch plate on top
5. Install switches into the hotswap sockets
6. Install keycaps
7. Connect the battery and flip the power switch

---

## Credits

### Designer

Built and designed by **[@theb0b12](https://github.com/theb0b12)**.

### Special Thanks

A **massive** shoutout to **[@stardustArc](https://github.com/stardustArc)** (Discord: `@fuzzytomatohead_`) — she essentially walked through the entire design and build process step by step. This keyboard would not exist without her help.

Big thanks to **[@zakwaykway](https://github.com/zakwaykway)** for his knowledge about switches and switch footprints — invaluable when figuring out the dual MX/Choc hotswap setup.

Shoutout to the **[Ergogen Discord](https://discord.gg/ergogen)** and the **[ZMK Discord](https://zmk.dev/community)** communities — the collective knowledge in both servers made this project possible.

Thanks to **[@genteure](https://github.com/genteure)** for his help with the board shield and his excellent tool **[ZMK Shield Wizard](https://shield-wizard.genteure.workers.dev/)**, which makes setting up custom ZMK shields dramatically easier.

### Tools & Libraries

- **[Ergogen](https://ergogen.xyz/)** — PCB and case generation
- **[ceoloide footprint library](https://github.com/ceoloide/ergogen-footprints)** — KiCad footprints used for all components
- **[ZMK Firmware](https://zmk.dev/)** — wireless keyboard firmware
- **[nice!nano](https://nicekeyboards.com/nice-nano/)** — wireless MCU
- **[ZMK Shield Wizard](https://shield-wizard.genteure.workers.dev/)** — board shield generation by @genteure
- **[Keymap Layout Tools](https://nickcoutsos.github.io/keymap-layout-tools/)** — layout visualization and editing
- **[Keymap Editor](https://nickcoutsos.github.io/keymap-editor/)** — visual ZMK keymap editor by @nickcoutsos

---

## License

This project is open source. PCB design files, case files, and ZMK config are free to use, modify, and build from. If you make changes and share them, a link back here would be appreciated.