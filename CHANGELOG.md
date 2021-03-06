# 1.12.2

## 1.4.3

* FIXED : Duplication issue with baubles
* FIXED : Tenebra Door dropping an Oak Door when broken

## 1.4.2

* CHANGED : Book Wyrm idle sound is now much quieter
* FIXED : Upper limit for Book Wyrm enchanting level is now only enforced for breeding (that means you can cheat in Book Wyrms with 60 enchanting level if you want, not that it'd be useful)

## 1.4.1

* FIXED : Server crash on startup

## 1.4.0

* CHANGED : Baubles is no longer optional
* ADDED : The Mourner, a new boss to fight, summon her with an Idol of Sorrow to collect Remorseful Essence, some Umbrium and Scarlite
* ADDED : Tears of Penance and Tears of Retribution, ranged weapons crafted with Remorseful Essence
* ADDED : Umbrium as a Tinker's Construct material (includes Smeltery support)
* ADDED : Support for Immersive Engineering's Crusher, Squeezer and Arc Furnace recycling
* ADDED : Blastem can now be bonemealed
* ADDED : Blastem Seed, replaces the Blastem block item
* CHANGED : New textures:
  * All Pellets
  * Calling Stone
  * Blastem (growth stages are now visible)
  * The Destroyer
* CHANGED : The Destroyer now also drops Umbrium Ingots
* CHANGED : The Destroyer now has a special pose while explosive leaping
* CHANGED : Rebalanced Defiled Dugeons loot table, equipment should appear more consistently and is now always enchanted
* CHANGED : Blastem now regrows faster if harvested with a right click
* CHANGED : Blastem Fruit explosions no longer destroy dropped items
* CHANGED : The Ravager can now be crafted with oredicted leather
* FIXED : Modded mobs and animals should no longer naturally spawn in defiled biomes
* FIXED : Blastem Fruit explosions now correctly attribute their damage to the thrower
* FIXED : Optimized defiled biome generation, should be roughly twice as fast as before

## 1.3.0

* ADDED : Baubles compatibility, the following items are added when Baubles is loaded:
  * Scarlite Ring : slowly restores health over time
  * Phytoprostasia Amulet : protects from Vilespine and mature Blastem (thanks 666lumberjack for the idea and bms_ for the name)
* ADDED : ore dictionary entries for Pam's Harvestcraft compatibility on Book Wyrm meat and Scuronotte
* ADDED : Stained Glass can now be defiled into Obscure Glass (thanks orcdash)
* ADDED : Wawla echantment descriptions (thanks Sunconure11)
* ADDED : partial en_UD localization (thanks The-Fireplace)
* CHANGED : Book Wyrms now emits particles when digesting enchantments
* CHANGED : New textures for Blastem Fruits, Blazing Blastem Fruits and Foul Candy
* CHANGED : Foul Candy now uses Defilement Powder instead of Paper
* FIXED : Chisel compatibility now longer uses a deprecated method (thanks	Zsashas for the report)
* FIXED : Book Wyrm effect when digesting now persists on save reload

## 1.2.0

* ADDED : Support for Immersive Engineering's Garden Cloche (Vilespine, Blastem and Scuronotte)
* CHANGED : Shamblers now deal slightly less damage and no longer apply Weakness
* CHANGED : Twisted Shambler dungeons are now much more rare, Host dungeons are now more common

## 1.1.0

* ADDED: JEI support for defilement
* ADDED: Obscure Glass, made from smelting Defiled Sand, blocks light but can be seen through, has CTM support
* ADDED: Defiled Mossy Stone and Defiled Mossy Stone Bricks
* CHANGED: Halved default spawn rate of defiled biomes (you'll have to delete your old config to actually see this change)
* CHANGED: Moved around the Scuttler Eye in the recipes for The Ravager and Umbra Blaster
* FIXED: Vulnerability acting 1 level lower than it actually was

## 1.0.0

* Updated to 1.12.2
* Slightly reduced movement and strafing speed of Scuttlers (should be a bit easier to fight them while lagging)
* Scuttlers, Defiled Slimes and The Destroyer are no longer afraid of heights when pathing
* Hosts no longer have special handling for checking falls when pathing
* Increased durability of Umbrium Armor

# 1.12.1

## 0.3.0

* Added Defiled Gravel
* Added decorative blocks made with Ravaging Essence (Ravaging Stone and Ravaging Bricks)
* Added compatibility with ProjectE (EMC values and world transmutations)
* Added an alternate convenience recipe for Ravaging Pellets (2 Umbrium Pellets + 1 Ravaging Essence = 2 Ravaging Pellets)
* Added french (fr_fr) localization
* Changed Book Wyrm Analyzer recipe (requires a Scuttler Eye and Glass (instead of Glass Panes) now)
* Removed Tenebra tools
* Fixed Tenebra Wood ore dictionnary name
* Changed default enchanting level of unproperly initialized Book Wyrms to be more in line with the natural ones

## 0.2.1

* Fixed server crash when spawning The Destroyer (report by elucent)
* Conjuring Altar now use its own model to prevent issues with resource packs that replace the Enchanting Table's model (report by InsomniaKitten)

# 1.12

## 0.2.0

* Added Ravaging Ingot, made of Ravaging Essence to make powerful new tools
* Added Ravaging Pickaxe, Ravaging Shovel, Ravaging Axe and The Ravager, made from the aforementioned ingots
* Added a new advancement for crafting any of the aforementioned tools
* Added Umbrium Pellet, Spiked Pellet and Ravaging Pellet, used as ammo for The Ravager
* Added 3 potion effects :
  * Vulnerability, increases damage taken (applied by Ravaging Pellets)
  * Bleeding, damage over time (applied by Spiked Pellet)
  * Grounded, applies constant downwards velocity (currently unused)
* Removed advancement for crafting the Umbra Blaster

## 0.1.3

* Book Wyrm Analyzer now gives information about breeding (time until next possible reproduction for adults and time until maturation for babies)
* Conjuring Altars now emit some light
* Fixed foods giving too much saturation

## 0.1.2

* Fixed crash on dedicated server (thanks Elucent and InsomniaKitten)

## 0.1.1

* Added Slabs (can be uncrafted) for Defiled Stone, Defiled Sandstone, Defiled Stone Bricks and Tenebra
* Added Stairs (Quark style recipe, can be uncrafted) for Defiled Stone, Defiled Sandstone, Defiled Stone Bricks and Tenebra

## 0.1

* First public release
