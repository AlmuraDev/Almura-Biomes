# Almura-Biomes

The following are the files used to configure the unique biomes on Almura.

"GlobalBiomes" are using for all worlds except Cemaria
"Cemaria" are for Cemaria Only.

If you wish to contribue to this repo; please feel free to clone and PR a change.

SpawnLists.xlsx has the Entity names and modid specs for each.

SpawnLists can be modified by changing the following entries:


It's not possible to change mob spawns in vanilla biomes. These
are the values used by vanilla for this biome. They are read-only:
changes to this setting are ignored and overwritten.

The monsters (skeletons, zombies, etc.) that spawn in this biome
SpawnMonsters: [{"mob": "mocreatures.caveogre", "weight": 5, "min": 1, "max": 4}, {"mob": "mocreatures.biggolem", "weight": 3, "min": 1, "max": 4}, {"mob": "mocreatures.werewolf", "weight": 6, "min": 1, "max": 4}, {"mob": "mocreatures.rat", "weight": 7, "min": 1, "max": 4}, {"mob": "Spider", "weight": 25, "min": 2, "max": 4}, {"mob": "Zombie", "weight": 25, "min": 2, "max": 4}, {"mob": "Skeleton", "weight": 25, "min": 2, "max": 4}, {"mob": "Creeper", "weight": 25, "min": 2, "max": 4}, {"mob": "Slime", "weight": 10, "min": 4, "max": 4}, {"mob": "Enderman", "weight": 10, "min": 1, "max": 4}, {"mob": "Witch", "weight": 5, "min": 1, "max": 1}]

The friendly creatures (cows, pigs, etc.) that spawn in this biome
SpawnCreatures: [{"mob": "mocreatures.bird", "weight": 15, "min": 1, "max": 4}, {"mob": "mocreatures.bunny", "weight": 8, "min": 1, "max": 4}, {"mob": "mocreatures.fox", "weight": 8, "min": 1, "max": 4}, {"mob": "mocreatures.mole", "weight": 7, "min": 1, "max": 4}, {"mob": "mocreatures.mouse", "weight": 7, "min": 1, "max": 4}, {"mob": "mocreatures.raccoon", "weight": 8, "min": 1, "max": 4}, {"mob": "Sheep", "weight": 12, "min": 1, "max": 4}, {"mob": "mocreatures.kitty", "weight": 25, "min": 1, "max": 4}, {"mob": "Pig", "weight": 10, "min": 1, "max": 4}, {"mob": "Chicken", "weight": 10, "min": 2, "max": 4}, {"mob": "Cow", "weight": 8, "min": 2, "max": 4}, {"mob": "Mule", "weight": 5, "min": 1, "max": 4}, {"mob": "Donkey", "weight": 5, "min": 1, "max": 4}, {"mob": "Llama", "weight": 5, "min": 1, "max": 4}, {"mob": "Rabbit", "weight": 5, "min": 1, "max": 4}]

The water creatures (only squids in vanilla) that spawn in this biome
SpawnWaterCreatures: [{"mob": "mocreatures.bass", "weight": 25, "min": 3, "max": 8}, {"mob": "mocreatures.goldfish", "weight": 12, "min": 1, "max": 4}, {"mob": "mocreatures.fishy", "weight": 12, "min": 1, "max": 4}, {"mob": "Squid", "weight": 10, "min": 4, "max": 4}]

The ambient creatures (only bats in vanila) that spawn in this biome
SpawnAmbientCreatures: [{"mob": "mocreatures.bee", "weight": 8, "min": 1, "max": 2}, {"mob": "mocreatures.butterfly", "weight": 8, "min": 1, "max": 2}, {"mob": "mocreatures.dragonfly", "weight": 8, "min": 1, "max": 2}, {"mob": "mocreatures.fly", "weight": 8, "min": 1, "max": 2}, {"mob": "Bat", "weight": 10, "min": 1, "max": 2}]
