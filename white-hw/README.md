Components found on the white Panda.

**TOP side (when you openup your Panda):**
- ESP-12 (wifi replaced by GPS module in grey version)
- RGB LED
- ST1S40 3A DC step-down regulator VFQFPN package (components and its placement is exactly as manufacturer note says)
  https://www.st.com/resource/en/datasheet/st1s40.pdf
- some passive components like diodes, resistors, capacitors

**BOTTOM invisible side:**

- U1 - STM32F413 (main microcontroller with 3xCAN ability)
- U6,7,8 - 3 times NXP TJA1042 (https://www.nxp.com/docs/en/data-sheet/TJA1042.pdf) in HVSON8 package
- U2 - 2549Q - AutomotiveUSB ChargingPort Controller (http://www.ti.com.cn/cn/lit/ds/slusce3/slusce3.pdf)
  16-PinQFN(3x3 mm) Package
- Y1 - 16MHz oscilator AH7P (SMD version)
- U10 - NCP5661 fixed 3.3V DFN6 package https://www.onsemi.com/pub/Collateral/NCP5661-D.PDF
- U9 -  1 wire CAN (GM LAN) SOIC-8 - https://www.onsemi.com/pub/Collateral/NCV7356-D.PDF
- U3 - 2x LIN interface NXP TJA1022 HVSON14 package https://www.nxp.com/docs/en/data-sheet/TJA1022.pdf
- Q1 - looks like transistor (https://www.diodes.com/assets/Datasheets/ds30330.pdf ?) N29 T1 markings on it
- everything else are passives like for TOP side

**Pictures:**

![Panda top](https://raw.githubusercontent.com/martiinezz/panda/master/white-hw/panda-t.jpg)

![Panda bottom](https://raw.githubusercontent.com/martiinezz/panda/master/white-hw/panda-b.jpg)

