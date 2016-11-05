# BlackMagic Atem Midi Control 
This set of Macros for the JustMacros host software allows to use a common Midi-Controller to implement a hardware shading for cameras which can be controlled through the BlackMagic ATEM software. In the test case a AKAI LPD8 was used. The buttons were used to switch a camera to an AUX-channel, the 8 knobs were used to adjust iris and black levels for four cameras.

## Prepare
JustMacros allows to control only camera 4 in the free version. To use this scripts you need to get a license.
Make sure JustMacros is configured right and has a connection to your ATEM Mixer. 

## Setup
Find out the Midi Channel and CC Numbers for the controller knobs/buttons you want to use. Add this information in the HDM_MIDI_PROCESSOR file.
Add the number of your controlling midi device in START and execute. 