# LateGameUpgrades
***INSTALL THE DEPENDENCIES***  
***ALL CLIENTS NEED THIS MOD INSTALLED***  
***ALL CLIENTS MUST HAVE THE SAME CONFIG***  

*Everything about this mod can be changed via the config "com.malco.lethalcompany.moreshipupgrades.config"*

to install just put the MoreShipUpgrades folder in your BepInEx plugins folder.

Type `lategame` in the terminal to see mod info!  
Type `lategame store` or `lgu` to view current upgrade status and cost.  
Type `info <upgrade>` for dynamic info.

This adds 18 powerful ship upgrades to make lategame last longer and remedy having a bunch of money and nothing to spend it on.

If using V40 - downgrade to V2.1.0

## V 2.6.0

### **[ Upgrades & Items ]**
- Protein Powder
    - Increase damage done with shovels (and signs).
- Interns
    - Spectate dead player, enter intern into terminal, you will be charged (by default) 1000 credits and it will revive them.
    - Revived players are teleported to a random location in the facility.
    - This should be pretty stable but I noticed if I did it over and over and over again I could run into issues.
- Peeper
    - Expensive piece of equipment that looks at coil heads for you.
- Walkie GPS
    - Upgrades walkie talkies to display the time and your position.
    - Useful for fog
### **[ General Changes / Additions ]**
- Upgrades now go on sale
    - The sale is client side (everyone sees different things on sale).
    - This is to encourage people to take on different roles than they normally would.
- Config now has an option to turn all upgrades to shared upgrades.
- Info command improved
    - It now shows the cost and effect of each level of upgrade
    - Scales with the number of tiers you set in the config
- Lots of little fixes
- Pager removed :(
### **[ Recovery ]**
- `Unload upgrade_name` command
    - will remove the effects of that upgrade from your client.
- `load steam_name` command
    - will copy the upgrades that steam_name has to your client.

### **[ Upcoming ]**

- Config syncing
- More complex / meaningful tiered upgrades.
- More items and Upgrades.

## Community

### Please post bugs, assets, or ideas [on this post](https://discord.com/channels/1168655651455639582/1178407269994594435) after joining [this modding discord.](https://discord.gg/hzEcKFSSDX)

Feel free to [create a pull request](https://github.com/Malcolm-Q/LC-LateGameUpgrades) and help with the mod.

Anyone who contributes in any way is greatly appreciated. People willing to contribute 3D models are needed.

## Compatibility

### This changes and patches a lot so problems may arise.  
- Bigger Lobby and More Company are more or less compatible but credit desync can arise  
- LC Better Saves is currently incompatible but I made a PR and am awaiting the update on thunderstore :)  
- Door fix causes an issue with locksmith  

## Credit
- GitHub Contributors
    - Dilly_The_Dillster
- Graphics / Art / Models
    - Sad Amazon
    - Bobilka
    - Pixelated Engie - [twitter](https://twitter.com/PixelatedEngie)
- Beta Testers
    - Lann
    - Kapt
    - Rootbeer
    - Glitched
    - a glitched npc - [twitch](https://www.twitch.tv/a_glitched_npc)

## Upgrades & Items
***Everything is tweakable via the config***
* __Protein Powder - $500__
    * Increase damage dealt with shovels and signs.

* __Interns - $1000__
    * Replaces your dead friend with a fresh intern (revives your friend).
    * Teleports to a random location in the facility.
    * $1k per use

* __Walkie GPS - $450__
    * Upgrades the walkie talkie to show your position and time.
    * Must be holding it.
    * Useful for fog.

*__Peeper - $500__
    * Looks at coil heads for you.

* __Locksmith - $640__
    * Makes noise when picking, makes a lot of noise when failing.
    * Just run into a locked door to start the minigame.
    * Strike the pins in the order they flash to unlock the door.

* __Portable Teleporter - $300__
    * An item that when used teleports you back to the ship.
    * Keeps items.
    * 90% chance to get destroyed on use.

* __Advanced Portable Teleporter - $1750__
    * Same as above.
    * 20% chance to get destroyed on use.

* __Beekeeper - $450__
    * Circuit bees do significantly less damage to you.

* __Bigger Lungs - $600__
    * Increased sprint duration.

* __Running Shoes - $650__
    * Increased movement speed.

* __Strong Legs - $300__
    * Jump higher.

* __Malware Broadcaster - $550__
    * Instead of disabling turrets and landmines; Destroy them.

* __Light Footed - $350__
    * Enemies have to be closer to hear your footsteps.
    * Applies to both walking and running.

* __Night Vision - $380__
    * Press Left Alt to toggle night vision.
    * Has self regenerating batery.
    * Pick up and lmb to equip.
    * Lose on death (by default).

* __NV Headset Batteries - 300__
    * increases regen speed and decreases depletion speed of NV

* __Discombobulator - $450__
    * Enter `initattack` into the terminal to stun enemies around the ship.
    * Enter `cooldown` to view cooldown (120 seconds).
    * Attracts enemies in a larger radius than loud horn.

* __Better Scanner - $650__
    * Increase distance of Ship and Entrance pings drastically.
    * Increase distance of all other pings.
    * Line of sight is no longer needed for pings.

* __Back Muscles - $715__
    * No longer experience effects from carryweight.


