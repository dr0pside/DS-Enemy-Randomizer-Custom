# Dark Souls Enemy Randomizer 0.4.2

Update of the original DS1 Enemy Randomizer to change some things and overall make it harder:

BUGS FIXED:
- No more Seath or Kalameet in Nito's arena (Seath gets stuck in the ceiling and is unkillable, Kalameet is just extremely unfun and RNG-heavy as he can one-shot you through the pillar and you have the skeletons coming after you)
- Sentinels now all spawn with regular aggressive AI

BALANCE CHANGES:
- Only lava-proof enemies/bosses can spawn in the lava in Demon Ruins and Lost Izalith (basically you will have demonic statues everywhere but you won't get random free souls anymore)
- Only lava-proof bosses can spawn in the Centipede Demon arena (so him, Quelaag or Taurus Demon)
- Black Knight ghosts in the Kiln don't get replaced anymore (it was basically an infinite souls glitch)

Enemy randomizer generates a random placement of enemies to make your playthrough of Dark Souls different and more challenging. Depending on the options you choose, it's possible to, for example, fight Manus (or 3 of them) in the swamps of Blighttown, or pass through the fog gate in Anor Londo only to see a puny hollow and a painting guardian instead of O&S.

## The mod can be downloaded from
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
