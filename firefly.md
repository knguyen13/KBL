## Project firefly

Automatic light. Designed to brighten up our lightless storage closet.

***Brief***
Lights up the closet when the door is opened and turns off when the door is closed.

***Design***
An stm32l0 mcu polls a magnetic sensor(reed switch) to detect when the door is opened or closed.
When door open is detected, the mcu will activate the relay to connect the 12V Li-Ion battery to the light bar;

***Wishlist***
* Firmware Upgrades:
    * Add timer to automatically turn off after 5 minutes in case user has forgotten to close the door.
    * Add low power mode with wakeup on interrupt to conserve energy while not in use.

* Hardware Upgrades:
    * Use buck converter to power the stm32 to avoid having 2 separate power sources.
