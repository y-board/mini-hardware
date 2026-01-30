# Y-Board Mini

A compact PCB design featuring an ATTiny202 microcontroller with integrated peripherals including an RGB LED, buzzer, and button. The project is intended to help people learn out to solder.

## Parts List

| Category           | Part                     | Quantity | Link                                                                                                             | Notes                                      |
| ------------------ | ------------------------ | -------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| **Processor**      | ATTiny202-SSNR           | 1        | -                                                                                                                | **Sourced by JLC as part of PCB assembly** |
| **Buzzer**         | CEM-1201S                | 1        | [DigiKey Link](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/CEM-1201S/412413)        | Audio output                               |
| **LED**            | QBL8RGB60D0-2897         | 1        | [DigiKey Link](https://www.digikey.com/en/products/detail/qt-brightek-qtb/QBL8RGB60D0-2897/10441184)             | RGB LED                                    |
| **Button**         | 1825910-6                | 1        | [DigiKey Link](https://www.digikey.com/en/products/detail/te-connectivity-alcoswitch-switches/1825910-6/1632536) | Tactile switch                             |
| **Battery Holder** | Keystone Electronics 500 | 1        | [DigiKey Link](https://www.digikey.com/en/products/detail/keystone-electronics/500/151580)                       | Coin cell holder                           |
| **Battery**        | CR1225                   | 1        | [Amazon Link](https://www.amazon.com/dp/B085T38P28)                                                              | Coin cell battery                          |
| **Capacitor**      | 0.1 µF                   | 1        | -                                                                                                                | Decoupling capacitor                       |
| **Capacitor**      | 10 µF                    | 1        | -                                                                                                                | Power filtering                            |
| **Resistor**       | 220 Ω                    | 3        | -                                                                                                                | Current limiting                           |


## Project Files

- KiCad schematic and PCB layout files
- Gerber files for manufacturing
- 3D models for components
  - A jig for programming the ATTiny202
  - A jig for making soldering the board easier
- Production files (BOM, positions, netlist)
