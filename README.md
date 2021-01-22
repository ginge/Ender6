# Ender 6
Creality Ender 6 notes
Barry Carter <barry.carter@gmail.com>

Machine teardown/info

# General Resources
* Forum - https://forum.creality.com/category/20/ender-6
* Reddit - https://www.reddit.com/r/ender6/
* Facegroup group too (private)

# General Notes
* EEPROM is stored on the SD card. If you change the SD, make sure to copy it over

# LCD:
DWIN DMT48270C043_06WT - https://www.aliexpress.com/item/1005001962148737.html?spm=2114.12010612.8148356.23.51f46c08lNXdFA
DGUS mode. Mostly compatible with Ender 5 plus commands.
No LCD Source available.

# LCD Resources
* http://www.ampdisplay.com/documents/pdf/DGUS%20Development%20Guide_V3.1.0.pdf
* https://github.com/CR6Community/CR-6-touchscreen <- Re-purposeable to new orientation and layout

# BL Touch
* Just buy a plain one, no kit required. Ender 6 has mounting brackets
* required 1m of ribbon cable & conector. Get extension.
* Ender 6 has a Molex Picoblade 1.25mm pitch connector. - https://www.ebay.co.uk/itm/Molex-PicoBlade-1-25-micro-connector-2-3-4-5-6-Pin-leads-100mm-28-AWG-wire-PCB/232695637343?hash=item362dbda55f:g:vHoAAOSwWmNapoY1
* USB connector is broken out with an extension cable
* Levelling: z-Offset problem:
  * When levelled and aux levelling is done PRESS HOME TWICE. This saves the EEPROM.

# Firmware
* Marlin confs - https://github.com/MarlinFirmware/Configurations/tree/import-2.0.x/config/examples/Creality/Ender-6?fbclid=IwAR0_o2rPAgZGxDpl3_Vk7JpqURJPMX700ijOMignPIvyoPEuqtwHmsnmPXE

# Main board
* Pinout - https://docs.google.com/spreadsheets/d/1DYhh9fwLnvZzuNvMoBen9Dl68KN-4TWkbO94lJ4iwe4/edit#gid=0

# Cura 4.8 config
* Copy all files relating to ender from their slicer to Cura.
* I was using flatpak so added them to ~/.cura folders
* Info from here - https://forum.creality.com/topic/1172/creality-ender-6-cura-slicer-profile/3

# To Do
* Z axis leadscrew  replace with finer pitch
* better filament roller support that doesn't rub
* extension for the filment sensor to align it with the feeder
* a clip to hold the bowden so it doesnt dnag on the blue connector
* jog wheel
* better PSU

# Addons
* Fan Shroud - https://www.thingiverse.com/thing:4698226
* x/y Chain - https://www.thingiverse.com/thing:4731935
* cable trunk Strain relief - https://www.thingiverse.com/thing:4690585
* head strain relief - https://www.thingiverse.com/thing:4695820
* filament bearing holder - https://www.thingiverse.com/thing:4659228
* Orion quiet fan - https://www.digikey.com/en/products/detail/orion-fans/OD4010-24HB/2621113?fbclid=IwAR3BVuU-d9iysA3kckwqtj83w1VciwGTxTPJBJn7Hn-ydM5ehei6z_Pmev0


# LCD firmware hacking
* https://github.com/b-pub/dwin-ico-tools

* Creality CR6SE firmware dwin code ported to ender 6 (Y)  - mostly working. 
* re-position all ui elements for correct orientation (20%)
* Sniff/map all stock LCD commands (N)
* Able to use stock LCD (Kinda)
* DWIN code applied to lcd (N)

Issues:
* There are some commands that are not mapped
* you get stuck in screens

