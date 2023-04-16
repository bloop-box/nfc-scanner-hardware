# NFC2USB

[![CI](https://github.com/bloop-box/nfc-scanner-hardware/actions/workflows/ci.yml/badge.svg)](https://github.com/bloop-box/nfc-scanner-hardware/actions/workflows/ci.yml)


![3D Render](https://bloop-box.github.io/nfc-scanner-hardware/3D/NFC2USB-3D_top.png)

[Documentation](https://bloop-box.github.io/nfc-scanner-hardware)


Connect an RC522 based NFC-Reader to your computer using USB

The project is based around a Raspberry Pi [RP2040](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html) microcontroller. It would have been possible to solve this with a much simpler controller but availability and pricing at the time of development as well as ease of use made the RP2040 with built in USB the best choice. 

The board is designed using KiCAD 6 with production and assembly by JLCPCB in mind. All parts are selected to be available from JLCPCB at the time of writing and as many parts as possible are used from their basic library.