# Ender3V2-modifications
Mods of my Ender 3 V2 with .blend and .STL files
## Backing up .blend files
This repo is made for me to publicly upload my mods and methods I used for creating my own modifications.
## Why and what?
Personal backup, and helping myself to remember what tools I used and what I have done to make my ENDER 3V2 personal without any CAD background.
I'm trying to be crystal clear, open and link any of my mods that I remixed or modified. Not trying to break any rules as great as possible.

## Blender? Really? NO PLEASE NO
### FreeCAD > Blender
  
Blender is good for simple mesh edits / remixes, but still. Wasting time on blender CAD Sketcher is not a good idea.
## What else? What have I done?

List of mods that are edited to my flavour.
- X-axis cover (Destroyed my M3 x 40mm screws. Had to create M3 x 30mm screw mod. Then I added limit switch mod for Linear Mod carriage)
- X-axis linear rail carriage.
- Dual Z-axis to fit washers and better support for Z-axis motor. Coupler was hitting the original part.
- Y-axis motor holder. Was hitting bed tensioner screws. It needs to be modded / replaced.
- Y-axis drilling helpper. Holes for MGN12 linear rail. It needs changes and I have to create mod that supports Y-axis belt better and make it more straight.
  
These are just top of my head what I remember, but I'll create better list of parts and mods.

## Required Modding
  
**X-axis:** It has had SOME mods and fixes. BLV set with [FrankEnstein](https://github.com/kevinakasam/FrankEnstein-Duct/tree/main) and modded base to fit screws and hold it together better on the X gantry / carriage.
X-axis only needs Motor holder / endswitch holder which would be better and for double shear support. Not necessary this last part but better than nothing.
  
**Y-axis:** Uses BLV base, but could use dual mgn rail system. Not sure if it's benefitting at all for acceleration results, but will see. Currently max y-axis acceleration is 5000, but I use 10000mm/s². Seams will show the high acceleration results.
Y-axis upgrade path is simple: Dual MGN rail. New bed heater system. New bed heater means = New PSU and silicon heater.
  
**Z-axis:** Dual leadscrew / BLV Z-axis. I could just use KevinAkaSam's Z-axis mod. Only needs printing the necessary parts.
Z-axis not necessarily needs upgrade, except the belted mod. 
  
**DUCT:** Yeah nothing really. FrankEnstein V2
  
**Extruder:** Orbiter V2.0 -> V2.5 upgrade done. Better quality? "yes". Worth it? I guess?
  
**Enclosure:** Needs filtering system
  
**Motherboard and Electronics:** GPIO pins, fans and new motherboard holder location and design. Led control from RPi 5 or from RPi Pico.
  
**Filament runout sensor:** Not installed
