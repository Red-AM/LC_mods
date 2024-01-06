# Scoopy's Variety Mod (formerly LethalExtension)

## Overview:

***Ensure you uninstall/delete LethalExtension to avoid conflicts before playing***

***Config values will not carry over, you will need to update the new config file (BepInEx/config/ScoopysVarietyMod.cfg) with any changes you had made***

Currently, the mod adds one new interior, which is dungeon themed, and some new scrap items. This interior is comprised of custom assets and is intended to add some variety to the interiors in the base game. 

The dungeon interior is in an almost complete state, with some bugs. There will likely be more content added to this dungeon in the near future, in addition to fixing some of the remaining issues.

The dungeon interior is a sprawling and dark crypt style interior with a high degree of verticality compared to the base interiors. 

If you encounter any bugs you'd like to report, please post them in the LethalExtension thread located in the "mod-releases" section of the Lethal Company modding discord (https://discord.com/servers/lethal-company-modding-1168655651455639582).

## Features:
1. Dungeon (Interior)
	1. Sprawling interior made from custom assets with high degree of verticality.
	2. Spawning parameters can be customized using the config file located in BepInEx/config.

2. Scrap Items
	1. Guitar: Plays funny weezer riff on use
	2. Fire Axe: Defensive weapon, hits significantly harder than shovel. Can't be purchased. Spawns on all (vanilla) paid planets.
	
More features and improvements to come in the near future.

To avoid issues in multiplayer, ensure all players have the same settings in their individual config files.

## Images
![](https://i.imgur.com/AI4lRFy.jpg)

![](https://i.imgur.com/o93yarY.jpg)

![](https://i.imgur.com/ID54iJT.jpg)

![](https://i.imgur.com/8g8W89m.jpg)


## Installation:
- Ensure you have all listed dependancies installed.
- Download and unzip the mod.
- Place the contents of the 'plugins' folder into the 'plugins' folder located in your BepInEx install (Lethal Company\BepInEx\plugins`)
- Launch the game once to generate a config file if you would like to edit config parameters.

## Known issues:
- Some lag issues on large generations due to HDRP shadows.
- All players must have matching config values or sync issues will occur.
- Spray cans don't work on dungeon assets.
- The weezer guitar can currently cause desync issues when players other than the host pick it up.
- The dungeon interior is not enabled on March, due to the fact that March has multiple fire exit doors. Fire exits will not function on moons with more than one fire exit door.
- Spawning on custom moons can cause sync issues.
- Some enemies have pathing issues.
- Very rarely on large maps (such as Titan), if the interior generation is too vertical, the player can be teleported to the entry door after travelling too far up or down.

