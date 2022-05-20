# NES-Power-Board
A PCB that will fit in place of the stock NES frontloader's RF module.   (Complete Stand-Alone Drop In)
***
This Fork is from mspinksosu and takes his original design and fixes the composite video and mono sound
I also have another repository that has my complete redesign of the NES Power Module to help remove EMI and Noise.

My Redesigned NES Power Module Project - https://github.com/ShawMerlin/NES-Power-Module-Redesign

Original Project - https://github.com/mspinksosu/NES-Power-Board

# Improvements in Version D (Current)
- Removed the components that are used for RF since we are not utilizing that here.
- Moved the Large C1 Capacitor over a bit as the NES Shield was hitting it.
- Changed the Power LED from Stby Power to Power On.
- Increased Hole Padding for easier Soldering.
- Changed C3 & C8 Capacitors to Aluminum Organic Polymer Capacitors that are 8mm tall instead 11mm.

# Improvements in Version C
- Converted all SMD parts to through hole components (easier for novice soldering and matches the time period)
- Fixed the Composite Video Circuit using 2SA1015 & 2SC1740 Transistors.
- Routed all Mono Sound to the RCA_Audio (Red) Jack.  This jack is Mono for Internal or Right for External.
- Labelled the pins on the Multi-out Header for easier tinkering.
- Turned the 0 Ohm Resistor pads into quick solder pads.
- Labelled the RCA Jump section to show in and out signals.
- Changed the RCA_RF Jack to be Composite Video Only and added a second board that does 9 Pin Genesis Port 2 output.
- Added a 2 way jumper section for RCA_Video to switch between Composite Video and Left Audio.
- Changed the thickness of the font for easier reading.
- Added Capacitor, Resistor and Diode Values on the silkscreen for easy reference.
- Added a Power LED and LED Resistor, both are SMD 0805 and are optional to use.
- Added the Breakout pads for Ext Composite Video, Left and Right Channel Audio.

Project is Open Sourced with a MIT License. It can be edited, changed and sold at your own discretion.  
Please link back here if this helps you with your own project.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=97YFBJX4NXA8W)


**-- Gerber Viewer --**

![image](https://user-images.githubusercontent.com/70423454/157851385-621849d3-6b59-41b4-95cc-d1c1de20b542.png)


![image](https://user-images.githubusercontent.com/70423454/155845263-13174411-8a89-49a9-94dc-73f4287c7ad0.png)


![image](https://user-images.githubusercontent.com/70423454/155845290-7f2093ba-6e6d-428e-b230-7c98344ba051.png)
