# 0.5.1
- Changed fire exit spawning to be more similar to the base game
	- No longer spawns in a 1x1 room, now on random door blockers
- Changed guitar to be one-handed
	- While the desync issue may still occur, this should at least allow players who become desynced to still interact with the world
- Some lighting changes to hopefully improve performance

# 0.5.0
- Added a new room tile
- Changed door sounds for opening/closing/unlocking wood doors
- Changed dungeon interior moon config
	- You can now specify lists of individual moons instead of just pre-defined settings
	- You can specify modded moons aswell, though these are still unstable and may result in issues
	- If you have made any config changes you will likely need to update your config to match the new settings
- Fixed an issue where turrets could see/shoot through doorways and some objects
- Moved some torches to reduce lighting bleed-through
- Increased scrap value of fire axe and weezer guitar

# 0.4.0
- Added a new room tile
- Fixed enemies being unable to navigate up the spiral staircase
- Added a central pillar to the spiral staircase room
- Fixed enemies being able to walk through some map objects
- Adjusted map objects in some rooms

# 0.3.0
- Renamed to "Scoopy's Variety Mod" to avoid confusion with similarly named mods
- Fixed weezer guitar bugging out players games and being undroppable
	- Encountered no issues in my testing, please report if this issue persists
- Fixed enemies not being able to enter the spiral staircase room
	- Spiral staircase itself is still not functional
- Added config options to control scrap item rarities
- Adjusted lighting to improve FPS drops caused by hitting shadow cap

## 0.2.1
- Fixed dungeon spawning on March when not intended
	- This will disable dungeon spawning on modded moons for the short term - more permanent fix coming soon
- Added some props to the dining room tiles
- Moved the annoying table infront of one of the dining room door spawns 
- You can now specify specific planets other than titan in the config in a similar manner to titan ("vow", "rend", etc.)

## 0.2.0
- Added fire axe as a scrap and useable weapon
	- Only found as a scrap spawn, can't be bought
	- Deals significantly more damage than the shovel, or can be sold for a good price
- Significantly changed the generation parameters of the dungeon interior
	- Start room should no longer generate only a single path, and rather provide between 3-4 paths each time
	- Dungeon size has been reduced significantly, to improve navigation and bring it closer in-line to vanilla interiors
	- Overall dungeon generation should be more "branch-y" and less "depth-y"
- Changed dungeon lighting to improve visibility
	- Increased brightness and radius of torches 
	- Added and moved some torches in tiles
- Changed dungeon footstep sounds to better suit the material
- Significantly reduced likelihood of dungeon being too vertical and causing player to teleport to entrance
	- May still occur very rarely on titan
- Fixed enemies being unable to path up and down normal staircases
	- Only tested extensively with masked enemies - some enemies may still not work
- Fixed enemies not opening doors and walking through walls
	- Some enemies are still broken and unable to open doors, but none should walk through walls anymore
- Fixed an issue where players could clip through the front door and fall out of the map
- Changed cell-doors to fix server-wide syncing
- Fixed locked cell doors not being able to be unlocked with a key
- Minor changes to some dungeon tiles 

## 0.1.0
- Initial release
- Added dungeon interior.
- Added weezer guitar as two-handed scrap item.