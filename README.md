# flip-flop
# astable
# astable flip-flop
# fritzing 
# PCB


Astable Flip-Flop Circuit PCB.
Open in Fritzing to view the schematics, inspect or modifiy the circuit.

Parts required to make the flip-flop circuit are:

2x LEDs
2x 10 μF capacitors
2x 470 Ohm resitors
2x 100 kOhm resistors
2x BC547 transistors

You will also need print yourself or have the circuit board printed for you for a fee, 
for example by uploading the .fzz file to https://aisler.net/

Q1 and Q2 are the BC547 transitor.
Alternatilvy the equivalent 2N2222A can be used, it has slightly more gain than the BC547.
However, the 2N2222A will have to be mounted rotated 180 degrees as it's pin out is the other way round than that of the BC547.

The blinking interval is determined by the values of the two 100kOhm resistors and that of the two capacitors as per the formula: T = R x C

Example values:
100 kOhm x 10 μF = 1.0s
 10 kOhm x 10 μF = 0.1s
100 kOhm x  1 μF = 0.1s

You can choose LEDs of any color.






