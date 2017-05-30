# OreShrubs - 1.3.0 Beta #
- Just updated to 1.11.2. May contain bugs! Urgh~

# OreShrubs -  1.2.1 #
- Removed trash loot tables from loot bags, they now should contain more good stuff!
- RandomShrubs can now be stacked in the world.
- FIXED! Advanced LootBags are now craftable.

# OreShrubs - 1.2.0 #
- ADDED advanced config settings for OreShrubs. (Density, GenHeight, VeinSize, ...)
- ADDED forgotten shrines to the world generation. A RandomShrub will be generated inside them.
- ADDED a RandomShrub and RandomBerries. Can be found rarely in forgotten shrines.
    --> They need a minimum light level of 13, otherwise they will shrink and turn in a burned OreShrub.
    --> Has to be placed on Obsidian to grow.
- ADDED LootBags in two variants. Can be crafted out of random berries and contain random chest loot.
- ADDED new shrub:
    --> DarkGem(EvilCraft) - Spawn in the Overworld.
    --> CertusQuartz(Applied Energistics) - Spawn in the Overworld.
- ADDED possibility to add custom shrubs via a config file. (See Minecraft Forum Thread for more information.)
- CHANGED OreBerries and OreShrubs as loot in chests. They know should be generate more consistent.
- UPDATE Translations.

# OreShrubs - 1.1.1 #
- Language Support for: Russian(ru_RU) [Thanks to 'Aurelius']
- All OreShrubs now registered like the recent added ones. That means: All Berries can directly craft to nuggets. (For now)
- All old berries are deprecated. You still have them in your inventory and should convert them in the new ones.
- Config option: 'craftOreBerriesToIngots' and 'disableOreBerryRecipesToo' are deleted. They are unnecessary now.
- ADDED a config option to disable a shrub.
- ADDED retroactively generation (Retrogen). Can be disabled in config.
- ADDED OreShrub and OreBerries as obtainable loot in chests.
- CHANGED the gotten experience points from Experience Berries from 10 to 8.
- CHANGED Uranium ingot recipe, if only yellorum is present.
- CHANGED that only a collision with uranium or lead shrub will give negative effects.
- FIX: Right click a tiny OreShrub with flint and steel will no more leave a fire in front of the shrub.
- FIX: Empty Ore Shrub, if a mod is not loaded but enabled in the config.
- FIX: Crash on start up, if a mod register a material, that not exist as item.

# OreShrubs - 1.1.0 Beta #
- Ore Shrubs have no more transparency if the graphics settings is set to 'Fast'. (Like leaves)
- Ore Shrubs can not floating anymore. They always need a solid face or a fully grown shrub below/above them.
- ADDED translation support. Please visit the Minecraft Forum Thread for that.
- Language Support for: Portuguese(pt_PT) [Thanks for the one who translated it!]
- The ShrubTrap has now a blast resistance like obsidian.
- ADDED new shrubs:
  - Quartz - Spawn in the Nether.
  - Draconium(Draconic Evolution) - Spawn in the End.
  - Cobalt, Ardite(Tinkers Construct) - Spawn in the Nether.
  - Black Quartz(Actually Additions) - Spawn in the Overworld.

Because of a new registration system for shrub types:
- The berries of the new added shrubs can directly crafted into nuggets. (Will be changed later.)
- Is the mod for a shrub type are not loaded, e.g. Draconic Evolution, the shrub block is disabled.
- Ore shrubs generate in slightly bigger veins but they are a little bit rarer.
- Ore shrubs can be placed on top and the bottom of a block. (Sometimes it looks strange, but its Minecraft!)
- Ore shrubs can only be placed on the blocks on which they were generated. (Draconium -> End Stone)
- Configs: 'craftOreBerriesToIngots' and 'disableOreBerryRecipesToo' will not work for the new added shrubs. These two configs are unnecessary for those.

# OreShrubs - 1.0.0 #
- Release