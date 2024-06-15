# Bill of Materials

This page lists all parts and materials required to build the clock.

## 3D-printing

Everything can be printed in PLA.

## Electronics

First of all, you need the PCBs. Making them yourself could be quite a challenge since tha main board is a double sided design and the other two boards have a non-square outline which can be best CNC-milled or hand made with a router. Therefore I would recommend ordering them form a prototyping PCB service. I had them made at JLC PCB and the quality they arrived in is very convincing. Check out the [gerber files](gerber/readme.md).

The following table shows the required components. The datasheets show the exact pieces I used in my design and realization.

| Part/Material | Quantity | Notes |
|---------------|---------:|-------|
| Power supply | 1 | 5V DC regulated, with at least 3000 mA output current rating.<br>Micro USB connector |
| [WS2812b LED chip](datasheets/ws2812b.pdf) | 86 | |
| Micro USB connector | 1 | |
| Ceramic capacitor 1000uF, 16V, 0603 | 2 | |
| Resistor 330R, 5%, 0603 | 1 | |
| [ESP32-WROOM-32E 4MB](datasheets/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf) | 1 | See the [pinout](datasheets/esp32-pinout-chip-esp-wroom-32.png). |
| 0.22 mm<sup>2</sup> stranded wire | 58 | 4 distinct colors; quantity is in cm and is for each color separately. |
| M2 6mm screws | 4 | |
| M3 5mm screws | 2 | |
| M3 8mm countersunk head screws | 16 | |
| M3 8mm lens head screws | 22 | 12 are optional if you want to better fix the segments together |
| M3 nuts | 12 | optional if you want to better fix the segments together |

