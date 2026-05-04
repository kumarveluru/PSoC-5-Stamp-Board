# PSoC 6 BLE Stamp Board

This repository contains all the essential files related to the **PSoC 6 BLE Stamp Board**, 
a compact, stamp-sized development board based on the **Cypress CY8C6347BZI-BLD53 (PSoC 63)** 
microcontroller. It features a dual-core **ARM Cortex-M4 + Cortex-M0+** architecture, 
integrated **Bluetooth 5.0 Low Energy (BLE)**, programmable analog and digital peripherals, 
and castellated edge pins for easy SMD module integration.

You will find the following:

- **Board Schematic:** A detailed circuit design of the PSoC 6 BLE Stamp Board.
- **PCB Layout:** The physical design of the printed circuit board.
- **PCB Routing:** The connections and pathways for signals and power on the PCB.

For more details, refer to:
- [CY8CPROTO-063-BLE Product Page](https://www.infineon.com/evaluation-board/cy8cproto-063-ble)
- [PSoC 63 Datasheet](https://www.infineon.com/assets/row/public/documents/30/44/infineon-psoc-tm-6-cy8cproto-063-ble-with-airoc-tm-bluetooth-r-le-prototyping-board-user-guide-usermanual-en.pdf)

---

### Tools Used

The electronic design and development were done using **KiCad**, an open-source EDA software.
The version used for this project is **KiCad 9.0.7**.

#### The footprints of all Resistors, Capacitors, Inductors, LEDs:
`0603_1608Metric_Pad1.08x0.95mm_HandSolder`

All the files are attached in the repository folder.

A custom library was created to import certain symbols into the schematic along with their corresponding footprints and 3D models.

The name of the library is:
- **connectors.kicad_sym** : for symbols
- **My library.pretty** : for footprints

---

## Schematic

![Schematic](https://github.com/kumarveluru/PSoC-5-Stamp-Board/blob/main/Images/Root%20Schematic.png)


---

## PCB Layout

### Placement of Components

![Component Placement](https://github.com/kumarveluru/PSoC-5-Stamp-Board/blob/main/Images/Placement.png)

### Overall PCB Layout

![PCB Layout](https://github.com/kumarveluru/PSoC-5-Stamp-Board/blob/main/Images/Layout.png)

---

## 3D View

### Top View

![3D Top View](https://github.com/kumarveluru/PSoC-5-Stamp-Board/blob/main/Images/3D%20view%20Top.png)

### Bottom View

![3D Bottom View](https://github.com/kumarveluru/PSoC-5-Stamp-Board/blob/main/Images/3D%20view%20Bottom.png)

---

## Board Dimensions

| Parameter | Value    |
|-----------|----------|
| Width     | 31.26 mm |
| Height    | 29.175 mm |

---

## License

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---


## Contact

V Kumar - V.Kumar@iiitb.ac.in 
V Kumar — [GitHub Profile](https://github.com/kumarveluru)
Project Link: [https://github.com/kumarveluru/PSoC-5-Stamp-Board](https://github.com/kumarveluru/PSoC-5-Stamp-Board)



## Acknowledgments

I would like to express my sincere gratitude to my college, **International Institute of Information Technology (IIIT-B)**, for providing the resources and support to complete this project.  

I am especially grateful to my professor, **Dr. Kurian Polachan**, for their invaluable guidance, encouragement, and expertise throughout the development of this work.
