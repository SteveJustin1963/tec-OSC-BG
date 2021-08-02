# tec-OSC




### issue TE 14-21; 
"This project is a crystal oscillator for the TEC. It turns the TEC into a fixed frequency computer in which each of the Machine Codes takes up a precise period of time. This means programs such as controller programs or timing programs will run for a precise time span and will not vary from one day to the next due to speed control adjustments."


### BG 
has shrunk this pcb down to the size of the 4049; "A drop in replacement for the 4049 IC. Board contains a sot-23 inverter for the keyboard interrupt and an 4mhz xtal oscillator soldered to a 16pin carrier board. This board is a requirement for the later TEC firmware (JMON, LCD etc) and increases the clock speed from a few hundred khz to 4mhz.
Includes standard pin header for direct soldering. If you intend to use an IC socket, you will need to source machined pin headers as to not stretch the IC socket contacts. "




### other ideas..

KS, the tec-1e, a selectable values and a VCO option exists as well. I would also like to add a single stepper version with bus LEDS for debugging.

![](https://github.com/SteveJustin1963/tec-OSC/blob/master/pics/1e%20proposed%20clock%20cct.jpg)



