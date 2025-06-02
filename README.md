# ⚡ High Power DC Load Control Unit – 2000W | STM32F103

This project features a **2-layer PCB design** that combines both **high-power switching components** and **low-power control circuitry** on a single board. It is built around the **STM32F103 microcontroller** and is capable of driving loads up to **2000W**. The design includes proper isolation techniques to ensure safety, reliability, and performance in high-current environments.

---

## 🔧 Key Features

- ✅ **Microcontroller**: STM32F103C8T6 (ARM Cortex-M3)
- 🔌 **Power Capacity**: Drives loads up to **2000W** (e.g., high-power LEDs, motors, heaters)
- 🛠️ **PCB**: Custom-designed **2-layer board** integrating high and low-power sections
- 🧯 **Isolation**: Implemented electrical isolation and layout techniques for noise immunity and component protection
- 📐 **Design Tools**: KiCad 8.0 used for schematic and PCB layout
- ⚙️ **Peripheral Drivers**: 
  - MOSFET/IGBT gate driver (e.g., UCC5350)
  - Current sensing and thermal monitoring
- 🧪 **Tested and Verified**: Proven control and protection circuitry with real load tests

---

## 📂 Project Structure

```bash
.
├── hardware/
│   ├── schematics.kicad_sch
│   ├── pcb_layout.kicad_pcb
│   ├── 3D_models/
│   └── fabrication_files/
├── firmware/
│   ├── main.c
│   ├── peripherals/
│   └── stm32f103_hal_config/
├── README.md
└── images/
    └── board_render_top.png
