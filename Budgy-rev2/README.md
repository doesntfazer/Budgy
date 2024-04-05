# Budgy
 Split 34 key keyboard powered by a raspberry pi pico and QMK

This keyboard is Diodeless. 

DO NOT DOWNLOAD OR PRINT REV 2. I have yet to do any testing. But I noticed a major flaw with the current design. The power supply voltage for the SK6812MINI-E that I am planning to use is 5v (or +3.7~+5.5), and the logic input is 3.3v. I would just use the 3v3 out. But in testing the SK6812MINI-E will not light up under such low power. 

I have added in a voltage divider using 10k + 30k resistor's in an attempt to fix this. This should provide Just enough power (3.75v) to the SK6812MINI-E supply voltage, and be withing the operating range (+-.5v) of the logic input. Although I believe that this fix might work, I don't think that this is the best solution to the problem. 

Another issue is that the VBUS on a rp2040 is directly connected to the 5v usb pin. Some issues can come from this, one being that the power coming from usb is not always consistant. If it doesn't output exactly 5v-5.05v, It will likely either not light, or not be within operating range of the logic input. 

I am going to put rev2 on the backburner for now. If anyone is interested in testing it out in it's current state let me know. But I don't know if I trust it.


Build guide coming soon. 
