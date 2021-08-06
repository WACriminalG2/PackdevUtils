# v1.17.0 -- 8/5/21

* Added validation schema for AgriCraft: plant.

# v1.16.0 -- 8/5/21

* Added validation schema for Scavenge scripts.

# v1.15.0 -- 8/4/21

* Updated Origins schemas. Credit: S_K_Tiger
* Modified Cave Generator utility snippets.
* Added schema validation for Cave Generator presets. Heavily WIP. As VScode is unable to apply regular JSON schema validation to HJSON and CAVE files, you'll want to temporarily use a .json or .jsonc extension for your presets while editing them. Do note that schema validation is unable to include some of CG's more advanced features such as variables, functions, and imports. For best results with CG, use its native file format and syntax. This schema validation is intended as a learning tool for new CG preset developers and an in-editor reference tool.
* Universal Registry added:

## BLOCKS

* Artisan Worktables
* Custom Machinery
* Gauges and Switches
* GeoSmelt
* Monke Madness
* Solar Cooker
* Trophy Manager

## ITEMS

* Artifacts
* Artisan Tools
* Artisan Worktables
* Custom Machinery
* Gauges and Switches
* GeoSmelt
* Monke Madness
* Solar Cooker
* Spartan Weaponry
* Trophy Manager

## ENTITIES

* Artifacts
* GeoSmelt
* Monke Madness
* Spartan Weaponry

## POTIONS

None.

## ENCHANTMENTS

* Spartan Weaponry

## BIOMES

None.

# v1.14.0 -- 8/3/21

* Updated Origins schemas. Credit: S_K_Tiger
* Added schema validation for Solar Cooker recipes.
* Added schema validation for recipes from Ex Nihilo Sequentia: Compost, Crook, Crucible, Fluid-Item Transformation, Fluid-On-Top Transformation, Fluid Transformation, Hammer, Heat, Sieve.
* Added schema validation for Masterful Machinery: Structures, Processes, Controllers.

# v1.13.0 -- 8/3/21

* Added schema validation for custom portal definition via Immersive Portals.
* Added schema validation for Botany Pots soils, crops, and fertilizers.

# v1.12.0 -- 8/3/21

* Added schema validation for CompactCrafting's miniaturization recipes.
* Added schema validation for Silent Gems 3's token enchanting recipes.
* Added schema validation for loot tables courtesy of Levertion's schema project under the CCA 4.0 International license: https://github.com/Levertion/minecraft-json-schemas. Slight modifications have been made from the schema provided in that project, to allow non-vanilla registry IDs to be used. This has resulted in some superfluous referenced files that are nonetheless difficult to disentangle from the actual schemas. I hope to complete that task over time, but thought it might be more motivating for me if I were to simply get this one out the door and functional, first.

# v1.11.0 -- 8/2/21

* Added schema validation for custom honey and traits from Resourceful Bees.
* Added schema validation for custom Tetra materials.
* Applied existing schema validation for InControl's summonaid.json.
* Not a change to this extension, but worth noting that Masa has implemented a custom dump format in TellMe that should make it much easier for me to add mods to the universal registry, and maintain existing ones through version updates. Thanks, Masa!

# v1.10.0 -- 8/1/21

* Added schema validation for Project Rankine's evaporation recipes.
* Added schema validation for custom bees from Resourceful Bees.

# v1.9.0 -- 8/1/21

* Adjusted parent schema URL.
* Added schema validation for Crock Pot's cooking recipes.
* Added schema validation for Origins: layers, powers, and origins. Credit: S_K_Tiger
* Added schema validation for Spoiled's food-spoiling recipes.

# v1.8.3 -- 7/31/21

* Updated Lycanite's Mobs schemas -- was previously working from old documentation.

# v1.8.2 -- 7/31/21

* Fixed internal sub-schema references.

# v1.8.1 -- 7/31/21

* Fixed folder-matching for Architect's Palette warping schema validator.

# v1.8.0 -- 7/31/21

* Added schema validation for Lycanite's Mobs spawner, creature, and element configuration files.

# v1.7.0 -- 7/30/21

* Added schema validation for Bountiful's decree and objective/reward pool JSONs.
* Universal registry added:

## BLOCKS

* Botany Pots
* Bountiful
* Carrots Lib
* CasinoCraft
* Crock Pot
* Culinary Construct
* Dimensional Dungeons
* Edible Bugs
* Engineer's Decor
* Fluffy's Farming
* Horticulture
* Husbandry
* MedievalCraft
* MineColonies
* Occultism
* Piscary
* PokeCube
* PokeCube Adventures
* PokeCube Legends
* Seasonals
* Silent Gear
* Silent's Mechanisms
* Simply Tea
* SushiGo Crafting
* Terraqueous
* Terraqueous Heads
* Token Enchanter
* Tough As Nails
* Tropicraft
* Untamed Wilds
* Vanilla Food Pantry
* Water Strainer
* XL Food Mod

## ITEMS

* Additional Banners
* Botany Pots
* Bountiful
* Carrots Lib
* CasinoCraft
* Crock Pot
* Culinary Construct
* Dimensional Dungeons
* Edible Bugs
* Engineer's Decor
* Fluffy's Farming
* Horticulture
* Husbandry
* MedievalCraft
* MineColonies
* NeverEnoughCandy
* Occultism
* Penguin Lib
* Piscary
* PokeCube
* PokeCube Adventures
* PokeCube Legends
* Seasonals
* Shopaholic
* Silent Gear
* Silent's Mechanisms
* Simply Tea
* SushiGo Crafting
* Terraqueous
* Terraqueous Heads
* Token Enchanter
* Tough As Nails
* Tropicraft
* Untamed Wilds
* Vanilla Food Pantry
* XL Food Mod

## ENTITIES

* Engineer's Decor
* MedievalCraft
* MineColonies
* Occultism
* Piscary
* PokeCube
* PokeCube Adventures
* Silent Gear
* SushiGo Crafting
* Terraqueous
* Tropicraft
* Untamed Wilds

## POTIONS

* Carrots Lib
* Crock Pot
* Fluffy's Farming
* Occultism
* Seasonals
* Simply Tea
* SushiGo Crafting
* Terraqueous
* Tough As Nails
* Vanilla Food Pantry

## ENCHANTMENTS

* Effect Enchantments
* Farmer's Delight
* FlashFyre's Enchants
* MineColonies
* Silent Gear

## BIOMES

* Dimensional Dungeons
* Fluffy's Farming
* PokeCube
* PokeCube Legends
* Tropicraft

# v1.6.0 -- 7/29/21

* Added validation schema for Mystic Alchemy potion ingredients.
* Added validation schema for Architect's Palette warping recipes.
* Added validation schemas for InControl's spawner.json and spawn.json.
* Updated @minecraft/tag validation schema.

# v1.5.0 -- 7/29/21

* Added test JSON schema validation for tag files.
* Universal registry added:

## BLOCKS

* Agricraft
* BlockLayering
* Comforts
* ComputerCraft Tweaked
* EvilCraft
* Exotic Critters
* Habitat (Bloom and Gloom)
* Immersive Petroleum
* Infernal Expansion
* Jellyfishing
* Lord of the Rings Renewed
* MrCrayfish's Furniture
* Odd Water Mobs
* PneumaticCraft
* Reliquary
* Serene Seasons
* SwitchBow
* Traverse
* Treemendous

## ITEMS

* Agricraft
* Antique Atlas
* Archer's Paradox
* BlockLayering
* Comforts
* ComputerCraft Tweaked
* EvilCraft
* Exotic Critters
* Goblin Traders
* Habitat (Bloom and Gloom)
* Hats
* Immersive Petroleum
* Infernal Expansion
* Jellyfishing
* Lord of the Rings Renewed
* MrCrayfish's Furniture
* Nature's Compass
* Odd Water Mobs
* PneumaticCraft
* Reliquary
* Serene Seasons
* Spartan Shields
* SwitchBow
* Traverse
* Treemendous
* Waddles
* Water Strainer

## ENTITIES

* Archer's Paradox
* ComputerCraft Tweaked
* EvilCraft
* Exotic Critters
* Goblin Traders
* Habitat (Bloom and Gloom)
* Hats
* Immersive Petroleum
* Infernal Expansion
* Jellyfishing
* Lord of the Rings Renewed
* MrCrayfish's Furniture
* Odd Water Mobs
* PneumaticCraft
* Reliquary
* SwitchBow
* Traverse
* Treemendous
* Waddles

## POTIONS

* Archer's Paradox
* EvilCraft
* Exotic Critters
* Habitat (Bloom and Gloom)
* Immersive Petroleum
* Infernal Expansion
* Odd Water Mobs
* Reliquary
* SwitchBow

## ENCHANTMENTS

* AgriCraft
* EvilCraft
* Jellyfishing
* Spartan Shields
* SwitchBow

## BIOMES

* Bayou Blues
* EvilCraft
* Exotic Critters
* Infernal Expansion
* Jellyfishing
* Lord of the Rings Renewed
* Odd Water Mobs
* Traverse
* Treemendous

# v1.4.3 -- 7/29/21

* Pluralizing arrays.

# v1.4.2 -- 7/29/21

* Fixed language scopes. Oops.

# v1.4.1 -- 7/29/21

* Added language scopes for snippets to prevent them from showing up in unnecessary contexts. Unfortunately, the "necessary context" for the universal registry is pretty broad, but the other helper snippets should be cleanly out of the way now.

# v1.4.0 -- 7/28/21

* Added @kubejs/shaped/ helper snippets for common recipe shapes: Chest, Compression. More like these planned.
* Added Mystic Alchemy utility snippet for potion ingredient recipe, @mysticalchemy/recipe/potion_ingredient. Added @kubejs/mysticalchemy/potion_ingredient to create a reusable helper function for simple recipes of this type. 
* Added Resourceful Bees utility snippets for custom bee, honey, and bee trait definition. Use @resourcefulbees/custom to get started.
* Added Resourceful Bees centrifuge recipe. Use @resourcefulbees/recipe/centrifuge.

# v1.3.0 -- 7/27/21

* Enchantment and biome registries added.
* Universal Registry added registry IDs for:

## BLOCKS

* Cold's Enchants 2.0
* Ma Enchants
* Mana and Artifice
* MrCrayfish's Guns
* MrCrayfish's Vehicles
* Mystic Alchemy
* ObserverLib
* Pyromancer

## ITEMS

* Mana and Artifice
* MrCrayfish's Guns
* MrCrayfish's Vehicles
* Mystic Alchemy
* Pyromancer
* Wonderful Enchantments

## ENTITIES

* Cold's Enchants 2.0
* Mana and Artifice
* MrCrayfish's Guns
* MrCrayfish's Vehicles
* Pyromancer

## POTIONS

* Cold's Enchants 2.0
* Mana and Artifice
* Marblegate's Exotic Enchantments: Flowing Agony
* MrCrayfish's Guns
* Pyromancer
* Unique Enchantments (Core)
* Wonderful Enchantments

## ENCHANTMENTS

* Apotheosis
* Astral Sorcery
* CoFH Core
* Cold's Enchants 2.0
* Cursed
* Cursery
* Cyclic
* Enchantable
* Ensorcellation
* Ma Enchants
* Mana and Artifice
* Marblegate's Exotic Enchantments: Flowing Agony
* Minecraft
* MrCrayfish's Guns
* Nature's Aura
* Pyromancer
* Unique Enchantments (Battle, Core, Util)
* Wonderful Enchantments

## BIOMES

* Abundance
* Biomes O' Plenty
* BYG
* Druidcraft
* Environmental
* Minecraft
* Twilight Forest
* Twist
* Undergarden
* Unnamed Animal Mod


# v1.2.1 -- 7/27/21

- Added utility snippets for Cave Generator, which has not yet updated to 1.16 but is in the process of doing so.
- Added (currently very limited) utility snippets for KubeJS.
- Added utility snippets for Masterful Machinery.
- Added utility snippets for Open Terrain Generator, which is nearing beta status for 1.16.

* Universal Registry added registry IDs for:

## BLOCKS

* Sophisticated Backpacks
* Waystones
* XNet

## ITEMS

* Rats
* Resourceful Bees
* Tetra
* Twist
* Undergarden
* Unnamed Animal Mod
* Various Oddities
* World-Building Plus
* Wyrmroost

## ENTITIES

* Resourceful Bees
* Sophisticated Backpacks
* Tetra

## POTIONS

* Rats
* Resourceful Bees
* Tetra