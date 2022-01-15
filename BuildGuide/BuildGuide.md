# Build Guide

 

## Check Kit Contents
- [ ] 1x QWERT-hand plate
- [ ] 1x HJKL-hand plate
- [ ] 1x QWERT-hand base
- [ ] 1x HJKL-hand base
- [ ] 1x PCB
- [ ] 2x reset switches (YD-3414)
- [ ] 24x M2 screws (4mm, wafer head)
- [ ] 12x standoffs (~3mm diameter, brass)
  - 7mm for low-profile, Kailh PG1350 Chocolate switches
  - 9mm for standard, MX style switches
- [ ] 8x Non-slip feet
- [ ] (optional) 2x batteries
- [ ] (optional) 2x 3.5mm TRRS jacks, PJ-320A
- [ ] (optional) 1x left case
- [ ] (optional) 1x right case

 

## Gather Additional Parts
- [ ] 42x switches, standard MX or Kailh PG1350 Chocolate
- [ ] 42x 1u keycaps
- [ ] Controller boards
  - Split + wireless: 2x Nice!Nano
  - Single_piece + wireless: 1x Nice!Nano
  - Split + wired: 2x ProMicro (Elite-C and Proton-C not yet verified to work)
  - Single_pice + wired: 1x ProMicro (Elite-C and Proton-C not yet verified to work)
- [ ] (optional for wired+split) 1x 3.5mm TRS (mono) or TRRS (stereo) cable
- [ ] (optional) 84x Mill-Max sockets
  - 7305, 0305-0 and 0305-1 only!
  - 0305-2 sockets are too long and will NOT work!

 

## Gather Tools
- [ ] Flush cutter
  - Due to limited space and tight clearances, typical side-cutters may not be able to trim the pins close enough to the surface of the PCB. It is best to use a pair of flush-cutters instead, [such as these](https://www.amazon.com/XURON-170-II-Micro-Shear-Flush-Cutter/dp/B07BSSG48F).
- [ ] Phillips screwdriver
- [ ] Soldering equipment
- [ ] Tweezers
- [ ] Tape
- [ ] (optional) Black permanent marker (Sharpie)

 

## Pre-build Notes
- [ ] Read all instructions before starting the build! Or at least read each sub-section before starting the steps.
- [ ] Familiarize yourself with the plates and PCB. Note the printed labels on the plates, bases, and PCB are labeled.
![Labels](/images/build/labels.jpg)
- [ ] This build guide uses the terms **QWERT-hand** / **HJKL-hand** and **user-side** / **table-side** to refer to the two halves of the PCB and their two respective faces. This is because the terms left/right and top/bottom get ambiguous as soon as the PCB is rotated or flipped over. Pay special attention that you are working on the correct half of the PCB and on the correct side, because it is very easy to accidentally make mistakes this way.
- [ ] Decide how you want to build your Mercury:
1. Split + wireless
![mercury](/images/split_wireless.jpg)

1. Split + wired
![mercury](/images/split_wired.jpg)

1. Single-piece + wireless
![mercury](/images/merged_wireless.jpg)

1. Single-piece + wired
![mercury](/images/merged_wired.jpg)



## TRRS sub-boards
- [ ] For **split+wired builds**, solder both TRRS jacks to the **user-side** of both halves of the PCB.
![Solder TTRS jacks](/images/build/trrs.jpg)
- [ ] For **all other builds** (split+wireless, single_piece+wireless, and single_piece+wired), snap off the TRRS sub-boards from the PCB.
![Snap off TRRS sub-boards](/images/build/remove_trrs.jpg)

 

## Edge Color
- [ ] (optional) use a black permanent marker to paint the edges of the plates and bases black.

 

## PCB halves
  - [ ] For **single_piece builds**, skip this section.
  - [ ] For **split builds**, cut along the divots just to the left and right of the bulge in the middle of all eight PCB bridges.
![Bridge Cut Points](/images/build/cutpoints.jpg)
  - [ ] Double check that the PCB halves sit flush against each other with no gap between them.
![Flush PCBs](/images/build/flush.jpg)

 

## Controller board header pins
- [ ] Shorten two strips of header pins to 10 pins long.
![Shorten header pin strips](/images/build/shorten_headers.jpg)
- [ ] Insert the **short legs** of the header pin strips into the **QWERT-hand** half of the PCB, through the **table-side**.
![Insert header pin strips](/images/build/insert_headers.jpg)
- [ ] Double check that the **short legs** of the header pins are inserted into the PCB.
- [ ] Double check that the header pins inserted down through the **table-side** of the PCB.
- [ ] Double check that the header pins are inserted into the **QWERT-hand** half of the PCB.
- [ ] Place the controller onto the header pins and use a piece of tape to hold everything together temporarily.
![Tape controller in place](/images/build/tape_controller.jpg)
- [ ] Using flush cutters, trim the header pins flat to the surface of the PCB.
![Trim header pins flush](/images/build/trim_header_pins_flush.jpg)
- [ ] Solder the header pins **to the PCB only**. Do not solder the controller board.
![Solder header pin strips to PCB](/images/build/solder_headers.jpg)
- [ ] Remove the controller board and set it aside for now.
- [ ] For **split builds**, repeat this process for the second set of header pins on the **HJKL-hand** half of the PCB.



## Optional: remove spacers from headers
- [ ] This step is optional but recommended. It makes it easier to remove the controller boards later if they need to be replaced for repair, upgrade, or other purposes.
- [ ] Use pliers to carefully pull the plastic spacers off of the headers. They should slide off with gentle rocking and pulling.
![Remove plastic spacers](/images/build/header_removal.jpg)
- [ ] It is still necessary to precisely space the controller board away from the PCB. To facilitate this, cut 6x single-pin spacers from the strip. Reinstall three of these single-pin spacers roughly where pictured, and repeat for the second controller.
![Reinstall trimmed spacers](/images/build/header_spacers.jpg)

 

## Reset switches
- [ ] Solder the reset switch to the **table-side** of the **QWERT-hand** half of the PCB.
![Reset switch](/images/build/reset.jpg)
- [ ] For **split builds**, also solder a reset switch to the **table-side** of the **HJKL-hand** half of the PCB.

 

## Switches
- [ ] Screw the standoffs securely to the **table-side** of both plates.
![Attach standoffs](/images/build/standoff.jpg)
- [ ] Using flush cutters, trim the legs of four switches flush with the PCB. This is to prevent these switches from accidentally short circuiting against the controller boards.
![Trim switch legs](/images/build/mark_switch_legs.jpg)
- [ ] Snap all of the switches into the plate.
- [ ] Double check that the four switches with the trimmed legs are positioned directly over the controller boards.
- [ ] It is best to install all of the switches into the plate before soldering. Once you start soldering, it becomes very difficult to make sure that all of the switches are fully pressed into the plate.
- [ ] If you are using Mill-max hot-swap sockets, solder them into the PCB now.
- [ ] Place the plate + switch assembly onto the PCB.
- [ ] Double check that all of the switch legs fit into their respective holes in the PCB, and have not been bent out of place.
- [ ] Solder all of the switches in place.

 

## Batteries
- [ ] For **wired builds**, skip this section
- [ ] For **wireless builds**, place a battery into the battery cutout labeled **BT1** in the **QWERT-hand** half of the PCB and tape it in place.
![Battery placement](/images/build/battery_placement.jpg)
- [ ] Solder the black wire to the PCB pad marked -. Then solder the red wire to the PCB pad marked +
![Solder batteries](/images/build/battery_solder.jpg)
- [ ] For **split builds**, repeat the process of securing and soldering a battery into the cutout labeled **BT3** in the **HJKL-hand** half of the PCB.
- [ ] (Optional) if you want extra battery life, you can add additional batteries to battery bays **BT2** and **BT4**.

 

## Controller boards
- [ ] Place a controller board onto the header pins of the **QWERT-hand** half of the PCB, with the controller board components facing the PCB.
- [ ] Double check that the controller boards have all of their components facing the PCB, with the smooth side of the controller board facing the table.
- [ ] Double check that there are two through holes on the controller boards opposite the USB port that do NOT have header pins in them.
![Empty through-holes](/images/build/empty_holes.jpg)
- [ ] Solder the controller boards in place.
- [ ] Trim the header pins flush with the controller boards.

 

## Final assembly
- [ ] (Optional) install the plastic case around the PCB, being careful to slip it around the reset switch and controller board.
- [ ] Screw the bases in place. Do not over tighten the screws, or the keyboard may bend and not sit flat.
- [ ] Apply anti-slip feet.
![Foot location](/images/build/foot_locations.jpg)



## Firmware

See the [Firmware Guide](/BuildGuide/FirmwareGuide.md)
