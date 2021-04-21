# POWpedal
The design goal of this project is to test Germanium transistors' clipping charactaristics in a guitar pedal that adjusts amplitude and bias for both hard and soft clipping in the same tone.

## Simulations
These simulations use a SPICE-like tool called TINA-TI available for download here: https://www.ti.com/tool/TINA-TI

### TODO
Find the operating conditions (Beta [aka hFE] of transistors and amplitude of guitar pickups) and make sure the gain is adjustable so the quietest combo can still distort and the loudest can play clean

https://github.com/MiataMike/POWpedal/wiki/Transistor-information
http://tomsguitarprojects.blogspot.com/2014/12/electric-guitar-output-voltage-levels.html

## Scope change
Add an oscilloscope using comparators, shift register, an LED driver and an 8x16 LED display (or cooler). An RC oscillator can provide a tunable temporal sampling window (like ms/div). This will be useful for setting the bias and gain, since it will clip unless you have *both* at the right levels. I'll add a bypass so it'll display the upstream signal and act as a cable driver
