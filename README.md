# LowKey36c (for choc) by Matt Gilbert

This is the ZMK source repo for the LowKey36c spit keyboard.

## This is a prototype!

As this is a prototype, the files here have not been merged with the main repo for ZMK. That means that you must fork and clone this repo to your own account, and then use the firmware built from the automation. You can't use the standard ZMK setup to build the firmware for this board yet. When I've completed v2.0 of the PCB I will open a PR with ZMK to get this shield added to the included options.

This board is designed to be used with Seeed Xiao nRF52840 (BLE) controllers. I have included ZMK Studio support. This also uses the RGB LED on the Seeed Xiao via the excellent [RGBLED Widget](https://github.com/caksoylar) to show battery level, connection state, and active layer.
