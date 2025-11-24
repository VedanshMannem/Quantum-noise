Creating quantum noise:

This project exploits the breakdown region of a zener diode to hear the quantum tunneling of electrons. Zener diodes are doped very specifically to have a thin energy barrier so this allows for quantum tunneling when the voltage is very close to the rating of the diode. 

After building the circuit:
The speaker picked up lots of background, and the tunneling effect was too low to hear. An oscilloscope was used later to pick up lower frequencies, but there was lots of background on that as well. The tunneling was likely the noise on the oscillosope reading. 

<img width="1884" height="1025" alt="image" src="https://github.com/user-attachments/assets/50e70aa8-a76a-4293-9d7a-37a5887ca0ed" />

Project setup:
1) Use a DC power supply and wire that in series with a 5.1V zener diode
2) Connect the module's power source in parallel to the DC power supply
3) Plug in a resistor in series with the zener diode
4) connect the module (or the oscilloscope) in parallel with the zener diode

The GND-power and volume gnd are both specificed on the amazon link.

<img width="1177" height="463" alt="image" src="https://github.com/user-attachments/assets/47a8d861-70dd-4fe1-ac34-a34c83d1f0d9" />
Note: the J2 and 4-pin connectors combined act as the module (the oscilloscope would replace this component)

Pinout/setting up modules:
Module: GND-GND-IN-VCC (power ground, sound ground, sound, power)
Speaker: GND-IN
