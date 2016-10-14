# Orange Dark Terror mods

This file lists some possible mods to make on an Orange Dark Terror amplifier.

You should print the amp's schematic file for easier reference. I won't provide it since I don't know if it's copyrighted material, you should search for it yourself.

# WARNING / DISCLAIMER

These mods will totally void your amp's warranty and are given for reference only. There's also high voltages involved, that can kill yourself, burn your house and rape your cat.

I'm not responsible for anything that happens to you, to whatever belongs to you, or to anybody.

In summary, these mods are strongly discouraged and you should stop reading this :)

## Preamp conversion to OR15 / Rockerverb
Their only difference with the Dark Terror preamp is the 3-band EQ. Let's build it and install it !

### Required parts
* 1x A500k pot (bass)
* 1x B25k pot (mids)
* 1x B250k pot (treble)
* 1x 47k resistor

### Optional parts
Those parts will be reused once desoldered from the PCB, but you can buy new ones if you want.
* 2x 22nF 400V film capacitor
* 2x 470pF 1kV film capacitor

### Howto
Check that all caps are discharged, and remove the PCB from the amp.

Drill 2 new holes for 2 more pots (around the Shape control hole).

Desolder the following components: 
* VR1 (Shape pot)
* C11 & C12 (100pF capacitors)
* R17, R18, R56 (56k, 15k, 4k7 resistors)

Build the new tone stack using the provided schematic (on a vero board, turret, whatever you like). You can reuse the 470pF caps you've desoldered: set them in parallel to replace the two 100pF in series (this will form a ~235pF cap that sounds fine).

Connect the Tone Stack input to R15 / V2 pin 6.

Connect the Tone Stack output to pin 3 of VR3 (Volume knob).

Enjoy your new EQ :)

## Natural channel
