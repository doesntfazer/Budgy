# Budgy Keyboard

Budgy is a split 34 key keyboard powered by a Raspberry Pi Pico and diode-less.

### Builds:
![Budgy](https://i.imgur.com/2iLX4xt.jpg)  


[Build by: Jakob Edvarsson](https://github.com/JakobEdvardsson)
![Budgy](https://i.imgur.com/TFpg2NZ.jpeg)


## What you need to build a Budgy


| Component | Amount |
|--|--|
| Reversible Budgy PCB | x2 |
| Raspberry Pi Pico w/headers | x2 |
| Cherry Switches (5 pin recommended) | x34 |
| Keycaps | x34 |
| TRRS Cable | x1 |
| PJ-320A TRRS Jacks | x2 |
| Rubber Bumpers | x8 |


- Solder headers to both raspberry pi Pico's

- On the left hand board, solder the Raspberry Pi Pico facing up and to the rightmost set of pins. If you are still unsure reference the photo above.

- Like in the previous step above, on the right hand side of the board, solder the Pico to the rightmost set of pins. Use the photo for reference. 

- Solder the TRRS Jacks to the top of each side, again reference photo. 

- I recommended at this point, you test the board to make sure everything is functioning. Plug in each side of the board while holding down the reset pin on the top of the board. Drag and drop the UF2 files from [here.](https://github.com/doesntfazer/Keyboard-Dweebs-Firmware-repository/tree/main/VIAL-QMK/budgy) You need to do this on both boards.

- Connect the halves using a TRRS cable, and short each key using some tweezers or a piece of wire. These files use [Vial QMK. You can download this app and use it to configure your keyboard.](https://get.vial.today/download/)

- If everything is working correctly you can proceed to solder in all of the switches, add your keycaps, and put a rubber bumper in each corner on the bottom of each pcb, then start typing away.

### Firmware

Here are links to a couple of different firmware available for the Budgy keyboard. 

- VIAL [here.](https://github.com/doesntfazer/Keyboard-Dweebs-Firmware-repository/tree/main/VIAL-QMK/budgy)
- KMK - [here.](https://github.com/KMKfw/kmk_firmware/tree/master/boards/budgy)
- QMK - [here.](https://github.com/qmk/qmk_firmware/tree/master/keyboards/budgy)



#### Some things to note. 
- It's okay if you don't have 5 pin Cherry switches. If you bend one of the pins on the switch a bit, they should hold in place when you flip the board over.
