---
layout: default
---

# Why are achievements not working ?

## It's the way the game is coded

> It is not possible to gain achievements if the checksum has been changed - either by tampering with game files, or by running the game using mods that affect gameplay mechanics (graphical mods do not affect checksum), or a corrupted installation (the Ironman mode icon will change to reflect this).

Community Flavor Pack does not affect gameplay mechanics but it has to edit files in `common` folder ([list here](https://github.com/ElTyranos/CommunityFlavorPack/wiki/Edited-vanilla-files)), where the game checksum is computed,  in order to add new assets. No edit in there = no new models.

For more informations, check [CK3 wiki](https://ck3.paradoxwikis.com/Achievements).
