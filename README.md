# ESP8266 RF Motor Controller PCB

## Overview
Designed a custom ESP8266-based PCB integrating power regulation, input protection, and RF-aware layout for wireless motor control applications.

## Key Features
- On-board buck converter (12V → 3.3V) using MP1584  
- Input protection using fuse and TVS diode  
- ESP8266 (ESP-12F) with programming header and reset/boot circuit  
- RF layout considerations with antenna keep-out region  
- GPIO-based control interface for external devices  

## Schematic
![[Schematic](images/schematic.png)](https://github.com/Shivampunia/ESP8266_RF_Controller/blob/main/ESP8266%20RF%20sch.png)

- Modular design with separate blocks: power, ESP module, protection, RF section  
- Proper decoupling and biasing for stable ESP operation  

## PCB Layout
![[PCB Layout](images/pcb_layout.png)](https://github.com/Shivampunia/ESP8266_RF_Controller/blob/main/ESP8266%20RF%20pcb.png)

- Short power paths and wide traces for current handling  
- RF section isolated with antenna keep-out  
- Clean routing with separation of power and signal paths  

## 3D View
![[3D View](images/pcb_3d.png)](https://github.com/Shivampunia/ESP8266_RF_Controller/blob/main/ESP8266%20RF%203d.png)

- Compact(80 mm * 22 mm )layout suitable for embedded applications  
- Proper component placement for assembly and testing  

## Design Highlights
- Integrated power + control + RF in a single board  
- Practical PCB design including protection and signal integrity awareness  
- Suitable for IoT and wireless control applications  

## Tools Used
- KiCad (Schematic & PCB Design)
- ESP8266 (ESP-12F)
