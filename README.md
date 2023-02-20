# unitscan_turtle    
Target finding addon for Turtle WoW.

## Credit
[Shirsig](https://github.com/shirsig/unitscan-vanilla)

## Description
This fork extends [unitscan-vanilla](https://github.com/shirsig/unitscan-vanilla) by adding predefined [zone targets](https://github.com/GryllsAddons/unitscan-turtle/blob/master/zonetargets.lua) (rare or dangerous mobs) when you enter a zone.    
Zone targets that have been found will be readded to the target list one minute after you have found them.   
This is so you can keep detecting patrolling targets (such as Stitches).    
Custom targets added by the unitscan command will keep the default unitscan behaviour (not re-added after they are found).

There are two commands:<br/>
**/unitscan** lists the active scan targets<br/>
**/unitscan name** adds/removes **name** to/from the scan targets<br/>
When a target is detected it is removed and has to be readded to continue scanning for it.
