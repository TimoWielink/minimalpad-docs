# Source: https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad

[![](https://cdn.prod.website-files.com/67a8fe2ace8968bc2e48ba6c/67e1d11760b87c017f2f77c9_Union.svg)](https://www.minimalmacropad.com/)

[Shop](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#) [Documentation](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#) [Support](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#) [Contact](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#) [Configurator](https://studio.minimalmacropad.com)

[Home](https://www.minimalmacropad.com/)  

/

Instructions

/

How to Assemble a MinimalPad

# How to Assemble a MinimalPad

On this page

#### **Parts**

The dumbpad I build has a couple of different configurations and thereby affecting the parts list. I went with the Oled version and one rotary encoder to have a knob for things like volume control or control sliders in Lightroom. You can buy a kit with the main components for this macropad [here](https://keebd.com/products/dumbpad-macropad-keyboard-kit) or source all the parts yourself I will show a quick parts list and then go into every part in depth. The main instructions and project can be found on [Github](https://github.com/imchipwood/dumbpad).

**1x Dumbpad PCB 
16x MX style keycaps 
16x MX switches (Preferred with placement pins) 
17 x 1n4148 diodes (thru hole) 
1 x Arduino Pro Micro 
1 x 0.91" 128X32 OLED Display 
1 x EC11 rotary encoder with pushbutton (7-pin) 
1 x 6mm tactile switch**

![Photo of a top view of a macropad, small keyboard](https://cdn.prod.website-files.com/67baa89df0cc6a61d57139f1/67fe36ebbdd0abbdcf5e3a50_6310b87253e99e571e249287_984A0049.jpeg)

**Switches:** you can choose what kind of MX style switches you want to use, desolder them from an old keyboard or buy a set online. I would recommend switches with the 2 pins on the bottom to have them straight on the PCB. 

‍**Arduino Pro Micro:** The brain of the macropad is this Arduino Pro micro, I have been looking for a Black version with USB-C but availability is low due to the shortage. I added some links for different versions here: [Europe,](https://nettigo.eu/products/arduino-pro-micro-clone-atmega32u4-5v-16mhz) [US](https://www.amazon.com/Teyleten-Robot-Bootloadered-Development-Microcontroller/dp/B08THVMQ46/ref=sr_1_3?crid=NUYPK5135T8Z&keywords=arduino+pro+micro&qid=1662040287&sprefix=arduino+pro+mciro%2Caps%2C163&sr=8-3) 

‍**Key Caps:** For keycaps, there is also such a wide variety of options. Take them from an old keyboard, or buy a keycap set. You will only need 16 keycaps, and I would recommend finding ones that are all the same height. 

‍**PCB:** If you order the PCB yourself you have some customization options. I wanted to add some logo to the Silkscreen of the PCB to make it a little more custom so I came up with a little DumbPad logo and added my name to the front. This will require some PCB modification, which is optional, the stock silkscreen works fine if you'd rather skip it.

#### **Diodes**

Solder the 17 diodes first, before anything else goes on the board. They're directional, so check the silkscreen for the band orientation on every single one. Diodes are small and easy to bridge, so take it slow and check continuity as you go if you have a multimeter handy.

#### **OLED Display and Rotary Encoder**

The 0.91" OLED and the EC11 rotary encoder both mount on the same side as the Pro Micro. Socket the display if you want the option to swap it later, otherwise solder it flush to the PCB. The encoder's pushbutton doubles as an extra input, wire it in before you close up the case.

#### **Reset Button**

The 6mm tactile switch is your reset button for flashing firmware. Mount it wherever the PCB breaks it out, usually a small hole on the underside or edge of the board.

#### **Soldering Order**

Work bottom to top: diodes, switches, then the taller components (Pro Micro, OLED, encoder, reset button) last. Doing it in this order keeps the board flat on the table for the fiddly, low-profile joints and saves the tall parts for when you don't need to fight gravity.

#### **Flash the Firmware**

Once everything's soldered, flash ZMK to the Pro Micro. See the Configure Your Keys guide for the ZMK Studio walkthrough, once you're up and running you'll be able to remap every key from the browser without touching the code again.

#### **Final Check**

Before you close up the case, plug it in and test every key and the encoder. Easier to fix a bad joint now than after it's screwed shut.

LINKS

[Features](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#) [Shop](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#) [Tutorials](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#) [Terms and Conditions](https://www.minimalmacropad.com/terms-conditions)

© 2026 Unbox Studio

DESIGNED AND BUILT IN AMSTERDAM

The minimalPad is was inspired from the DumbPad project from Imchimpwood 

Thank you for all the support 
‍

[![](https://cdn.prod.website-files.com/67a8fe2ace8968bc2e48ba6c/67ba97d7b21db79b34ae378a_mdi_github.png)](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#)

[![](https://cdn.prod.website-files.com/67a8fe2ace8968bc2e48ba6c/67ba97d7b21db79b34ae378a_mdi_github.png)](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#)

[![](https://cdn.prod.website-files.com/67a8fe2ace8968bc2e48ba6c/6a71e7759129090b6f8ba79b_prime_twitte1r.svg)](https://www.minimalmacropad.com/resources/how-to-build-a-minimalpad#)