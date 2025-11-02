# Electronics

PCB v.0.1

The electronic part of the robot was designed using the Kicad EDA software. The following components were used for this project:

- Feetech FI7635M Servos - 180-degree rotation
- Pololu D36V50F7 Converters
- Raspberry Pi 4B 4GB
- Pololu Maestro Mini 16-channel servo controller (a 12-channel version can also be connected)
- USB-C, micro-HDMI, and USB mini-B ports - to allow external connection to the robot without needing to remove the Raspberry Pi or the servo controller
- I2C and SPI modules - for taking measurements using an external ADC converter, accelerometer, communicating with a Gamepad, current sensors, or LED drivers
- Voltage level converter module - for communication between the Raspberry Pi and the Pololu Maestro Mini controller

## Connection Schematic

<img src="https://github.com/user-attachments/assets/5ec6ac46-b3a4-433a-acf5-d819b28db146" width="700" alt="image">

## PCB Layout (Traces View) and 3D View

<img src="https://github.com/user-attachments/assets/a7eec8a2-031b-4ca0-948b-49a6f5cfb982" width="350" alt="image">
<img src="https://github.com/user-attachments/assets/0b16ec17-e14e-4dbf-96d8-df1000f2d60c" width="400" alt="image">
