# PancakeXXL keyboard

![Static Badge](https://img.shields.io/badge/current_vesrion-1.0?labelColor=green)


This 40% is made in the idea of a little keyboard easy to travel with is little format and is 3d printed case to be lightweight.
This keyboard is made QMK and work with VIAL to make it customisable by everyone !

## Special thanks
I made it integrally but I take for inspiration for the layout the [Tanuki](https://github.com/SethSenpai/Tanuki) and get help from the [HLB team](https://github.com/H3lli0n/HLB-Projects) for some aspect of the keyboard (especially thanks to Please to help me with the PCB part and Hellion to help me with the case and firmware problems)

---
# Layout
Like say earlier I took inspiration of the Tanuki for the layout, but modify the last row by making it with a center Fn and not on the side, I also make it compatible with a 7u option.
To use the 7u layout you gonna need a special plate in the [plate and case directory](/plate_and_case/) who's using clip-in 7u stab (using 7u screw-in stab would have caused overlapping issues with switches) and activate the option on vial in the Layout tab
 ## Layout 2x2u and 7u
![Layout 2x2u](/kle/pancake%202u.png)
![Layout 7u](/kle/pancake%207u.png)
With the 2x2u you have an hold mod to use the up and down layer, you can customise it if you prefer to don't have it.

---
# QMK
The keyboard is made with a RP2040 MCU from rasbperry pi integrated on the PCB itself. This is a powerful MCU capable of a lot of thing like using QMK and by extension the VIAL application for easy modification of the keyboard.

---