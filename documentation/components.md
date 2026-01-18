# Component List - miniMadre PCB

This document lists the components identified in the `v1.sch` and `v1.brd` files of the `miniMadre` project.

## Integrated Circuits (ICs)

| Designator | Part Name | Description | Manufacturer | Datasheet |
| :--- | :--- | :--- | :--- | :--- |
| **U1** | TPS552892RYQR | 36-V, 8-A Buck-Boost Converter | Texas Instruments | [TPS552892 Datasheet](https://www.ti.com/product/TPS552892) |
| **NA** | ESP32-WROOM-32 S3 | Wi-Fi + BT + BLE MCU Module | Espressif Systems |
| **U4** | BQ24075RGTT | 1.5-A USB-Friendly Li-Ion Battery Charger | Texas Instruments | [BQ24075 Datasheet](https://www.ti.com/product/BQ24075) |
| **U6** | BQ27441DRZT | System-Side Impedance Track Fuel Gauge | Texas Instruments | [BQ27441-G1 Datasheet](https://www.ti.com/product/BQ27441-G1) |
| **IC1** | DS3231 | Extremely Accurate I2C-Integrated RTC/TCXO/Crystal | Maxim/Analog Devices | [DS3231 Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/DS3231.pdf) |
| **U3** | FT232RL | USB to Serial UART Interface | FTDI | [FT232RL Datasheet](https://ftdichip.com/products/ft232rl/) |
| **Q1** | FS8205A | Dual N-Channel Enhancement Mode Power MOSFET | Fortune/Various | [FS8205A Datasheet](https://www.ic-fortune.com/) |
| **U2** | DW01A | Battery Protection IC | Fortune/Various | [DW01A Datasheet](https://www.ic-fortune.com/) |
| **Q2, Q3, Q4, Q5**| AO3404A / SI2300 | N-Channel MOSFET (Logic Level) | Alpha & Omega / Vishay | [AO3404A Datasheet](http://www.aosmd.com/res/data_sheets/AO3404A.pdf) |

## Connectors

| Designator | Part Number | Description | Manufacturer | Datasheet |
| :--- | :--- | :--- | :--- | :--- |
| **J1, J2, J3, J4, J5** | BM04B-SRSS-TB | 4-pin SH Connector, 1.0mm pitch, Top Entry | JST | [BM04B-SRSS-TB Datasheet](https://www.jst-mfg.com/product/pdf/eng/eSR.pdf) |
| **J6** | BM02B-SRSS-TB | 2-pin SH Connector, 1.0mm pitch, Top Entry | JST | [BM02B-SRSS-TB Datasheet](https://www.jst-mfg.com/product/pdf/eng/eSR.pdf) |
| **J7** | 53398-0871 | PicoBlade Header, 8 Ckt, 1.25mm pitch | Molex | [53398-0871 Datasheet](https://www.molex.com/molex/products/part-detail/pcb_headers/0533980871) |
| **J8** | USB4730 | USB Type-C Receptacle, IP67 | GCT | [USB4730 Datasheet](https://gct.co/connector/usb4730) |
| **J9** | 67910-0002 | Mini PCI Express Connector | Molex | [67910-0002 Datasheet](https://www.molex.com/molex/products/part-detail/memory_card_sockets/0679100002) |
| **J10 (Latch)** | 48099-4000 | Latch for Mini PCIe Card Holder | Molex | [48099-4000 Datasheet](https://www.molex.com/molex/products/part-detail/memory_card_sockets/0480994000) |
| **J11** | SIM8060 | SIM Card Holder | GCT/Various | - |
| **J13** | MEM2067 | Micro SD Card Holder | GCT/Various | - |
| **U$1** | B2B-PH-SM4-TB | PH Connector Header | JST | [PH Series Datasheet](https://www.jst-mfg.com/product/pdf/eng/ePH.pdf) |

## Passive Components (Selected)
*Note: Standard resistors and capacitors are listed with their values.*

| Components | Type | Package | Value/Description |
| :--- | :--- | :--- | :--- |
| **L1** | Inductor | 7045 | 1uH (MDH7045C-220MA family) |
| **C1, C2, C5, C6** | Capacitor | Aluminum / Tantalum | 100uF |
| **C7** | Capacitor | 0805 | 47uF |
| **C3, C15, C16, C29, C32** | Capacitor | 0805 | 10uF |
| **C9** | Capacitor | 0805 | 4.7uF |
| **C4, C8, C27, C31, C33** | Capacitor | 0805 | 1uF |
| **R1** | Resistor | 0805 | 48.7K |
| **R2, R3** | Resistor | 0805 | 102K |
| **R34** | Resistor | 1206 | 0.01R (Current Sense) |
