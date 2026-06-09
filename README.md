# Navion FC

## What is it
It is a small all-in-one flight controller used for autonomous vehicles.

It will run Ardupilot and is compatible with any type of autonomous vehicles.

## Features ✅
-  Barometer
-  IMU
-  Magnometer
-  10 PWM outputs
-  PPM/SBUS input
-  4 Neopixel outputs
-  MicroSD Card Reader
-  USB-C Connector
-  SWD Debugging Interface
-  3 UART Headers
-  1 USART Header
-  1 I²C Header
-  Safety Switch Header
-  16MB External Flash
-  Battery Voltage Monitoring
-  Up to 40V battery input voltage
## Why do I want to make it ? 🛠️

I have always been passionate about autonomous vehicles and wanted to build a universal solution that can run all of the vehicles I'll be building in the future.

That's why I made my flight controller extremely modular and versatile.

## How does it work ?

-  You attach all of your ESCs and Servos to the PWM outputs.

-  Attach neopixel strips to the top neopixel headers (You should power them externally).

-  Connect a standard Pixhawk 2.4.8 (or similar) GPS module (You need to swap the connectors for JST-XH connectors) to the GPS and I²C headers.

-  Connect the battery to the battery header.

-  Connect the RC receiver to the PPM/SBUS header (and configure it accordingly later).

-  Connect a telemetry module to the USART2 header.

-  You can connect other UART accessories like a Lidar to the UART2 and UART3 headers.

-  Then you configure your peripherals in **Mission Planner**, setup your flight controller, plan a mission, and you should be good to go !

## PCB 

### Schematic

<img width="4960" height="3507" alt="image" src="https://github.com/user-attachments/assets/37276798-0427-413a-8887-e5d0241f29fb" />

### Routing

<img width="1177" height="818" alt="image" src="https://github.com/user-attachments/assets/51dcb585-e58f-458f-b954-c37ecdbd4add" />

### 3D View

<img width="1080" height="823" alt="image" src="https://github.com/user-attachments/assets/2892fb74-9cbe-479c-8d38-4aa69b9580b1" />

## 3D Deisgn 🎨

<img width="901" height="717" alt="image" src="https://github.com/user-attachments/assets/f7469d78-7478-428b-be6f-12c3d8ba1a74" />

<img width="852" height="701" alt="image" src="https://github.com/user-attachments/assets/e3d9691a-3380-4c3d-80c9-2940a213f71c" />

## Firmware

This flight controller will run a custom ported version of the **[Ardupilot firmware](https://github.com/ArduPilot/ardupilot)**

## Disclaimer ⚠️

This project is still untested.

## Credits ❤️
Project made by : **Oussama NAOUAR**

Total logged working hours : **40 hrs**

Made as part of the **Hack Club Fallout** program.
