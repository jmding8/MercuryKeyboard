# Firmware and Keymap Notes



## Flashing Firmware For Wireless Builds
- See [the ZMK documentation on how to flash](https://zmk.dev/docs/user-setup#flashing-uf2-files) the firmware binaries to your keyboard.
- The default firmware binary files [are located here](/Firmware/), and are named **zmk_left.uf2** and **zmk_right.uf2**.

 

## Default Keymap
Mercury's default keymap seeks to achieve the following goals:
* All keyboard shortcuts should be accessible
* Reduce the use of the outer pinky columns
* Minimize the learning curve, especially:
  * Minimize the need for user-tuning of timing parameters (`tapping-term`)
  * Minimize the requirement for strict key-up order

To achieve these goals, we use several combos

### Modifier combos
1. `K` + `L` -> `Right Shift`
1. `S` + `D` -> `Left Shift`
1. `D` + `F` -> `Number Layer`
1. `S` + `D` + `F` -> `Shifted Number Layer`
1. `A` + `Function Layer` -> `Shifted Function Layer`

### Other combos
1. `X` + `C` -> `Tab`
1. `C` + `V` -> `Esc`
1. `M` + `Comma` -> `Caps Lock`
1. `H` + `J` -> `Menu Key` (opens the context menu, similar to `Right Click` in Windows)
1. `Q` + `W` + `E` -> activate `System Layer` for the next keypress

![keymap](/images/keymap.png)



## Bluetooth 
- After flashing the firmware, you will likely need to follow [the settings reset procedure described here](https://zmk.dev/docs/troubleshooting#split-keyboard-halves-unable-to-pair) to get the two keyboard halves to bond to each other, and to get the keyboard to pair with your computer.
- There are three Bluetooth profiles that can be used to pair with three computers. To select a specific profile, activate the `System Layer`, then press `Bt1` / `Bt2` / `Bt3` (left thumb cluster).
- To clear a Bluetooth profile so that it can pair with a different host, activate the profile you wish to clear. Then activate `System Layer`, and press  `BtClear` (`C` key).
- By default, the keyboard will always prefer to send output to USB when a USB cable is connected. If you want to send output over Bluetooth while chargin your keyboard over USB, you will need to enable Bluetooth-preferred output. To do this, activate `System Layer`, then press `Bluetooth` (`B` key). To enable USB-preferred output isntead, activate `System Layer`, then press `USB` (`S` key).