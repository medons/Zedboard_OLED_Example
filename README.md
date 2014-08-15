Zedboard_OLED_Example
=====================

Modified PMOD OLED design to work better on Zedboard
Doesn't seem to work properly immediately after bit file download but resets properly.
The PMOD example kicking around has the display inverted in X and Y relative to the Zedboard.
This is fixed.  Also because of the inversion the code needs to deal with the 128x32 section of the controller's 128x64 memory.
This version initializes and scrolls the full memory contents.
