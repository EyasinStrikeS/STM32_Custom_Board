# STM32_Custom_Board

# STM32 Custom Board (Altium Project)

This is a custom development board designed with an STM32 microcontroller using Altium Designer. It is currently at the **design stage** and ready for prototyping.

## 🎯 Goal

- Develop a minimal STM32 platform for embedded systems development.
- Include basic interfaces: USB, SWD, and GPIO.
- Optimize for beginner-friendly programming and low BOM cost.

## 🧰 Tools Used

- Altium Designer 24.x
- STM32CubeMX (for pin mapping and peripheral planning)

## 🧩 Features

- MCU: STM32F103C8T6 (can be swapped)
- USB Micro-B for data/power
- 3.3V LDO regulator
- Reset + User buttons
- Status LED
- SWD header for debugging
- Breakout headers for GPIO

## 📁 Project Contents

- `Hardware/`: Full Altium schematic and PCB layout files
- `Output_Files/`: Gerbers, BOM, and PnP files for manufacturing
- `Docs/`: PDF schematic and 3D renders of the board

## 🖼️ Preview

### Schematic Snapshot
![Schematic](Docs/PDF_Schematic.png)

### 3D Render
![3D Board](Docs/3D_Render.png)

## ✅ Current Status

✔️ Schematic completed  
✔️ PCB layout completed  
✔️ DRC and ERC passed  
🕐 Awaiting fabrication

## 📝 Next Steps

- Manufacture PCB (JLCPCB or OSH Park)
- Assemble and validate design
- Add test firmware (blinky, USB CDC, etc.)
- Expand with sensor/communication modules

## 📄 License

MIT — Feel free to fork, improve, and use this design!
