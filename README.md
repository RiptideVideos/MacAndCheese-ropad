# MacAndCheese-ropad

The MacAndCheese-ropad is a 4x4 macropad running on a Xiao RP2040. All 16 of the macropad buttons are fully customizable with the QMK firmware or other firmware that the RP2040 supports. 

The MacAndCheese-ropad is intended to be used for daily tasks like copying, pasting, taking a screenshot, ect. THe buttons can also be used as extra function buttons (up to 8 on MacOS and 12 on Windows). Using more adanced software, the buttons could be tied to app specific functions or really anything that can be run on a computer.

> Learn more about button use for QMK here: https://docs.qmk.fm/keycodes_basic

I built the MacAndCheese-ropad because I thought it would be a fun but not to hard challage, it has been just as expected. While some of it was smooth sailing a lot was feeling like I was in the dark on many things, however I was able to pull through and continue the project. I hope this macropad makes me more productive and proud to have somthing I worked hard on be usful to me.

## The Design:

The design features 16 square keys layed out in a 4x4 grid.
- The keys are Cherry MX switches.
- There is a empty space right of the keys which holds the Xiao RP2040.
 
<img width="1694" height="840" alt="Screenshot 2026-03-14 at 8 59 48 AM" src="https://github.com/user-attachments/assets/8a566c84-eac2-4db5-987d-4f260491b56b" />

## The PCB:

The PCB uses a matrix to support all 16 keys, a photo of the PCB in KiCad is below:

<img width="1326" height="1029" alt="Screenshot 2026-03-20 at 3 21 23 PM" src="https://github.com/user-attachments/assets/6c4d3e9b-e5aa-4013-a205-b5bf3206bea1" />

## The Firmware

The MacAndCheese-ropad uses the QMK firmware to give the keys uses, currentally the firmware is set up with 2 layers of keys. (The exact set up is in the repo).

## Bill of Materials

| Item | Qty | Source |
|------|-----|--------|
| Seeed XIAO RP2040 | 1 | Provided by Hackpad |
| 1N4148 Diodes | 16 | Provided by Hackpad |
| Cherry MX Switches | 16 | Provided by Hackpad |
| DSA Keycaps | 16 | Provided by Hackpad |
