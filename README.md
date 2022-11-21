# redmod-cp2077-collection
Collection of small Cyberpunk 2077 REDmod mods.

The theme of this collection is "Small change, Big impact". These are small tweaks that radically changed how I played Cyberpunk 2077 in my second playthrough.
Only REDmod is required.

## Stricter Ammo Limit
- Lowers your ammo carry capacity to increase the risk of running out during a prolonged fight. The risk level is fairly low, but is within reach.
- The ammo drops have also been slightly lowered (it now matches the magazine sizes of the weapons)

I've applied this mod to several other games in the past (or deliberately carried less ammo) and I find the sweet spot to often be 5x your magazine or crafting capacity. Similar to the psychological effect of reloading in a video game, this encourages me to use more tools to finish a fight faster, or think before jumping in.
I've also included a 10x variant.

| Weapon  | Old | New | 10x |
|---------|-----|-----|-----|
| Pistol  | 500 | 120 | 240 |
| Rifle   | 700 | 240 | 480 |
| Shotgun | 100 | 60  | 120 |
| Sniper  | 100 | 40  | 80  |

## Fixed Linear Upgrade Cost
- Adjusts the item upgrade recipe to use less ingredients, and the associated Eurodollar value for Rare/Epic/Legendary recipes scale up.

Crafting was nerfed in a patch by reducing the cost of ingredients and increasing vendor stock, but the recipes themselves are still unbalanced. In particular, the number of Grey components required is still extremely high, and the cost of buying components wasn't taken into consideration - upgrading an Epic is actually more expensive than a Legendary!

After a lot of spreadsheet modeling, I've created two possible solutions:

### Version 4:

| Part | Old | New | +10 Levels (New) |
|--|--|--|--|
| (Un)common | 13 parts, €$62 | 9 parts, €$42 |    €$ 2310 |
| Rare     | 21 parts, €$158 | 12 parts, €$78 |    €$ 4290 |
| Epic    | 23 parts, €$206 | 15 parts, €$126 |    €$ 6930 |
| Legendary | 21 parts, €$202 | 18 parts, €$200 |  €$ 11,000 |

### Version 5:
Version 5 removes "Crafting components" from the recipe entirely, making you only use "Upgrade components".

| Part | Old | New | +10 Levels (New) |
|--|--|--|--|
| (Un)common | 13 parts, €$62 | 6 parts, €$30 |   €$ 1650 |
| Rare      | 21 parts, €$158 | 9 parts, €$44 |   €$ 3630 |
| Epic    | 23 parts, €$206 | 12 parts, €$120 |   €$ 6600 |
| Legendary | 21 parts, €$202 | 15 parts, €$204 | €$ 11,220 |

## Untrack Quest
- This is a REDmod rewrite of a mod that lets you right-click a quest marker on the map screen to remove it. In the base game, you can only right-click to remove custom markers.
- I've also changed it so your custom marker is not automatically removed when changing to a new quest marker.

Sometimes it's nice to wander the world or try to find your own way to the quest without the subliminal influence of the minimap. It's not meant to stay off though, so as a side effect, the game will automatically switch to a new quest or quest update if you run into one.

If you reopen the world map, you'll see a default quest reminder called "A Favor for a Friend". After examining the code, removing this requires a more extensive mod which I haven't done yet.

## Faux New Game Plus
- Adds a number of benefits to a new game to speed things up a bit. Technically a cheat mod, but made with balance in mind.
- This doesn't read another save game and import a character - this is more akin to the New Game Plus seen in Mass Effect 2 and Pillars of Eternity 2, which gives a small, balanced number of boosts and prizes if you import a save.

The boosts and prizes are spread across three points in the game:

#### In the character creation menu: 
- The attribute point limit is now 1 to 20 instead of 3 to 6. (No extra points are added, so there's a soft cap of 18.)

#### After rescuing Sandra Dorsett at the end of the Prologue:
- Wakako gives you an extra 10,000 Street Cred XP, raising you to Cred Level 10.
- You gain €$24,910 - enough to immediately buy the bot and pay Rogue, or just buy some upgrades.

#### At the start of Act 2, you are given:
- Adam Smasher's room keycard
- All of the post-game legendary items rewarded in each ending path, which includes:
- Legendary Gorilla Arms and Militech Berserk Mk.5
- Caretaker's Spade and Rogue's Pistol "Pride"
- Panam's Rifle "Overwatch", Cassidy's Pistol "Amnesty", and the Aldecados jacket
- The "Genjiroh" Yukimura Pistol

All the items spawn at your level by default, so it's not particularly overpowered.


## Install Instructions
These mods are made to ONLY use REDmod, to maximise compatibility. This is the official mod-loading method - Cyber Engine Tweaks and redscript are unofficial methods and will break with every patch.

**If you haven't prepared Cyberpunk 2077 for modding before:**
1. Install REDmod from whereever you bought the game. (It's a free DLC)
2. Go to your install folder and go to "\\Cyberpunk 2077\r6\cache"
3. Make an empty folder called "modded".

**To install mods:**
1. In "\\Cyberpunk 2077\mods", place the MOD FOLDER ITSELF in here.
2. If you did it correctly, the "info.json" file should be at "\\Cyberpunk 2077\mods\MOD FOLDER\info.json".
3. Run REDlauncher. (Don't run the game directly.)
4. Open the game settings, tick "Enable Mods", and press Play. The mods will be compiled.

**To remove or turn off mods**
- To uninstall a mod, delete the folder and go through REDLauncher again.
- If you alter or update a mod file, empty the "modded" folder before running REDlauncher.
- If you only use REDmod-based mods, you can play without mods without uninstalling them by unticking "Enable Mods" in the launcher.

