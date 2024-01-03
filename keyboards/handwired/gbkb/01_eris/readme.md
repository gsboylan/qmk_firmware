# handwired/gbkb/01_eris

This is a handwired split board with an alice-like layout, utilizing RP2040 "[pico mini](https://www.aliexpress.us/item/3256805694704397.html)" microcontrollers. Note that the pinout of this microcontroller is not pro-micro compatible.

This keyboard was designed in collaboration with Steve DaSilva.

In order to configure this board using VIA, you must first compile and flash the 'via' keymap and then load `keymaps/via/keyboard.json` in the Via gui editor.

* Keyboard Maintainer: [Graham Boylan](https://github.com/gsboylan)

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Holding down the top left key on half of the board while connecting that half to USB will enter the bootloader.
* **Physical reset button**: Hold the 'BOOT' button on the microcontroller while resetting or connecting to usb 
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
