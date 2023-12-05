# CYPD3177-Breakout
Small 2-layer fixed USB-C PD Power Sink with CYPD3177. Breadboard friendly design, and can easily be assembled on a hot plate if you have a stencil.

The board provides a fixed output of 9V1A using the CYPD3177 chipset. It's highly flexible, allowing USB-C Charging up to 15W and USB-C PD up to 100W. Unlike many other chips available, it does not require any firmware nor flashing, and power settings are configured with pullup and pulldown resistors. This board is set to 9V @ 1A, to ensure maximum compatibility with most PD-capable bricks. It's very compact, measuring less than 22x32mm with breadboard-friendly mounting, an affordable 2-layer design, and single side SMD component placement. 

![KiCAD Render of PD Board](https://cloud-e45xlmam7-hack-club-bot.vercel.app/05m8a0347_dxo.jpg)

The board is more flexible than off-the-shelf PD boards based on chinese chipsets. They usually only have four pins for mounting, but this board is more mechanically sturdy due to the opposing pins on either side of the board.

You can also modify the design to add switches to configure requested voltage/current during power-on.
