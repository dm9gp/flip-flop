# astable
# multivibrator
# fritzing 
# PCB


Astable Multivibrator Circuit PCB.
View the attached images or 
open .fzz file in "Fritzing" from https://fritzing.org/ to view the schematics, inspect or modify the circuit.

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

P.S.
Although Flip-Flop would really be another name for a Bistable Multivibrator, it seems widespreadly used as a synonym for the Astable Multivibrator.

"Multivibrator" because it outputs waveforms that are rich in harmonics.

This work is dedicated to the public domain. 




