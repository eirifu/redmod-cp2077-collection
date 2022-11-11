# redmod-cp2077-collection
Collection of small Cyberpunk 2077 REDmod mods.

The theme of this collection is "Small change, Big impact". These are small tweaks that radically changed how I played Cyberpunk 2077 in my second playthrough.
Only REDmod is required.

## Stricter Ammo Limit
- Lowers your ammo carry capacity to increase the risk of running out during a prolonged fight. The risk level is fairly low, but is within reach.
- The ammo drops have also been slightly lowered (it now matches the magazine sizes of the weapons)

I've applied this mod to several other games in the past (or deliberately carried less ammo) and I find the sweet spot to often be 5x your magazine or crafting capacity. Similar to the psychological effect of reloading in a video game, this encourages me to use more tools to finish a fight faster, or think before jumping in.
I've also included a 10x variant.

### New Capacities:
- Pistol: 500 → 120
- Rifle: 700 → 240
- Shotgun: 100 → 60
- Sniper: 100 → 40

## Fixed Linear Upgrade Cost
- Adjusts the item upgrade recipe to use less ingredients, and the associated Eurodollar value for Rare/Epic/Legendary recipes scale up.

Crafting was nerfed in a patch by reducing the cost of ingredients and increasing vendor stock, but the recipes themselves are still unbalanced. In particular, the number of Grey components required is still extremely high, and the cost of buying components wasn't taken into consideration - upgrading an Epic is actually more expensive than a Legendary!

After a lot of spreadsheet modeling, I've created two possible solutions:

### Version 4:

- Common/Uncommon: 13 parts, €$62 → 9 parts, €$42
- Rare: 21 parts, €$158 → 12 parts, €$78
- Epic: 23 parts, €$206 → 15 parts, €$126
- Legendary: 21 parts, €$202 → 18 parts, €$200

### Version 5:
Version 5 removes "Crafting components" from the recipe entirely, making you only use "Upgrade components".

- Common/Uncommon: 13 parts, €$62 → 6 parts, €$30
- Rare: 21 parts, €$158 → 9 parts, €$44
- Epic: 23 parts, €$206 → 12 parts, €$120
- Legendary: 21 parts, €$202 → 15 parts, €$204

## Untrack Quest
- This is a REDmod rewrite of a mod that lets you right-click a quest marker on the map screen to remove it. In the base game, you can only right-click to remove custom markers.
- I've also changed it so your custom marker is not automatically removed when changing to a new quest marker.

Sometimes it's nice to wander the world or try to find your own way to the quest without the subliminal influence of the minimap. It's not meant to stay off though, so as a side effect, the game will automatically switch to a new quest or quest update if you run into one.

If you reopen the world map, you'll see a default quest reminder called "A Favor for a Friend". After examining the code, removing this requires a more extensive mod which I haven't done yet.
