_Find the traces of the people that were there before you._

[![Discord](https://img.shields.io/discord/1205872487158775890?style=for-the-badge&logo=discord&logoColor=white&label=DISCORD&labelColor=7289da&color=2c2f33)](https://discord.com/invite/HQ8Pqk8bUE)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Static Badge](https://img.shields.io/badge/Support%20me!-Kofi?style=for-the-badge&logo=Kofi&logoColor=white&label=Ko-fi&labelColor=FF5E5B&color=13C3FF)](https://ko-fi.com/terabuildsstuff)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![GitHub Release](https://img.shields.io/github/v/release/STRAYED-FATES/Forsaken?style=for-the-badge&logo=github&label=GITHUB&labelColor=black&color=6e5494)](https://github.com/STRAYED-FATES/Forsaken)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Static Badge](https://img.shields.io/badge/-STRAYED%20FATES-LICENSE?style=for-the-badge&label=LICENSE&labelColor=white&color=white)](https://github.com/STRAYED-FATES/LICENSE?tab=License-1-ov-file)

This project adds rare, semi-vanilla style abandoned structures to the Overworld, inspired by pre-industrial revolution buildings from around the globe; With no eccentric loot, no swarms of mobs, only the beauty of the scars time left on civilization.\
**STRAYED FATES: Forsaken** uses a multitude of variants, alongside complex processors, varied decorations and well-thought uses of features, with the goal of making each time you stumble onto a structure a once in a playthrough discovery.

# Content
The main theme of the STRAYED FATES projects is abandoned buildings and their ambience, telling a story through near barrenness.
Each major update will be themed and have its fair amount of new structures, while minor updates might include new variants or structure sets, and possibly mod compatibilities, alongside fixes & tweaks. The current version includes:

<details>
<summary><b>Homes</b></summary>

Structure sets : 9
- Oak: 11+(11x14*) variants
- Spruce: 9 variants
- Western: 9 variants
- Snowy: 9+(9x14*) variants
- Desert: 9 variants
- Bricks: 9+(9x14*) variants
- Mud: 9 variants
- Oriental: 9 variants
- Turf: 9 variants\
*Cellar
</details>
<details>
<summary><b>Wells</b></summary>

Structure sets : 5
- Rustic: 61732~* variants
    - Spruce: 15433* variants
    - Oak: 15433* variants
    - Birch: 15433* variants
    - Dark Oak: 15433* variants
- Oriental: 979* variants
- Mud: 15 variants
- Pit: 8 variants
    - Cobble: 4 variants
    - Mud: 4 variants
- Pump: 23 variants
    - Cobble: 9 variants
    - Mud: 9 variants
    - Bamboo: 5 variants
- Washhouse: 5 variants

*Calculated on the number of necessary jigsaw pieces variants that can be combined
</details>

# FAQ
*The term "project" refers to the Datapacks/Mods of STRAYED FATES, the term "update" refers to named major updates of one of the projects.*
## GENERAL
**Can this be used in Vanilla and or on a server?**\
All projects use the Vanilla custom structure system to generate and no modded blocks. It can be used completely server side, meaning you can use it on your own in Singleplayer or install it on your server without other players needing to install it. Any mod support will simply not apply if you don't have the mods.

**What's the difference between the Datapack version and the Mod version?**\
Content wise, none. The only difference is that the Datapack has to be applied per world while the mod applies to any world of the instance.

**Can I safely uninstall or install the project.s on an existing world?**\
Yes, you will just stop or start finding structures only in newly generated chunks.

**Is it compatible with [...]?**\
Those projects follow the Vanilla/Fabric/Forge/Neoforge biome tags system to choose which Vanilla/Custom biomes allow for the spawning of the structures. Meaning it is compatible with any worldgen Datapacks or Mods using those tags correctly and any other Datapacks or Mods. If unsure, try it and see.

**Does it support [...] mod?**\
All supported mods of a project and their content are listed on their downloads pages. We do not take requests.

**Can I update safely?**\
You are able to update the projects anytime one is available, however the changes will only be seen in newly generated chunks and structures. Meaning that fully pregenerated worlds will not see the changes.

**How do I tell if it's working?**\
The Datapack has to be loaded and applied to the world while Mod should automatically apply to all worlds of the instance. In both cases, you can use /datapack list to see if the project is there. You can also use `/locate structure #project:any` or 
`/locate structure #project:update`
 and see if you're able to locate the structure.

**Where do I find the [...] structure?**\
The point of the projects is not to find all the structures, but if for some reason you wish to know where to find each one, check their respective file in `data/project/tags/worldgen/biome/has_structure/homes/` to learn in which biomes they can appear. Ultimately you could also use `/locate structure project:update/` in game, or use jacobsjo's [map](https://map.jacobsjo.eu/) website to find where each structures are located in your seed.

**Will there be any backports?**\
No.
## CONFIGURATION
There is no options directly available for the projects, to configure it, you have to open the `.zip` or `.jar`(to open a `.jar`, rename it `.zip`, then rename it `.jar` once you're done) using programs like 7zip or WinRar.
Note that any update might reset your changes.
We will not offer support on modified versions of the project nor allow for them to be shared as per the license.
### Frequency
To change the frequency/rarity of structures, head to `\data\project\worldgen\structure_set`, and open the desired `.json`. You  can then modify the `frequency`, a value between `1` and `0` corresponding to the chances a structure has to spawn when meeting the other values, the `spacing`, the average distance in chunks the structures of that group will have from each other, and the `separation`, which is the minimum chunks the structures of that group will have from each other.
### Disabling
#### Update
To disable the structures of an update from spawning in your world, head to `\data\project\worldgen\structure_set`, find the update `.json` you wish to disable, then delete it or add a `-` at the start of it's name to disable it. We recommend to also delete or disable the corresponding function in `\data\project\functions`.
#### Set
To disable a structure group in one of the updates, open the corresponding `\data\project\worldgen\structure_set\update.json` file, select the module ( `{ }` ) the structure is labeled in, alongside the comma after it, then delete it and save.
#### Piece
To disable a piece of a structure, head to  the corresponding `.json` file in `\data\project\worldgen\template_pool\update\` select the module ( `{ }` ) the structure and its weight is labeled in, alongside the comma after it, then delete it and save.


Logos by [OopsOnlyDelta](https://modrinth.com/user/OopsOnlyDelta)
