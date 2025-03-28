<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

the top output pin represents A (most significant bit), while the bottom one represents B(less significant bit) in a 2 bit state.
The previous states are ran through calculated logic, which is then ran through a D-flip flop to go to next states.
The output of the next states also go through hard-code logic to light up lights in a sequence from green -> yellow -> red -> green.

## How to test

Let the clock run and observe the sequence of lights, or step through the clock one at a time and observe the sequence of lights.

## External hardware

Three LEDs.
