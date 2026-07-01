# Caeseura

**cae·sue·ra**
/siːˈzʊrə/

**noun**

1. in modern prosody : a usually rhetorical break in the flow of sound in the middle of a line of verse
2. break, interruption
   > "a *caesura* between the movie and its sequel"
3. a pause marking a rhythmic point of division in a melody

[credit](https://www.merriam-webster.com/dictionary/caesura)

***etymology***

Altered spelling of *caesura*, intentionally adding the **e** as wordplay, referencing the spelling of the city of **Céüse** in France, a very cool sport climbing destination and host to some of the hardest routes in the world. The sword **Caesura** from *The Kingkiller Chronicle*, great book btw. And the concept of splitting or dividing (get it, split keebs).

---

## Photos

| <img src="photos/IMG_7716.jpeg" width="550"> | <img src="photos/IMG_7717.jpeg" width="550"> |
| :------------------------------------------: | :------------------------------------------: |
| <img src="photos/IMG_7718.jpeg" width="550"> | <img src="photos/IMG_7725.jpeg" width="550"> |

---

## Builds

<p float="left">
  <img src="photos/DSC_6707.JPG" width="1005">
  <div align="center">
    <img src="photos/DSC_6725.JPG" width="400">
  </div>
</p>

Lu's Build, with a custom case and nice Asymplex/3D-printed Subliminal Contraction keycaps

---

## Features

- **47 keys**
- **Row Staggered**
- **Split design**
- **MX & Choc compatible** — hotswap sockets, choc v1 and v2 (if you snip the extra pin)
- **Wireless** — powered by the [nice!nano v2](https://nicekeyboards.com/nice-nano/) and [ZMK firmware](https://zmk.dev/)
- **Open source** — PCB gerbers + kicad files, case files, ZMK config, and Ergogen YAML

---

## Bill of Materials (BOM)

These are the things from my build. In hindsight I would've changed some things, use it with a couple more than a few grains of salt. Total cost will vary depending on switch choice, shipping, and discounts.

| Item                                 | Qty     | Unit Price | Total   | Link                                                                                                                |
| ------------------------------------ | ------- | ---------- | ------- | ------------------------------------------------------------------------------------------------------------------- |
| nice!nano v2                         | 2       | $25.00     | $50.00  | [Typeractive](https://typeractive.xyz/products/nice-nano)                                                           |
| Batteries                            | 1 set   | $15.49     | $15.49  | [Amazon](https://www.amazon.com/dp/B09726K2LC)                                                                      |
| PCB (left + right)                   | 1 set   | $27.00     | $27.00  | JLCPCB                                                                                                              |
| Switches (Choc)                      | ~47     | -          | -       | personal choice                                                                                                     |
| Choc hotswap sockets (x10)           | 5 packs | $1.50      | $7.50   | [Typeractive](https://typeractive.xyz/products/hotswap-sockets?variant=45742200324327)                              |
| MX hotswap sockets                   | 5 packs | $1.50      | $7.50   | [Typeractive](https://typeractive.xyz/products/hotswap-sockets?variant=45742200291559)                              |
| Reset switch (Panasonic EVQ-PUA02K)  | 3       | $0.67      | $2.01   | [Digikey](https://www.digikey.com/en/products/detail/panasonic-electronic-components/EVQ-PUA02K/286334)             |
| Power switch (SMD)                   | 2 packs | $1.50      | $3.00   | [Typeractive](https://typeractive.xyz/products/power-switch)                                                        |
| JST PH 2-pin battery connector       | 2       | $0.10      | $0.20   | [Digikey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/S2B-PH-K-S/926626)                       |
| Keycaps                              | ~47     | -          | -       | personal choice                                                                                                     |
| SOD-123 diodes (1N4148W)             | 50      | $0.0495    | $2.48   | [Digikey](https://www.digikey.com/en/products/detail/diotec-semiconductor/1N4148W/18833653)                         |
| Mill-Max 310 board sockets           | 6       | $1.43      | $8.58   | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/310-47-112-41-001000/7364039)      |
| Mill-Max 3320 pins                   | 65      | $0.0876    | $5.69   | [Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/3320-0-00-15-00-00-03-0/4147392)   |
| Adhesive rubber feet                 | 1 pack  | $6.99      | $6.99   | [Amazon](https://www.amazon.com/dp/B0DXH5D1FQ)                                                                      |
| M2x6mm FHCS screws                   | 1 pack  | $8.69      | $8.69   | [Amazon](https://www.amazon.com/dp/B01MYRN6A1)                                                                      |
| M2 heat-set inserts                  | 1 pack  | $6.99      | $6.99   | [Amazon](https://www.amazon.com/dp/B0FJXLNMLM)                                                                      |

---

## Build Guide

WIP

---

## Credits

### Designer

Built and designed by **[@theb0b12](https://github.com/theb0b12)**.

### Special Thanks

A massive shout-out to **[@stardustArc](https://github.com/stardustArc)** — she essentially walked me through the entire design and build process step by step. This keyboard would not exist without her help.

Big thanks to **[@zakwaykway](https://github.com/zakwaykway)** for his knowledge about switches and switch footprints, invaluable when figuring out the dual MX/Choc hotswap setup.

Shout-out to the **[Ergogen Discord](https://discord.com/invite/DbCfZfZ)** and the **[ZMK Discord](https://discord.com/invite/sycytVQ)** communities — the collective knowledge in both servers made this project possible.

Thanks to **[@genteure](https://github.com/genteure)** for his help with the board shield and his excellent tool **[ZMK Shield Wizard](https://shield-wizard.genteure.workers.dev/)**, which makes setting up custom ZMK shields dramatically easier.

### Tools & Stuff

- **[Ergogen](https://ergogen.xyz/)**
- **[ceoloide footprint library](https://github.com/ceoloide/ergogen-footprints)**
- **[ZMK Firmware](https://zmk.dev/)**
- **[nice!nano](https://nicekeyboards.com/nice-nano/)**
- **[ZMK Shield Wizard](https://shield-wizard.genteure.workers.dev/)**
- **[Keymap Layout Tools](https://nickcoutsos.github.io/keymap-layout-tools/)**
- **[Keymap Editor](https://nickcoutsos.github.io/keymap-editor/)**

---

## License

This project is open source with the MIT license. PCB design files, case files, and ZMK config are free to use, modify, and build from. If you make changes and share them, a link back here would be appreciated.