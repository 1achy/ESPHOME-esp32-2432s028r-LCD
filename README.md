# ESPHOME esp32-2432s028r 


This start to project of https://github.com/niahane/meteo-thermostat



This is the program I wrote with esphome for my esp32-2432s028r very cheap board with esp32 + lcd ILI9341 2.8"

## Hardware
### Specifics
2.8″ 240×320 SPI ILI9341V with Touch Panel

### Configuration:
1. ESP32 with TELEC(211-161007): Internal 4MB (32Bit) Flash
2. External 4MB (32Mbit) Flash memory, winbond 25Q32JVSlQ rev 1.  2022.09.13: U3 4MB, U4 4MB. It is now Parallel SPI.
3. LCD ( ILI9341V  ) with Touch ( U3 :  XPT2046 resistive film method)
4. Expanded IO x 2
  - P3 ( GND, GPIO_35, GPIO_22, GPIO_21)
  - CN1 ( GND, NC, GPIO_27, 3V3)
5. SD SLOT ( Micro SD )
6. RGB LED ( MHP5050RGBDT  )
  - BLUE : GPIO_16, RED : GPIO_4, GREEN : GPIO_17
7. CDS ( GT36516  ) : GPIO_34
8. EXT Power Conn : P1 ( VIN, TX, RX, GND )
9. Audio OUT( Audio amp SC8002B ) : P4 SPEAK(2=VO2,1=VO1)
10. P1: Power Supply Base Conector
11. Included: Touch pen, 4pin External connector cable, USB Cable.






Weather : 3 button on all page -/+ scroll page and central for active heater
![foto](https://github.com/1achy/ESPHOME-esp32-2432s028r-LCD/blob/main/readme_img/example.jpg)
Wind
![foto](https://github.com/1achy/ESPHOME-esp32-2432s028r-LCD/blob/main/readme_img/vento.jpg)
This monitoring tempetarure int and externale and more 2 button +/- fore heater regulation
![foto](https://github.com/1achy/ESPHOME-esp32-2432s028r-LCD/blob/main/readme_img/grafico.jpg)
Status
![foto](https://github.com/1achy/ESPHOME-esp32-2432s028r-LCD/blob/main/readme_img/status.jpg)


Feature plus:

- touch bottom for scroll page
- touch bottom dedicated some page
- 4 page at moment wather - wind - homeassisant - status



![bme280](https://github.com/1achy/ESPHOME-esp32-2432s028r-LCD/blob/main/readme_img/1703943240-Screenshot-2023-12-30-at-14-32-26-733E-Esp-wroom-32-Esp32-For-Arduino-Lvgl-Wifi-28-28inch-Lcd-Tft-Module-With-Touch-Wroom-240-320-.png)


![rclw](https://github.com/1achy/ESPHOME-esp32-2432s028r-LCD/blob/main/readme_img/1703943134-Screenshot-2023-12-30-at-14-31-18-733E-Esp-wroom-32-Esp32-For-Arduino-Lvgl-Wifi-28-28inch-Lcd-Tft-Module-With-Touch-Wroom-240-.png)

![aztouch1](https://github.com/1achy/ESPHOME-esp32-2432s028r-LCD/blob/main/readme_img/1703942900-de997d983c0182a35cf30cceca23220db6154e67.jpeg)


## Hardware
### Wiring esp32-2432s028 + BME280 sensor
All credits for extended pinout explanation go to macsbug, see more on: https://macsbug.wordpress.com/2022/08/17/esp32-2432s028/

<img src="/../main/readme_img/esp32_2432s028_i2c.jpg" width="40%" alt= "Schematic" height="40%">

Flashing instructions: keep the boot button pressed when you plug in the USB cable/flasher, this will allow to flash the firmware.



## Next steps
1) Improve format page
2) Add Air monitor quality page
3) Add Security page alarm
4) LVGL Library implemetation start on : https://github.com/1achy/ha_deck_-ILI9341_2.8





Greetings from Achy
