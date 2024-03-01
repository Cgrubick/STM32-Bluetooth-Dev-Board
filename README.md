# STM32-Bluetooth-Dev-Board
STM32 based PCB design
By Clayton Grubick

Overview

This repository contains the design files, firmware, and documentation for a custom-designed PCB featuring an STM32 microcontroller with Bluetooth capabilities. The project is aimed at demonstrating advanced PCB design techniques, including RF circuitry for Bluetooth communication, making it suitable for a wide range of wireless applications.
Features:

STM32WB55CEU6 : Utilizes a high-performance STM32 MCU, offering ample processing power for complex applications
USB-C Connectivity: Utlizied USB-C with USB2.0 for connecting to the board and communication and power supply. Paired with the USB ESD protection IC
LDO Regulator: 5V to 3.3V supply
SWD Intereface: SWD connection for programming and debugging
RF Circuit: Impedence matching network and a LPF directed into a coaxial connection
Bootloader Button: Debouncing circuit and bootloader switch for firmware
This was my first higher level PCB design and also my first try at designing RF circuits, while the RF portion in this board is pretty trivial it was still a great exercise.

The low pass filter footprint is custom and the 3D model is also included under the 3D models folder, more info and data sheets are also included.

Schematic
![image](https://github.com/Cgrubick/STM32-Bluetooth-Dev-Board/assets/75959508/545121e6-cdc9-4b15-ba19-069c787c6414)


PCB

![image](https://github.com/Cgrubick/STM32-Bluetooth-Dev-Board/assets/75959508/7e5bf997-2409-4929-878b-0d1a05b9b684)


3D view

![image](https://github.com/Cgrubick/STM32-Bluetooth-Dev-Board/assets/75959508/8d89d61f-f6c8-4529-af9e-ff689ddc7a10)


TODO:

  -Manafuacture PCB
  
  -Write and load firmware onto board
  
  -Perform some simple embedded project with the board such as communication over bluetooth and sending and recieving data from an external computer




Credit/Inspo: Phils Lab
