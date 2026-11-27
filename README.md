<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Vishnudeva%20Govindarajan&fontSize=40&fontColor=ffffff&fontAlignY=35&desc=Embedded%20Systems%20%7C%20FPGA%20%7C%20IoT%20%7C%20Wearables&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=Embedded+Systems+Engineer+%7C+MSc+Leeds;From+register-level+firmware+to+RTL+on+FPGA;STM32+%E2%80%A2+ESP32+%E2%80%A2+ARM+Cortex-M%2FA+%E2%80%A2+Verilog%2FVHDL;Building+wearable+and+IoT+systems+that+run+on+real+hardware" alt="Typing SVG" />

<br/>

<a href="mailto:vishnu.devag@outlook.com"><img src="https://img.shields.io/badge/Email-vishnu.devag%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white"/></a>
<a href="https://github.com/vishnudevav"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Location-Singapore-E4002B?style=for-the-badge&logo=googlemaps&logoColor=white"/>

</div>

---

## `$ dmesg | grep flagship`

<a href="https://github.com/vishnudevav/wearable-health-monitor"><img src="assets/wearable-datapath.svg" width="100%" alt="Wearable Health Monitoring System datapath: five sensors (HR/SpO2, ECG, temperature, IMU, GSR) into embedded C firmware (acquisition, motion-noise filtering, vital-sign extraction), prototyped on STM32 and migrated to ESP32, streaming over Wi-Fi to a host"/></a>

---

## `$ cat about_me.h`

```c
typedef struct {
    const char *name;
    const char *role;
    const char *education[2];
    const char *experience[2];
    const char *focus[5];
    const char *status;
} Engineer;

const Engineer vishnu = {
    .name       = "Vishnudeva Govindarajan",
    .role       = "Embedded Systems Engineer",
    .education  = { "MSc Embedded Systems Engineering - University of Leeds (2026)",
                    "BEng Electronics & Communication Engineering - Anna University" },
    .experience = { "Embedded Systems Engineer Trainee - Emertxe Information Technologies",
                    "Digital Hardware & Embedded Systems Intern - Tessolve Semiconductor" },
    .focus      = { "Bare-metal firmware on STM32 / ARM Cortex-M",
                    "FPGA design in Verilog / VHDL (Quartus + ModelSim)",
                    "Wearable & biomedical sensing systems",
                    "IoT devices with ESP32 and Wi-Fi connectivity",
                    "Hardware-software co-design" },
    .status     = "Open to full-time embedded / IoT roles"
};
```

---

## `$ ls ./skills`

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-E16737?style=flat-square&logo=mathworks&logoColor=white)

**HDL & Digital Design**

![Verilog](https://img.shields.io/badge/Verilog-8A2BE2?style=flat-square)
![VHDL](https://img.shields.io/badge/VHDL-5C2D91?style=flat-square)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-6A1B9A?style=flat-square)
![RTL](https://img.shields.io/badge/RTL_Design-4B0082?style=flat-square)
![FSM](https://img.shields.io/badge/FSM-7B1FA2?style=flat-square)

**FPGA Tools**

![Quartus Prime](https://img.shields.io/badge/Quartus_Prime-0071C5?style=flat-square&logo=intel&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-1E88E5?style=flat-square)
![DE1-SoC](https://img.shields.io/badge/DE1--SoC-0071C5?style=flat-square&logo=intel&logoColor=white)
![Vivado](https://img.shields.io/badge/Vivado-ED1C24?style=flat-square&logo=amd&logoColor=white)

**Microcontrollers & Interfaces**

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![ARM](https://img.shields.io/badge/ARM_Cortex--M%2FA-0091BD?style=flat-square&logo=arm&logoColor=white)
![PIC](https://img.shields.io/badge/PIC-C41E3A?style=flat-square&logo=microchip&logoColor=white)
![UART](https://img.shields.io/badge/UART-555555?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-555555?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-555555?style=flat-square)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

---

## `$ ls ./projects`

### 01 · Wearable Health Monitoring System
> **MSc Project, University of Leeds**

A multi-sensor wearable that monitors heart rate, SpO2, ECG, body temperature, skin conductance (GSR) and motion (IMU). I prototyped it on STM32, then moved it to ESP32 to get built-in Wi-Fi for live data streaming. The hardest part was the signal: heart-rate readings were noisy and jumped, especially when the wearer moved. I worked on filtering and processing to make them stable.

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Wi-Fi](https://img.shields.io/badge/Wi--Fi-IoT-2E7D32?style=flat-square) ![Biomedical](https://img.shields.io/badge/Biomedical-Sensing-C2185B?style=flat-square)

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/vishnudevav/wearable-health-monitor)

### 02 · FPGA Human Reaction Timer
> **MSc Coursework · DE1-SoC**

A reaction-time tester written in Verilog on the DE1-SoC board. It uses a finite state machine to control the test, with timing, debouncing, and seven-segment display output, all verified in ModelSim before running on hardware.

![Verilog](https://img.shields.io/badge/Verilog-8A2BE2?style=flat-square) ![Quartus](https://img.shields.io/badge/Quartus_Prime-0071C5?style=flat-square&logo=intel&logoColor=white) ![ModelSim](https://img.shields.io/badge/ModelSim-1E88E5?style=flat-square) ![FSM](https://img.shields.io/badge/FSM-7B1FA2?style=flat-square)

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/vishnudevav/fpga-reaction-timer)

### 03 · Maze Escape Game
> **MSc Coursework · DE1-SoC (ARM Cortex-A9)**

A maze game running on the ARM Cortex-A9 hard processor of the DE1-SoC, rendered on an LT24 LCD. Includes the display driver, input handling, and the game logic loop.

![ARM](https://img.shields.io/badge/ARM_Cortex--A9-0091BD?style=flat-square&logo=arm&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![LT24 LCD](https://img.shields.io/badge/LT24-LCD-455A64?style=flat-square)

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/vishnudevav/maze-escape-de1soc)

### 04 · Car Black Box
> **Emertxe Information Technologies**

An automotive event-logging system modelled on a vehicle black box. It monitors vehicle events, timestamps them, and stores the log, using SPI and UART to communicate with peripherals.

![PIC](https://img.shields.io/badge/PIC-C41E3A?style=flat-square&logo=microchip&logoColor=white) ![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![SPI](https://img.shields.io/badge/SPI-555555?style=flat-square) ![UART](https://img.shields.io/badge/UART-555555?style=flat-square) ![Automotive](https://img.shields.io/badge/Automotive-1565C0?style=flat-square)

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/vishnudevav/car-black-box)

### 05 · LSB Image Steganography
> **Emertxe Information Technologies**

A C++ tool that hides a secret message inside a BMP image by changing the least significant bit of each pixel, and recovers it again, using bit-level file handling.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Bit Manipulation](https://img.shields.io/badge/Bit_Manipulation-37474F?style=flat-square)

[![View Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github)](https://github.com/vishnudevav/lsb-steganography)

---

## `$ git log --stat`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=vishnudevav&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vishnudevav&layout=compact&theme=tokyonight&hide_border=true"/>

<img src="https://streak-stats.demolab.com?user=vishnudevav&theme=tokyonight&hide_border=true" width="60%"/>

</div>

---

## `$ cat education.txt`

| | |
|---|---|
| 🎓 **MSc Embedded Systems Engineering** | University of Leeds, UK · 2026 |
| 🎓 **BEng Electronics & Communication Engineering** | Sri Ramakrishna Engineering College, Anna University |
| 📚 **Currently studying** | Electrical Engineering with Robotics · PSB Academy, Singapore |
| 📄 **Publication** | Co-author, *Annals of the Romanian Society for Cell Biology* |

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=36BCF7&center=true&vCenter=true&width=500&lines=Thanks+for+visiting!;Let's+build+something+on+real+hardware." alt="footer"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>

</div>
