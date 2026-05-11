[中文](./README.md)

# Interactive Html Bom

Interactive BOM (Bill of Materials) viewer for JLCPCB EDA Professional Edition (V3).

## Features

![alt text](images/Ibom1.png)

- Open the interactive BOM viewer directly inside the PCB editor
- BOM table and PCB view linked highlighting — click a row to locate the component
- Front/back view switching
- Net highlighting (click a trace or pad to view connections on the same net)
- Footprint silkscreen outline rendering (extracted from footprint library files, follows component rotation and mirroring)
- Silkscreen text display (automatically filters out useless information such as footprint names, keeping only designators and labels)
- Copper pour area rendering
- Multiple pad shapes (rectangle, circle, oval, regular polygon, complex polygon)
- Irregular board outlines (rounded rectangles, arc edges)
- Export as a standalone HTML file that can be opened directly in a browser, usable offline

## Usage

1. Open a PCB file in JLCPCB EDA Professional Edition
2. Top menu bar → **iBOM** → **Open Interactive BOM**
3. Wait a few seconds for data collection to complete, the iBOM renders automatically

Export HTML: Menu bar → **iBOM** → **Export HTML File**

## Origin

This project is ported from [easyeda-ibom-extension](https://github.com/turbobabr/easyeda-ibom-extension) ([Andrey Shakhmin](https://github.com/turbobabr)), originally designed for EasyEDA Standard Edition.

The iBOM core rendering engine comes from [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom) ([qu1ck](https://github.com/qu1ck)).
