---
title: Antennas
date: 2026-02-02T07:02:10-06:00
menus:
  main:
    weight: 20
---
#### Mast
The mast mount on the back of the rover was originally designed and built for my 2020 Jeep Cherokee.  By some miracle, it worked _perfectly_ without any modifications on the 2009 GMC Savana that is now the dedicated rover vehicle.

The mount goes into a standard 2" trailer hitch and is constructed from 2 x 2 x 1/8" square steel tube and 3/16" steel plate.  It is two pieces pinned together with standard receiver hitch pins.  The vehicle half is two pieces of 2x2 square stock welded together in an "L" shape and sandwiched between to 3/16" plates.  The mast half is a length of 2x2 square stock with plates welded on the top and bottom which hold the rotor and thrust bearing.  There’s really no big vertical load here so this could probably just as easily be a simple bushing.  But, anything worth engineering is worth over engineering, so I used a thrust bearing.

The actual mast in the VHF+ rover configuration consists of aluminum tube (lower) and pipe (upper).  The lower fixed section is 2 x 1/8" 6061 aluminum tubing.  The upper extendable section is 1-1/4" Schedule 40 6061 aluminum pipe.  Definitely a loose fit but it makes it very easy to quickly extend / collapse.  The two mast sections are pinned together with a simple 1/4" trailer coupler pin I found on Amazon.

The mast is rotated by a Spid RAU running on 24v.  All of the specs I've found say the rotor runs on 12-18v DC, but it runs _so slow_ on lower voltages, so I went rogue.  It is controlled by a Green Heron RT-21dc controller with a surgically implanted Samlex Step 7 DC-DC Step-Up Converter.  The Samlex 24v converter fits perfectly where the transformer would normally be mounted inside of the RT-21.

For HF operation with wire antennas, I also have two sections of fiberglass mast which can be pinned into the top aluminum mast to get to about 35ft.

#### VHF+ Antennas
All of the VHF+ Antennas are from [Directive Systems](https://directivesystems.com/).

- 50 - DSE3-50 - 3el Yagi @ 20'
- 144 - DSE144-6RS - 6el Rover Yagi @ 12’
- 222 - DSE222-10RS - 10el Rover Yagi @ 10’
- 432 - DSE432-15RS - 15el Rover Yagi @ 8’
- 902 - DSE3319LY - 19el Loop Yagi @ TBD (not installed... yet)
- 1296 - DSE2325LY - 25el Loop Yagi @ TBD (not installed... yet)

#### HF Antennas
- Homebrew doublet - ZS6BKW design 
- Chameleon Antenna CHA SS25 - 25' stainless steel collapsible whip