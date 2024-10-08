# Electronics
PCB v.0.1

Część elektroniczna robota została wykonana w programie Kicad EDA. Do projektu wykorzystano poniżej wymienione elementy:
* Serwa Feetech FI7635M - obrót 180 stopni
* Przetwornice Pololu D36V50F7
* Raspberry pi 4b 4GB
* Sterownik serw Pololu maestro mini 16-kanałowy (12-kanałowy też można wpiąć)
* Wyjścia USB-C, micro-HDMi, USB mini-B - w celu zewnętrznego podpięcia się do robota bez konieczności wyjmowania Raspberry pi oraz sterownika serw
* Moduły I2C, SPI w celu dokonywania pomiarów za pomocą zewnętrznego przetwornika ADC, akcelerometru, komunikacji z Gamepadem, czujnikami prądu czy też sterownikami diod
* Moduł konwertera napięć do komunikacji między raspberry PI a sterownikiem Pololu Maestro Mini

## Schemat połączeń

<img src="https://github.com/user-attachments/assets/5ec6ac46-b3a4-433a-acf5-d819b28db146" width="700" alt="image">

## Widok płytki PCB ze ścieżkami oraz widok 3D

<img src="https://github.com/user-attachments/assets/a7eec8a2-031b-4ca0-948b-49a6f5cfb982" width="350" alt="image">
<img src="https://github.com/user-attachments/assets/0b16ec17-e14e-4dbf-96d8-df1000f2d60c" width="400" alt="image">
