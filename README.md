# Ender3V2-modifications
Mods of my Ender 3 V2 with .blend and .STL files
## Backing up .blend files
This repo is made for me to publicly upload my mods and methods I used for creating my own modifications.
## Why and what?
Personal backup, and helping myself to remember what tools I used and what I have done to make my ENDER 3V2 personal without any CAD background.
I'm trying to be crystal clear, open and link any of my mods that I remixed or modified. Not trying to break any rules as great as possible.
## Blender? Really?

- No CAD experience
- Blender usage is casual and can't say I am professional or experienced
- I'm "stupid" that I didn't taught myself CAD or other softwares, because it'd helped me
- Blender is "good" to mod premade STL files
I used a lot of tools from in-software tools and "un-official" ones. Listed:
- [CAD Sketcher](https://www.cadsketcher.com/) is lifesaving mod
- [QuickSnap](https://github.com/JulienHeijmans/quicksnap) from GitHub is great tool to help connecting pieces together
- [BlendShell](https://github.com/oormicreations/BlendShell) tool is in testing. Trying to make Ducts or something with this tool
- [CAD Transform for blender](https://blender-archipack.gumroad.com/l/nQVcS) is new tool yet to be tested.
- Precision Drawing Tools. Measuring Vector - Vector distances.
- 3D-Print Toolbox. Exporting STL easy way.
- LoopTools
- tinyCAD mesh tools
- Bool Tool (best)

# Example of ugly(really ugly) interface of mod(s)
If you are professional CAD user. It's not safe for work or life for you.
![Screenshot](https://github.com/SaKaarle/Ender3V2-modifications/blob/main/pictures/GitHub%20ugly%20mod.PNG?raw=true)

![CAD-Sketcher screenshot](https://github.com/SaKaarle/Ender3V2-modifications/blob/main/pictures/GitHub_BLtouch.PNG?raw=true)
CAD sketcher example of BLTouch mod (to support my stupid V6 heatblock and Slice Engineering's bi-metal heatbreak)

No excuses. It works and it works for me. Sharp eyes can see what this copies and what I have done. Hero Me Gen duct support for MiniMeV4 duct. Duct that is glued to extruder holder that has BLTouch support.
And in the behind is Linear Rail mod that I found in Printables and I added few mods and screwholes. Better / more material for belt and different adapter to add my "own" duct to the carriage. My mod supports BMS and CR Stock hotend.

Why I created this demon? Simply just I wanted to have creative freedom and some personality. Oversimplifying things is best I can do and what I want to do. Many available mods are TOO complicated. Too messy and not so simple to build or just outright too simple and causing headaches. I wish I could give examples and more explanations.

## So no mods that you'd like to have?
Yes. Why invent a wheel when someone already did that?
Also my printer went from stock headache machine to modded less headache machine. In the middle of modding my printer, I wanted to create `do it yourself as much as possible` printer. But obviously some parts cannot be printed and sometimes I learned from the hardway what and how to do things.

I started to make my own "duct" mod. Slice Engineering Copperhead heatbreak has weird dimensions. Too long and couldn't get cooling correctly. I tried to mod MiniME V4 and it was stupid waste of time. Then I mod some other duct that had modular mod that could lower it just a bit. It wasn't great enought and I started to search more solutions. I stumbled on Hero Me Gen duct.

## Why I didn't just printed Hero Me Gen with PETG and used heat inserts?

I didn't want to? As I mentioned before I learned things hardway usually and I wanted to create something that fits for me. And not gonna lie, Hero Me Gen is great design but I wanted to create duct with my own touch. But not having CAD skills made it harder. So bit of copy paste, loved the duct and hotend cooler design of MiniMe V4 and I fused them (literally) together. It's a monster and I guess I'm proud of my creation.

My currend DUCT mod isn't fully presenting my vision. I want to add some kind of modular adapter to Extruders. Currently Orbiter V2.0 is only option. Or Bowder setup with extra plastic printed.

## What else? What have I done?
List of mods that are edited to my flavour.
- X-axis cover (Destroyed my M3 x 40mm screws. Had to create M3 x 30mm screw mod. Then I added limit switch mod for Linear Mod carriage)
- X-axis linear rail carriage.
- Dual Z-axis to fit washers and better support for Z-axis motor. Coupler was hitting the original part.
- Y-axis motor holder. Was hitting bed tensioner screws. It needs to be modded / replaced.
- Y-axis drilling helpper. Holes for MGN12 linear rail. It needs changes and I have to create mod that supports Y-axis belt better and make it more straight.

These are just top of my head what I remember, but I'll create better list of parts and mods.

## Mods in action

![X-axis](https://github.com/SaKaarle/Ender3V2-modifications/blob/main/pictures/photo1686598149(4).jpeg?raw=true)
Carriage looks familiar as Hero Me Gen. No surprises there.

![X-axis](https://github.com/SaKaarle/Ender3V2-modifications/blob/main/pictures/photo1686598149(3).jpeg?raw=true)
Cable management is garbage and atleasted tried something. It's the modded version with Linear Rail support. 

![Z-axis](https://github.com/SaKaarle/Ender3V2-modifications/blob/main/pictures/photo1686598149(1).jpeg?raw=true)
Z-axis Dual Axis support. Bad picture, but it works for dual motor setup. Had to mod it so it wouldn't hit the coupler on the motor.


![Y-axis](https://github.com/SaKaarle/Ender3V2-modifications/blob/main/pictures/photo1686598149(2).jpeg?raw=true)
Y-axis is modded. Used open-sourced Y bed part from GitHub and cut it. Added holes for MGN12 and drilled the metal part. Attached to Y axis and it's WORK IN PROGRESS. Why?
- Support for belt needs to be created. Straighten the belt by creating cut outs from the "drill helpper" part. It has places for belts from original, so just cutting it from original POM Wheel holes and add height about 2mm and it supports the belt.
- "Rinkula.stl" part is for Y axis stop sensor. Simple solution but could be better.
