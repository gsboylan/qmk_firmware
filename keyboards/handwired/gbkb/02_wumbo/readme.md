# handwired/gbkb/02_wumbo

This is a hand-wired, qwerty keyboard with 1u modifiers, 4 rows, and an 8-key bottom row with split spacebars.

This board utilizes an RP2040 "[Pico Mini](https://www.aliexpress.us/item/3256805694704397.html)" which is not pinout-compatible with the Pro Micro. 

* Keyboard Maintainer: [gsboylan](https://github.com/gsboylan)

Make example for this keyboard (after setting up your build environment):

    make handwired/gbkb/02_wumbo:default

Flashing example for this keyboard:

    make handwired/gbkb/02_wumbo:default:flash

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the top-left key and plug in the keyboard
* **Physical reset button**: Hold the 'BOOT' button on the microcontroller while pressing reset or connecting USB.
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
