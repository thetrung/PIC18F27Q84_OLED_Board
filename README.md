PIC18F27Q84 OLED Playboard
==============================
Nothing much to say, just for entertainment & satisfy myself for designing things in my head.

![](https://github.com/thetrung/PIC18F27Q84_OLED_Board/blob/master/Images/View_Render.png)

### Overview ::
**MCU SPECS:** 64Mhz - 128KB Flash - 8KB SRAM - 1KB EEPROM. 
Detailed information on [Microchip](https://www.microchip.com/en-us/product/pic18f27q43).

The board was made with intention to resemble tiny game consoles with proper input / output, which I got inspired by ATTiny85 board. It has :

- 1x Speaker
- 1x Power slide.
- 4x Buttons Input.
- 10x LEDs on Top Row.
- 4x LEDs above all buttons.
- 1x LEDs to indicate power state.
- 1x LED for STATUS (anything you want).
- ICSP to Program with Microchip PICKIT 3/4/5.
- OLED 128x32 Module support pins (SDA/SCK/VCC/GND).
  
![](https://github.com/thetrung/PIC18F27Q84_OLED_Board/blob/master/Images/View_Front.png)

- The 3V Battery Holder can be installed on the back. Although I'm not sure if it can actually run since got nothing to test but any compatible coin-battery should work somehow (CR2032, LIR2032... but I aim for CR2450). Turn off any unused / unnecessary modules inside your PIC & outside the board to save power on battery. I only tested this dual power system via simulator mostly :
  
![](https://github.com/thetrung/PIC18F27Q84_OLED_Board/blob/master/Images/View_Back.png)

### Schematic ::

![Schematic](https://github.com/thetrung/PIC18F27Q43_OLED_Board/blob/master/Images/Schematic.png)

