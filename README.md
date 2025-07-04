# Dark Souls Enemy Randomizer 0.4.3.2

Update of the original DS1 Enemy Randomizer to change some things and overall make it harder.
(I only started learning Python in May 2025 so please don't clown on me too hard for all the hardcoding)

BUGS FIXED:
- Seath cannot replace Nito or Firesage Demon anymore (gets stuck in the ceiling and is only barely killable via ranged attacks)
- Regular Sentinels now spawn in place of the non-aggresive bugged Royal Sentinels
- The first of the Four Kings won't be replaced anymore as any other boss/enemy that took its place would be invisible on first spawn (far from ideal solution but after 1 day of debugging I couldn't find the reason for the bug)
- No more mismatches between models and AI in Darkroot Garden & Basin
- Removed bugged giant sword skeletons who would constantly attack in place

BALANCE CHANGES:
- (Optional) Only demonic statues can spawn in the lava in Demon Ruins and Lost Izalith (no more free souls)
- (Optional) Only lava-proof bosses can spawn in the Centipede Demon arena to prevent insta-wins (so you'll fight him, Quelaag, Capra or Taurus Demon)
- Black Knight ghosts in the Kiln don't get replaced anymore (other enemies and bosses would fall to their deaths instantly, which was basically an infinite souls glitch)
- Harder versions of regular enemies can now appear (e.g. you can get Sen's Fortress versions of the Balder Knights instead of only getting the Undead Parish versions). Enemies affected: Channelers, Balder Knights, Berenike Knights, Manserpents (both Sword & Mage), Black Knights, Bonewheels, Basilisks, Undead Dogs, Frog-Rays, Small Rats, Stone Knights, Demonic Foliage.
- Easier versions of the following enemies can appear: Blue/Gold Crystal Golems, Clams, Mushroom Papas & Mushroom Babies.
- Kalameet not eligible to appear in Nito's arena anymore (extremely unfun and RNG-heavy as he can instakill you through the pillar while skellies gank you).
- Sen's Fortress boss now appears in the center of the arena, as some bosses like Sif and Nito would to get stuck in place and become trivial to kill with the vanilla placement

MISCELLANEOUS:
- (Optional) Moonlight Butterfly will not get replaced by default (simply because most other bosses will fall off the bridge by themselves and never die as there is no killbox below).
- Added bow-wielding regular and giant skeletons as potential enemies.
- Added the shear-wielding scarecrow as a potential enemy.
- Scarecrows can have one of a few model variations, as present in the DLC (fully clothed, upper body naked, lower body naked etc.)
- The model for covenant NPC Nito will now match the model for whoever is the boss in Tomb of the Giants.

Lava-Proof enemy handling & Moonlight Butterfly changes can be toggled from inside the UI (Even More Options tab)

# ORIGINAL DESCRIPTION:

Enemy randomizer generates a random placement of enemies to make your playthrough of Dark Souls different and more challenging. Depending on the options you choose, it's possible to, for example, fight Manus (or 3 of them) in the swamps of Blighttown, or pass through the fog gate in Anor Londo only to see a puny hollow and a painting guardian instead of O&S.

------

# Installation Instructions [Prepare to Die Edition]:

1. Unpack your Dark Souls archive files using [UnpackDarkSoulsForModding](https://www.nexusmods.com/darksouls/mods/1304/?).
2. Download Enemy Randomizer and place `EnemyRandomizer.exe` and `enemyRandomizerData` folder from the `.zip` file to `Dark Souls Prepare to Die Edition\DATA\` (the same folder where `DARKSOULS.exe` is).
3. Run the `EnemyRandomizer.exe`. The first time you launch the program, it will take some time to start up, as it's preparing files for randomization and backing up the originals.
4. Press the Randomize button to randomize the enemies according to the selected settings and write the modified data to .msb and .luabnd files.


# Installation Instructions [Remastered]:
------

1. Download Enemy Randomizer and place `EnemyRandomizer.exe` and `enemyRandomizerData` folder from the `.zip` file to `DARK SOULS REMASTERED\` (the same folder where `DarkSoulsRemastered.exe` is).
2. Run the `EnemyRandomizer.exe`. The first time you launch the program, it will take some time to start up, as it's preparing files for randomization and backing up the originals (this part takes a bit longer on the Remaster).
3. Press the Randomize button to randomize the enemies according to the selected settings and write the modified data to .msb and .luabnd files.
4. You should also probably back up your save file in `Documents/NBGI/DARK SOULS REMASTERED` and go into offline mode in Steam just in case (I don't know if the changes made by the randomizer can get one banned from online play).


## Restoring normal enemy placement after randomizing:

1. Run the randomizer and press the "Revert to normal" button to restore the original map and script files.
2. [Remaster] If you backed up your save file, then restore that as well.

## Original Credits/Thanks:

* __HotPocketRemix__ - bnd file unpacking/repacking implementation, event scripting tools that allowed me to change certain event scripts, program GUI inspiration
* __Wulf2k__ - looking at MSBEdit's source code helped me create my implementation of msb editing
* __Meowmaritus__ - [this](https://www.reddit.com/r/DarkSoulsMods/comments/6a4sbg/are_custom_maps_technically_feasible/dhe114q/) comment i found describing luagnl and luainfo file formats
* __Metal Crow__ - fix for the game (PTDE) crashing when trying to load all visual effects at once
* __Lan5432__ - helping me test v0.2, providing the best comments about screenshots
* __DuckyKoi__ - gifting me the remaster so I could port the randomizer to it.
