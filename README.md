# ⚡ Industrial Electrical Installation Design with Caneco BT

This project documents the low-voltage electrical design of an industrial installation supplied by a private transformer connected to the three-phase SOMELEC network. The installation is organized around a main low-voltage switchboard (TGBT) supplying two separate workshops.

The study compares two earthing arrangements for the same installation: **TT** and **IT**. Each arrangement has its own Caneco BT project files in the corresponding folder.

## 🏭 Installation overview

The design brief includes two industrial workshops with different types of loads:

- **Workshop 1:** machine tools, including lathes and drilling machines, plus socket outlets and lighting.
- **Workshop 2:** industrial furnaces and fans, plus socket outlets and lighting.

The project considers the distribution from the transformer and TGBT to the workshop distribution boards and their loads.

## 📁 Repository structure

```text
caneco-bt-industrial-installation/
├── README.md
├── regime-tt/   # Caneco BT project files for the TT arrangement
└── regime-it/   # Caneco BT project files for the IT arrangement
```

### `regime-tt/`

Contains the Caneco BT files for the installation studied with a **TT earthing arrangement**. In this configuration, the transformer neutral and the installation's exposed conductive parts are connected to earth through separate earthing arrangements. The project examines the associated protection choices and electrical distribution.

### `regime-it/`

Contains the Caneco BT files for the same installation studied with an **IT earthing arrangement**. In this configuration, the transformer neutral is isolated from earth or connected through a high impedance, while exposed conductive parts are earthed. The project examines the protection approach for this arrangement, including continuity of supply after a first insulation fault.

## 🔧 Work covered

The study includes:

- Analysis of the industrial load schedule and installation layout
- Power balance for the workshops and the main switchboard
- Transformer capacity selection
- Selection of circuit breakers and other protective devices
- Cable sizing based on the installation requirements
- Voltage-drop calculations
- Single-line diagrams for the TT and IT alternatives
- Comparison of the protection and design choices for both earthing arrangements

Caneco BT is used for the installation design, with theoretical calculations included for comparison. The project report refers to NF C 15-100 as its design reference.

## 📂 Project files

The `regime-tt/` and `regime-it/` folders are intended for the corresponding Caneco BT project files. Keep each set of files in its matching folder so the two design alternatives remain easy to distinguish.

GitHub does not retain empty folders. Add the actual Caneco BT files to each folder when uploading the repository.

## 📝 Notes

- TT and IT are two design alternatives for **one industrial installation**, not two separate sites.
- The report and presentation are not required in this repository; the README summarizes the project scope and explains the folder structure.
- This repository records an academic design study. The calculations and design choices should be checked against the applicable requirements before being used for a real installation.
