# Creality Ender 6

# boxing
* Missing side panel. Left panel was missing fromt he box.
* Knife blade cut on front door. Where they put the handle on, there is a nasty cut.
* Chip in touchscreen. 


# Build
* Really easy. No missing screws etc, tools supplied worked well.
* My 6 year old assembled most of it from the paper instructions
* The step about plugging in the wires wasn't too clear, so had to do that when the panel was on.

* Getting the screws in on the filament sensor and the extruder was not easy
* Corner brackets was a bit rubiks cube. They are fiddly to get on.
* Getting the hotend cabling trunk into the clips was not only hard but drew actual blood
* Use the online instructions! The paper ones should not exist.
* 1:30hr build time


# Initial thoughts.
* It's quite big. Especially compared to the effective print size
* Well made, very solid
* CoreXY was calibrated well, when measured it was < 0.1mm out.
* Well thought out design
* It isn't quiet. The hotend fan is noisy. really noisy. Everything else is good
* The supplied firmware is clunky and a bit annoying to use.
 - will flash stock Marlin
* it is fast and can maintain decent prints at high speed. (160mm/s and 80mm/s walls is fine)

# Print test
Bed levelling was ok, but was unaligned quickly. It sems to vibrate itself out of alignment. Tightening all levelling screws down by 2mm stopped this

* Had to really screw the z-sensor pillar in tight to stop it moving while printing
* Heated bed is underwhelming and was reasonly fast. 25-60deg in about 4 minutes
* Hotend is the usual affair, functional but not special.
* I tested the supplied image on the SD card "gou". It's clearly not for this machine as it is slow to print. It did complete in a reasonable amount of time at 450% speed.
* At very high speed there is a tiny amount of bed wobble. It doesn't seem to impact prints too much
* Bed adhesion was ok, but my previous hot swappable IKEA glass panels were way stickier, if less stable under heating.

# Quality
* Print quality is good. Actually really quite impressive given the price.
* The strong mechanism really lets you crank the speed. 

* PLA and ABS work fine, no retration problems.
* ABS was only ok because of the non-enclosed lid. But the new top cover whenit comes out.
* Feeding the bowden was really easy

# Bed

Good strong rough finished glass. Does not flex in the heat. Sandpapers the nozzle when you don't level the bed properly!

Adhesion was Rocky at first. The supplied PLA is junk, so get better filament ready.

Adhesion with a big brim was fine. Thin models needed the bed to be cranked to more than 50

Temperature (all measurements 20mm from edge)

* The measured vs displayed is quite close. measured 57c at set 60c
* Heating is even except for the extreme edges of the bed. The measured was delta of -5c in the front left corner
* The hottest I got it was 100c. That took 10 minutes


# Software
Their slicer is functional but has many cura features stripped. Weird.


# Thing I have noticed while using the machine
* Default beep is LOUD. WHY!
* I have the machine set reasonably low on a bench. using the touchscreen at an angle from above can lead to you pressing the wrong thing. I miss the jog wheel.
* You need a JST to JST cable for bltouch. There are some vids on youtube of hacking some cables together.
* The UI goes from Chinese script to english when the change screen. Yeah.
* The UI is missing key functionality, such as flow rate, estep calibration etc.

Gripes
The z stage can start to slowly slide down once a print has finished. The z-stepper switches off, and a heavy print and the arch nemesis gravity duke it out. It is weird, annoying and slightly concerning watching your large print hit the deck. Tightening the eccentric z screws helped a lot, but this still happens.

A sub gripe being I use that space below as a cupboard/filament store.If this drops to the bottom, the first thing the printer does on init is lower the bed. CRUUUUNCH

Did I mention the fan on the hotend was loud?

I question the utility of the door and sides, especially as it has no top. It won't stop inquisitive fingers getting mangled in the mechanism from the top. Odd choice.

# Summary
For the £400 I paid, it is a decent machine. The software is poo, and I will write a guide of how I got marlin on there and cura profile working.

If you have the room, it is a decent machine. It lets you print fast, and still has good enough quality.

Going from an Ultimaker 2+ and an Ender 3 i'm impressed. The final print quality is comparible, even if the out of box experience is not.
With a few mods and tweaks, a very good purchase. I'm happy.
