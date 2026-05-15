# 🔧 PC Hardware Assembly & System Building Lab

> Hands-on PC hardware assembly, component identification, and OS installation on physical machines

![Hardware](https://img.shields.io/badge/PC_Hardware-Assembly-FF6B35?style=for-the-badge&logoColor=white)
![Windows](https://img.shields.io/badge/Windows_10%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📋 Project Overview

Independently assembled desktop PCs from scratch at Jetking Institute lab. Identified, handled, and installed all hardware components correctly. Also mentored fellow students on hardware identification and assembly process. Installed operating systems on physical machines including Windows 10, Windows 11, and Linux distributions.

---

## 🖥️ Hardware Components Worked With

| Component | Details Practiced |
|---|---|
| Motherboard | ATX form factor, socket identification, slot types |
| CPU / Processor | Installation, thermal paste application, cooler mounting |
| RAM | DDR4 slot identification, dual-channel configuration |
| Storage | HDD and SSD installation, SATA cable connections |
| PSU | Power supply connections, 24-pin ATX, CPU 8-pin |
| GPU | PCIe slot installation, power connector |
| Cabinet | Component mounting, cable management |
| SMPS | Power rating understanding, connectors |

---

## ⚙️ Assembly Process — Step by Step

### Step 1 — Prepare the Cabinet
```
- Remove side panel
- Install standoffs for motherboard mounting
- Plan cable routing before component installation
```

### Step 2 — Install CPU on Motherboard
```
- Identify CPU socket type (LGA/AM4)
- Lift retention lever
- Align CPU with socket notches
- Place CPU without forcing
- Lower retention lever to lock
- Apply thermal paste (pea-sized amount)
- Mount CPU cooler and connect fan header
```

### Step 3 — Install RAM
```
- Identify RAM slots (A2/B2 for dual channel)
- Press both latches outward
- Align RAM notch with slot key
- Press firmly until both latches click
- Verify dual-channel configuration in BIOS
```

### Step 4 — Install Storage
```
HDD/SSD:
- Mount in drive bay with screws
- Connect SATA data cable to motherboard
- Connect SATA power cable from PSU

M.2 SSD (if applicable):
- Insert at 30-degree angle into M.2 slot
- Secure with M.2 screw
```

### Step 5 — Install Motherboard in Cabinet
```
- Align I/O shield with cabinet cutout
- Place motherboard on standoffs
- Secure with motherboard screws (don't overtighten)
```

### Step 6 — Connect Power Supply
```
- 24-pin ATX main power → motherboard
- 8-pin CPU power → top of motherboard
- SATA power → storage drives
- PCIe power → GPU (if needed)
```

### Step 7 — Front Panel Connections
```
- Power switch → PWR_SW pins
- Reset switch → RESET pins
- Power LED → PWR_LED pins
- HDD LED → HDD_LED pins
- USB 3.0 header → USB3 connector
- Audio header → AAFP connector
```

### Step 8 — First Boot & BIOS
```
- Connect monitor, keyboard, mouse
- Power on — enter BIOS (Del/F2)
- Verify all components detected:
  ✓ CPU model and speed
  ✓ RAM size and frequency
  ✓ Storage drives listed
- Set boot priority to USB/DVD for OS install
- Save and exit BIOS
```

---

## 💿 Operating System Installation on Physical Machine

### Windows 10/11 Installation
```
1. Create bootable USB using Rufus
2. Boot from USB (F8/F12 boot menu)
3. Select language, time, keyboard
4. Custom installation → delete old partitions
5. Create new partition for Windows
6. Complete installation (15-20 minutes)
7. Post-install: Windows Update, drivers
8. Install chipset, audio, network drivers
```

### Linux Installation (Ubuntu)
```
1. Download Ubuntu ISO
2. Create bootable USB with Rufus/Etcher
3. Boot from USB
4. Choose "Install Ubuntu"
5. Select timezone and keyboard
6. Create username and password
7. Complete installation → restart
8. Post-install: sudo apt update && sudo apt upgrade
```

---

## 🔍 Hardware Troubleshooting Practiced

| Issue | Diagnosis Method | Solution |
|---|---|---|
| PC won't POST | Check RAM seating, CPU power | Reseat RAM, check 8-pin connector |
| No display | Check GPU/monitor cable | Reseat GPU, test with onboard video |
| Overheating | Check CPU temp in BIOS | Reapply thermal paste, check cooler |
| No boot device | Check BIOS boot order | Set correct boot device |
| System beeps | Count beep codes | Refer motherboard manual |
| Slow performance | Check Task Manager | Clean dust, check thermal throttling |

---

## 👨‍🏫 Teaching Experience

Mentored fellow students at Jetking Institute on:
- Identifying motherboard components and slots
- Safe handling of static-sensitive components (ESD precautions)
- Step-by-step PC assembly process
- BIOS navigation and basic configuration
- Troubleshooting common POST errors

---

## ✅ Results Achieved

- ✔️ Assembled 2+ desktop PCs independently from components
- ✔️ Successfully installed Windows 10/11 on physical machines
- ✔️ Installed Linux (Ubuntu) on physical hardware
- ✔️ Diagnosed and resolved common hardware issues
- ✔️ Mentored students — improved lab teaching skills
- ✔️ Completed all tasks without hardware damage

---

## 📚 Skills Demonstrated

`PC Assembly` `Hardware Troubleshooting` `Component Identification`
`BIOS Configuration` `OS Installation` `Windows 10/11` `Ubuntu Linux`
`ESD Safety` `Cable Management` `System Building`

---

*Lab completed at Jetking Institute Faridabad — Jan–Apr 2026*
