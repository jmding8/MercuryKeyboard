# Firmware Guide

*** 

## Default Keymap
Mercury's default keymap:
![keymap](/images/keymap.png)
- The `Q` key acts as a shift modifier only when held in combination with the `Tab / Function_Layer` key.
- The `A` key acts as a shift modifier only when held in combination with the `Escape / Number_Layer` key.
- The `System_Layer` is accessed by holding the `Tab / Function_Layer` key and the `Escape / Number_Layer` keys down at the same time.
- Windows mode is toggled by `System_Layer` + `W`, and changes the order of the modifiers under the left thumb to Windows -> Alt -> Ctrl (left to right).

***

## Flashing Firmware For Wireless Builds
- For **wireless builds**, ZMK is the preferred firmware to use with the Nice!nano controller boards.
- See [the ZMK documentation on how to flash](https://zmk.dev/docs/user-setup#flashing-uf2-files) the firmware binaries to your keyboard.
- The default firmware binary files [are located here](/Firmware/), and are named **zmk_left.uf2** and **zmk_right.uf2**.
- After flashing the firmware, you will likely need to follow {the settings reset procedure described here](https://zmk.dev/docs/troubleshooting#split-keyboard-halves-unable-to-pair) to get the keyboard halves to bond and to get the keyboard to pair with your computer.
- If you want to modify the default keymap or firmware settings, see [the ZMK documentation on customization](https://zmk.dev/docs/customization).

***

## ~~Firmware For Wired Builds~~ Coming Soon...

***

## Bluetooth 
- After flashing the firmware, you will likely need to follow {the settings reset procedure described here](https://zmk.dev/docs/troubleshooting#split-keyboard-halves-unable-to-pair) to get the two keyboard halves to bond to each other, and to get the keyboard to pair with your computer.
- There are three Bluetooth profiles that can be used to pair with three computers. To activate a profile, `System_Layer` + `Bt1` / `Bt2` / `Bt3` (located under the left thumb).
- To clear a Bluetooth profile (to pair with a different computer for example), activate the profile then `System_Layer` + `Bt_Clear` (located under the `C` key).
- By default, the keyboard will prefer to send output to USB if  both USB and Bluetooth are connected. If you want to charge your keyboard but output to a different device over Bluetooth at the same time, you will need to enable Bluetooth-preferred output. To do this, `System_Layer` + `Bluetooth_Out` (located under the `B` key). To re-enable USB-preferred output, `System_Layer` + `USB_Out` (loacted under the `S` key).