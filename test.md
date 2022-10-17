## Test  

![KBL2200 rev. NC](https://live.staticflickr.com/65535/52433541806_ea62760402_q.jpg "prototype")
![PCB layout rev. NC](https://live.staticflickr.com/65535/52432990647_7c1d45234d_q.jpg "pcb layout")  

Breakout board for the stm32l0 mcu.

***Brief***  
Made for testing the STM32L011F3P6 chip.

***Design***  
An stm32l0, in 20TSSOP package, has it's pins connected to two 10-pin headers. These headers are conveniently spaced to fit a standard breadboard. The breakout board is very minimal; containing 1 power switch, 1 reset switch, 1 led, and a 20-pin header for flashing firmware. Additional peripherals will be connected to the mcu via the breadboard.

***Wishlist***  
* Hardware Upgrades:
    * Replace 20-pin header with tag-connect to reduce space.