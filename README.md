# unitscan_turtle    
Target finding addon for Turtle WoW.

## Credit
[Shirsig](https://github.com/shirsig/unitscan-vanilla)

## Description
This fork extends [unitscan-vanilla](https://github.com/shirsig/unitscan-vanilla) by automatically adding predefined zone targets (rare or dangerous mobs) when you enter a zone.    
The zone targets are set by the included [lua file](https://github.com/GryllsAddons/unitscan-turtle/blob/master/zonetargets.lua) and cannot be modified in game.    
Zone targets that have been found will be readded to the target list one minute after you have found them so you can continue detecting roaming targets.      
Additionally, unitscan will only return mobs that are neutral or hostile and alive but will always return player targets regardless.    
The default behaviour of unitscan has been modified so that if you are currently targeting a unit your target will not change when a unit is found.    
A macro command */unitscantarget* has been added to target the most recently found target.

Custom targets added by the /unitscan command will keep the default unitscan behaviour (removed from the targets list after they are found).

Commands:<br/>
**/unitscan** lists the active scan targets<br/>
**/unitscan name** adds/removes **name** to/from the scan targets<br/>
**/unitscantarget** targets the most recently found target<br/>
When a target is detected it is removed and has to be readded to continue scanning for it.

## Updating Zone Targets
The target list was pulled from classic however please [create an issue](https://github.com/GryllsAddons/unitscan-turtle/issues) for adding any missing custom Turtle WoW targets or any other dangerous or noteworthy targets.
