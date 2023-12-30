# astable
# multivibrator
# fritzing 
# PCB


Astable Multivibrator Circuit PCB.
See it in action in this video: https://www.youtube.com/watch?v=wZovhqsylgY

Although Flip-Flop would really be another name for a Bistable Multivibrator, it seems widespreadly used as a synonym for the Astable Multivibrator.
"Multivibrator" because it outputs waveforms that are rich in harmonics.


GET STARTED:

Review the attached images or 
open .fzz file in "Fritzing" from https://fritzing.org/.

To make the circuit, you will need a Breadboard or print the PCB file (in the latest version) 
or have the PCB printed for you, the PCB file here is in "Fritzing" format .fzz. 
You can open it in "Fritzing" (https://fritzing.org/) to first check it, 
modify it and then have it printed by a PCB printing service of your choice such as AISLER (https://aisler.net/) if you wish.


PARTS REQUIRED:

Parts required to make the flip-flop circuit are:

	2x LEDs;
	2x 10 μF capacitors;
	2x 470 Ohm resitors;
	2x 100 kOhm resistors;
	2x BC547 transistors;
	(3x Jumpers are optional);
	(1x Screw Terminal with 2 pins is optional);

you may also want to print the PCB by yourself or have the circuit board printed professionally for you, 
for example by uploading the .fzz file to https://aisler.net/


THE CIRCUIT:

Q1 and Q2 are the BC547 transitor.
I haven't tried the 2N3904 or 2N2222A transistors here. 
Note the transistor's pin layout before trying a different one.

The blinking interval is determined by the values of the two 100kOhm resistors and that of the two capacitors as per the formula: T = R x C

Example values:

	100 kOhm x 10 μF = 1.0s;
	 10 kOhm x 10 μF = 0.1s;
  	100 kOhm x  1 μF = 0.1s;

you can choose LEDs of any color.

Jumpers are optional. Use them for picking up the square waves and displaying them on an oscilloscope.


LICENSE:

This work is dedicated to the public domain. 




