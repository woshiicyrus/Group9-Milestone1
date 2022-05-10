# Group9-Milestone1
Blinky on STM32F411CEU6

**Group Member**

Yap Swee King - MKE211094

Muhammad Syakir bin Ahmad Zahiri - MKE211071

Rafiqi bin Rosli - MKE211067

**Overview**

Board used: STM32F411CEU6 (Cortex M4)

IDE used: STM32CubeIDE

Before configuration, we will need to update the firmware for the ST-Link using ST-Link Utility.
In the board configuration, we connected Port GND, SCK, DIO and 3V3 to the pins between the ST-Link V2 and STM32F411CEU6. 
We configured the Port C13 as output to light up the LED that have built-in at the microcontroller.
After the code generation, we programmed the pin 13 to ON by setting it to 1, while OFF by setting it to 0. For the delay in between the ON and OFF of the LED,
we set the value as 1000ms, the value can be changed to a higher value to configure the duration of the delay. 
Then, we flashed the HEX file to the board to see the result of the blinky.

**Photo**
![image](https://imgur.com/a/5m9NZcx)

**Youtube Link**
https://www.youtube.com/watch?v=lIQ3XBnW-Fk
