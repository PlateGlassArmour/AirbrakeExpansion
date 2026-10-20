AIRBRAKE EXPANSION
==================
Kerbal Space Program 1 (KSP 1.12.x)

OVERVIEW
--------
Airbrake Expansion adds three specialized airbrakes that use the stock KSP
airbrake model, with different roles for aircraft and atmospheric spacecraft.
Placement: Always remember that Airbrakes should be installed so that the
Pistons are Protected from the wind when deployed, and they'll provide more
control authority when placed farther from the Center Of Mass.

* Fast Twitch Airbrake
  A compact, fast-acting aerodynamic control surface intended to help stabilize
  a vehicle during atmospheric flight. Useful for correcting unwanted motion
  where fast flap movement matters more than raw braking power.

* Robust Airbrake
  A larger, stronger, slower-moving airbrake designed for demanding atmospheric
  entry and substantial drag. Its reinforced, heat-tolerant design trades
  responsiveness for durability.

* Smart Airbrake
  An entry-focused airbrake with a controller that automatically regulates its
  opening to reduce excessive vessel G-load. It also has optional protection
  against the airbrake's own overheating.

INSTALLATION
------------
1. Close KSP.
2. Open the mod's release ZIP.
3. Copy/merge the included GameData folder into your KSP installation folder.
4. Launch KSP. The three AEX airbrakes are in the Aerodynamics category.

SMART AIRBRAKE: BASIC USE
-------------------------
1. Attach one or more Smart Airbrakes to your vessel. Symmetric placement is
   recommended to avoid unwanted turning moments.
2. Set "G-force ceiling" to a value appropriate for the craft. The default
   is 7 G; the slider ranges from 1 G to 30 G.
3. Set "Deploy Angle" to the maximum opening you want to permit (0-90 degrees;
   default 70 degrees). This is a TARGET MAXIMUM, not an indication of the
   airbrake's current position.
4. Activate the vessel's normal Brakes action group to request airbraking.
   Turn Brakes off to request retraction.

While Brakes is on, the Smart controller reduces deployment when the vessel's
G-load approaches or exceeds the selected ceiling, and reopens more cautiously
when loads decrease. Its in-flight right-click menu shows measured load,
control load, peak part heat, commanded opening and flap angle, plus a status
message.

THERMAL PROTECTION
------------------
When enabled, protection retracts an individual Smart Airbrake if its internal
or skin temperature reaches 90% of the corresponding part limit. It permits
reopening after both fall to 80% or less. Thermal protection can be disabled
on the part's right-click menu.

COMPATIBILITY
-------------
Verified to work with with (but does not require) the following mods:

* Ferram Aerospace Research (FAR)
* ReStock
* TweakScale
* Community Tech Tree (CTT)

TROUBLESHOOTING
---------------
* All three parts should appear under Aerodynamics (or search for "AEX").
* If Smart's settings are missing, verify the compiled DLL is installed.
* If a part looks wrong with ReStock, verify the included .restockwhitelist is
  installed under GameData/AirbrakeExpansion/Patches.

PROJECT AND LICENSE
-------------------
License: MIT (see LICENSE.txt)
Source code: https://github.com/PlateGlassArmour/AirbrakeExpansion
Downloads: TBD
