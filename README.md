# unitscan_turtle    
Target finding addon for Turtle WoW.

## Credit
[Shirsig](https://github.com/shirsig/unitscan-vanilla)

## Description
This fork extends [unitscan-vanilla](https://github.com/shirsig/unitscan-vanilla) by automatically adding predefined zone targets (rare or dangerous mobs) when you enter a zone.

- The zone targets are set by the included [lua file](https://github.com/GryllsAddons/unitscan-turtle/blob/master/zonetargets.lua) and cannot be modified in game.
- Unitscan will only look for zone targets specific to your current zone. The target list is reloaded when you change zones.
- Zone targets will be reloaded 90 seconds after you have found a target (to re-detect roaming targets).
- Unitscan will only alert you of NPC targets that are neutral or hostile and alive. You will always be alerted for player targets regardless.
- Unitscan will not auto target the target when it is found, please click the target in the unitscan window or use the macro command below.
- A macro command */unitscantarget* has been added to target the most recently found target.
- Custom targets added by the /unitscan command will keep the default unitscan behaviour (removed from targets after they are found).
- You can move the unitscan frame by holding ctrl and dragging.

## Commands
**/unitscan** *lists the active scan targets*    
**/unitscan name** *adds/removes **name** to/from the scan targets*    
**/unitscantarget** *targets the most recently found target*    

## Updating Zone Targets
The target list was pulled from classic however please [create an issue](https://github.com/GryllsAddons/unitscan-turtle/issues) for adding any missing custom Turtle WoW targets or any other dangerous or noteworthy targets.
