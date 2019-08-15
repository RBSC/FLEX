--------------------------------------------
MSX FLEX Slot Extender v1.1
Copyright (c) 2019 RBSC
--------------------------------------------
Last updated: June 14, 2019
--------------------------------------------

WARNING! To avoid damage to FLEX and your MSX computer never insert or remove the extender when a computer is powered on!

WARNING! The extender is not designed to supply the power to more than one cartridge. If a slot expander is connected to
FLEX, it must have its own power supply!

IMPORTANT NOTE! The RBSC can not be sure that FLEX will work flawlessly with all available MSX hardware. See the "Known
issues" section below for more info.


About
-----

The device is the simple extender of the 50-pin MSX slot or MSX bus. It consists of 3 parts - the cartridge part, the 50-pin
slot extender and the 60-pin slot extender modules. The modules are connected to each other with the 50-wire ribbon cable
that is approximately 30cm long. 

The data lines have 100 Ohm resistors installed to compensate for the wave impedance of the ribbon cable. A few 100nf ceramic
capacitors are installed between the +5v and ground signals to remove the possible interferences in power lines.

The FLEX is designed to be used with one cartridge or one 60-pin module at a time. The cartridge board has 2 placeholders
for 50-pin ribbon cable connectors and this allows to attach 2 cables at the same time and to connect the 50 and 60-pin
extenders simultaneously. But those must never have 2 devices inserted at the same time! Doing this may create conflicts and
cause a power surge!


Cases
-----

The models of the cases and their covers must be printed with 0.2mm layer height and with their open sides facing upwards. The
pin is printed vertically and then is glued into the 50-pin extender's case. Brim is recommended for all models. The supports
must be at 20%. The infill must be not lower than 25%. The sturdy PLA is recommended for the cases.

The cartridge module's cover is attached to its case with 2 conical head screws (2.0mm x 12.0mm). The extender modules' covers
are attached to their cases with 4 conical head screws (3.0mm x 20.0mm). Shorter and longer screws must not be used. The screws
could be bought in any decent hardware store.


Engraving
---------

When the cases are printed in black plastic, the "MSX FLEX" text will not be visible on the top of the cases. In this case we
recommend to do laser engraving. The images for laser engraving are attached. The recommended width of the engraving should
not exceed 60mm. The recommended depth of engraving should be 0.1mm. See the "ready_engraved.jpg" picture for the reference.

The engraving must not be done in the areas where the "MSX FLEX" test is present, see the "ready.jpg" image for the reference.
Engraving in the areas where the text is located will result in damaging the thin layer of plastic above the letters and ruin
the good look of the case!


Notes
-----

The boards inside the cartridge case and the 60-pin extender case may wobble a bit. This was designed like that on purpose.
Please do not try to fix the boards firmly. Such wobbling makes the insertion and removal of the cables and devices safer.

Please note that the ribbon cable's connector is made out of plastic, so it's relatively fragile. When pulling the cable out
of the cartridge module please be gentle and do not pull too hard. When removing the cable please try to avoid bending of
the pins on the cartridge board. If the pins are bent, try to carefully straighten them with pliers before inserting the
cable.

The key on the flat ribbon's 50-pin connector may not be compatible with MSX bus expansion connectors of certain MSX computers.
So if you are connecting FLEX to the expansion bus connector, please make sure that the cable's connector is properly aligned.
In some cases the key will need to be removed for the proper alignment, however we advise against it. Be warned, that incorrect
orientation of the FLEX connector may cause severe damage to your MSX computer!

The cases of FLEX modules are normally made out of PLA plastic that is rather fragile. So when disassembling and reassembling
the cases please do not tighten the screws too much or you risk to damage the threads inside the screw holes. If that happens,
fixing the problem would require inserting a few thin threads of PLA into the hole before using the screw.

The SW1 and SW2 pins on the extender modules are not connected to each other. So on MSXs that require those pins to be
shortened in order to enable the power supply, inserting the FLEX with any of its slot extenders will not power-up the computer.
Only when a cartridge or a side slot module is inserted into one of the extender modules, the computer will power-up.


Known issues
------------

The FLEX may not work 100% reliably with all available MSX hardware. We've tested it on Yamaha, Philips, Panasonic, Sanyo and
Toshiba computers and there were a few minor issues that were depending on the hardware of those MSX machines or/and the
devices used in the extender.

We noticed the problem on certain computers with OPLL playback with the GR8NET cartridge. And we had a total failure of FLEX
with RBSC's IDE-FDD cartridge on all MSXs. This cartridge with the Sunrise BIOS complained about data corruption with most of
our CF cards. With other cards it worked, but frequent crashes occurred. So we don't recommend to use FLEX with the IDE-FDD
cartridge.


Tools
-----

The following IDC crimping tool should be used to make the cables:
https://www.aliexpress.com/item/Flat-Ribbon-Cable-Connector-Fixture-IDC-Crimping-Tool-DIY/32792508854.html

The tool requires the special adapter for the male IDC connectors:
https://www.ebay.de/itm/2pc-Adaptor-for-IDC-DIP-Plug-Crimping-tool-HT-214D-Crimper-Width-0-1-0-3-0-6/131173729141

Or you can print the adapter yourself:
https://www.thingiverse.com/thing:3504332


IMPORTANT!
----------

The RBSC provides all the files and information for free, without any liability (see the disclaimer.txt file). The provided
information, software or hardware must not be used for commercial purposes unless permitted by the RBSC. Producing a small
amount of boards for personal projects and selling the rest of the batch is allowed without the permission of RBSC. Printing
of cases is allowed without limitation.

When the boards and 3D models are used to create alternative projects, please always mention the original source and the
copyright!


Contact information
-------------------

The members of RBSC group Wierzbowsky, Tnt23, Ptero, Pencioner and DJS3000 can be contacted via the MSX.ORG or ZX-PK.RU forums.
Just send a personal message and state your business.

The RBSC repository can be found here:

https://github.com/rbsc

The MSX-related 3D models published by RBSC can be found here:

https://www.thingiverse.com/groups/rbsc/things


-= ! MSX FOREVER ! =-
