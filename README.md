# Orange Dark Terror mods

This file lists some possible mods to make on an Orange Dark Terror amplifier.

You should print the amp's schematic file for easier reference. I won't provide it since I don't know if it's copyrighted material, you should search for it yourself.

# WARNING / DISCLAIMER

These mods will totally void your amp's warranty and are given for reference only. There's also high voltages involved, that can kill yourself, burn your house and rape your cat.

I'm not responsible for anything that happens to you, to whatever belongs to you, or to anybody.

Therefor, these mods are strongly discouraged and you should stop reading this immediately :)

## Preamp conversion to OR15 / Rockerverb
The only difference with the Dark Terror's preamp is the 3-band EQ (instead of the Shape control).

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

Drill 2 new holes on the front panel for 2 more pots (around the Shape control hole).

Desolder the following components: 
* VR1 (Shape pot)
* C11 & C12 (100pF capacitors)
* R17, R18, R56 (56k, 15k, 4k7 resistors)

Build the new tone stack using the provided schematic (on a vero board, turret, whatever you like). You can reuse the 470pF caps you've desoldered: set them in parallel to replace the two 100pF in series (this will form a ~235pF cap that sounds fine).

* Connect the Tone Stack input to R15 / V2 pin 6.
* Connect the Tone Stack output to pin 3 of VR3 (Volume knob).

Enjoy your new EQ :)

## Natural channel (inspired by Orange Rocker 30)
In summary, we will use the first triode for preamplification, bypass the 3 following gain stages and the EQ, and connect back to the FX loop. A relay will be used for channel switching.

### Required parts
* 1x DPDT 5v relay
* 1x 1N4001 diode
* 1x stereo ISOLATED 6.5 jack
* 1x SPST toggle switch
* 1x bridge rectifier
* 1x 16v 470uF capacitor
* 1x 47R resistor
* 1x 33R resistor
* 1x 22uF 63V electrolytic capacitor
* 1x 22nF 400v film capacitor
* 1x 100pF 1kV film capacitor
* 1x A1M pot

### Howto

Remove PCB from the amp, drill 2 holes on the front panel: one for the Natural volume pot, one for the Channel switch.
Drill another hole on the back of the amp for the footswitch jack.

* Lift one terminal of the C2 capacitor (the one connected to V1 pin1 / R3)
* Lift one terminal of the R20 resistor (the one connected to ground)
* Replace C1 with the 22uF capacitor (beware of polarity !)
* Build the Natural volume control and the relay power supply,  using the provided schematic
* Wire everything up: switch, footswitch jack, relay, pots... lots of stuff to do, good luck !


## Footswitch
This builds the footswitch that toggles between the channels.

### Required parts
* 1x SPST latch footswitch
* 1x stereo ISOLATED 6.5 jack
* 1x 2.2K resistor
* 1x LED
* 1x enclosure

### Howto
Build everything by following the provided schematic.


