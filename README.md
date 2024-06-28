Here's the README in English:

---

# BETA - NPC Reduce (By pblo) beta-1.0.4.2

![BETA - NPC Reduce](https://www.spigotmc.org/data/resource_icons/112/112568.jpg)

## Description
If you want to improve your REDUCE techniques, this is the easiest way to do it.

## Compatibility
- **Native Minecraft Version:** Legacy (<= 1.13)
- **Tested Minecraft Versions:** 1.8

## Contributors
- LHW - PLUGINS

## Supported Languages
- English

## Donation Link
- [Discord](https://discord.gg/P2cDFtWrKU)

## Dependencies
**Note:** If a version is specified, the script will probably not work on a different version.

### Required
- [Citizen](https://ci.citizensnpcs.co/job/citizens2/3120/) (v2.0.32-SNAPSHOT)
- [Sentinel](https://www.spigotmc.org/resources/sentinel.22017/download?version=489512) (v2.7.3-SNAPSHOT-b505)
- [Skript](https://github.com/SkriptLang/Skript/releases) (v2.2) (likely the first version)
- Other Skript addons. [Download here](https://github.com/pblo618/NpcReduce/raw/main/Dependencies.rar)

### Recommended
- [Multiverse-Core](https://www.spigotmc.org/resources/multiverse-core.390/history) (v2.5-b699)
- [VoidGen](https://www.spigotmc.org/resources/voidgen.25391/history) (v2.2.1)
- [RandomKB](https://www.spigotmc.org/resources/randomkb.48891/history) (v1.55.5)
- [PAPI](https://www.spigotmc.org/resources/placeholderapi.6245/history) (v2.11.3)

## Installation Instructions
1. Add all plugins.
2. Restart the server.
3. Place files in the `plugins/Skript` folder.

## Support
For any bugs or support: [Discord](https://discord.gg/P2cDFtWrKU)

## Commands
Be careful when adding the script to your plugins, as you first need to start your server with skript2.2.jar and then change aliases-english.sk and add the script.

Add all plugins > restart the server > put files from the plugins/Skript folder

/rdc setup [map-name] (u need to hold an item for map icon)
/rdc reload (reload the skript)
/rdc setlobby (set hub's location)
/rdc reset (reset all the sets, locations, npcs, maps...)
/rdc npcjoin (set a npc to maps list / join maps in lobby)
/rdc configs (all settings)
/rdc list [spawns / npcs] (list all spawns and npcs configured)

## Config Commands (/rdc config)

/... skin <player-name>
/... nametag <text>
/... hologram <text> (use - to get space)
Ex.: "/rdc config hologram &b[-&6Hit-to-start-&b]"
/... reach <number>



## Permission
minecraft.op (opperator permission's is needed in setup configuration)

## Setup
1. Download all dependencies and the .sk file;
2. Add the plugins and folder to your server's plugins folder and then start it;
3. Join and setup your lobby.

/rdc setlobby (spawn of your server)
/rdc npcjoin (location to NPC Join)
Setup a map & npc;
/rdc setup [map-name]
Leave from setup ( /quit ) and go to NPC Join.

## Atual Features
- Inventory Sortment;
- No MySQL required.

## To-Do
- Map Selector;
- Spectate Players;
- Block reset animations / styles;
- Perks [Blocks & Sticks];
- Coins system.
