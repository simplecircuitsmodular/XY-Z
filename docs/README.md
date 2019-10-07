# XY-Z

#### [Overview](#overview) | [Design](#design)

### Overview

XY-Z is a 2d, 16 step sequencer. Each step is controlled by a separate potentiometer laid out in a 4x4 array. 2 inputs (X and Y) allow the user to cycle through rows and columns using trigger inputs.

### Design

The core of this module is the potentiometer array. Rows are selected using digital pins on an ATMega 328, and columns are selected using an analog multiplexer. The output is connected to an opamp buffer and varies form 0v-5vdc.

### Buy

I'll be updating this part soon with a link to buy PCBs on Reverb. For the time being you can email me to purchase development PCBs at a discount. These will be fully functional but have minor issues.
