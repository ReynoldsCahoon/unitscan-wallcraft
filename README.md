# unitscan_wallcraft
[Unitscan](https://github.com/ReynoldsCahoon/unitscan-wallcraft) modified for [Wallcraft](https://www.wallcraft.org/).

## Description
This fork extends [unitscan-turtle](https://github.com/GryllsAddons/unitscan-turtle) by adding Wallcraft specific rares and eventually adding addon communication to track rare spawn timers and provide announcements.

You can add custom targets to find players or targets not included in the zone targets list by using the command /unitscan *name*.

Unitscan will only look for zone targets specific to your current zone. The target list is reloaded when you change zones.

Zone targets will be reloaded 90 seconds after you have found a target (to re-detect roaming targets).

Unitscan will alert you of NPC targets that you can attack and are alive.

You will always be alerted for player targets regardless.

Targets added by the /unitscan command will be removed from active scan targets after they are found.

**Unitscan will pause scanning when in combat or when auto attack, auto shoot and wanding are active.**

You can move the unitscan frame by holding ctrl and dragging.
 
**Please note unitscan-wallcraft will not auto target the target when it is found.**    
**Click the target in the unitscan window or use the macro /unitscantarget to target the mob.**

## Addon Compatibility
Unitscan uses the [TargetByName](https://wowpedia.fandom.com/wiki/API_TargetByName) function to scan through the list of targets to find an exact match. This causes the game to switch targets if the named target is nearby. Unitscan will immediately restore your original target however if you are using addons that do something when you switch targets (such as issue an alert if targets are PvP flagged) then they may trigger for the found target.

## Commands
**/unitscan** *lists the active scan targets*    
**/unitscan name** *adds/removes **name** to/from the active scan targets*    
**/unitscantarget** *targets the most recently found target*    

## Recommended addons
To see target abilities in the tooltip please see [codex](https://github.com/nakda/codex/tree/main).

## Updating Zone Targets
The target list was pulled from classic however please [create an issue](https://github.com/ReynoldsCahoon/unitscan-wallcraft/issues) for adding any missing custom Wallcraft targets.
