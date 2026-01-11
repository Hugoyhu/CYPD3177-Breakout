# CYPD3177-Breakout
Small 2-layer fixed USB-C PD Power Sink with CYPD3177. Breadboard friendly design, and can easily be assembled on a hot plate if you have a stencil.

The board provides a fixed output of 9V1A using the CYPD3177 chipset. It's highly flexible, allowing USB-C Charging up to 15W and USB-C PD up to 100W. Unlike many other chips available, it does not require any firmware nor flashing, and power settings are configured with pullup and pulldown resistors. This board is set to 9V @ 1A, to ensure maximum compatibility with most PD-capable bricks. It's very compact, measuring less than 22x32mm with breadboard-friendly mounting, an affordable 2-layer design, and single side SMD component placement. 

![KiCAD Render of PD Board](https://github.com/Hugoyhu/CYPD3177-Breakout/blob/main/USBCDecoyBoard.jpg)

![Schematic](https://github.com/Hugoyhu/CYPD3177-Breakout/blob/main/CYPD3177%20Breakout%20Schematic.png)

The board is more flexible than off-the-shelf PD boards based on chinese chipsets. They usually only have four pins for mounting, but this board is more mechanically sturdy due to the opposing pins on either side of the board.

You can also modify the design to add switches to configure requested voltage/current during power-on.

*As a precaution: while this board is breadboard friendly, typical solderless breadboards are only rated up to _5V @ 1A_. Do _not_ use this on a solderless breadboard.*
Also, it's important to note the maximum current and voltage that parts on the board can tolerate. For example, if you are looking to adapt the design for a higher current setting, it may be worth considering alternative output connectors: standard 2.54mm headers are only rated for <3A typically. In addition, not all USB-C connectors are rated up to 5A, and not all passives are rated for high voltage tolerance. 
