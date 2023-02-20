# unitscan_turtle    
Target finding addon for Turtle WoW.

## Credit
[Shirsig](https://github.com/shirsig/unitscan-vanilla)

## Description
This fork extends [unitscan-vanilla](https://github.com/shirsig/unitscan-vanilla) by automatically adding predefined zone targets (rare or dangerous mobs) when you enter a zone.    
The zone targets are set by the included [lua file](https://github.com/GryllsAddons/unitscan-turtle/blob/master/zonetargets.lua) and cannot be modified in game.    
Zone targets that have been found will be readded to the target list one minute after you have found them so you can continue detecting roaming targets.      

Custom targets added by the /unitscan command will keep the default unitscan behaviour (removed from the targets list after they are found).

There are two commands:<br/>
**/unitscan** lists the active scan targets<br/>
**/unitscan name** adds/removes **name** to/from the scan targets<br/>
When a target is detected it is removed and has to be readded to continue scanning for it.
