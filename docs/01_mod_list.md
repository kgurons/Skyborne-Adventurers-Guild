# 01 - Mod List and Compatibility Policy

## Baseline Environment

- Minecraft: 1.21.1
- NeoForge: 21.1.234
- Java: 21

## Confirmed Core Mods

- Create
- Create Aeronautics
- Project MMO
- Project MMO Classes
- Iron's Spellbooks
- Apotheosis
- Simply Swords
- Better Combat
- Mekanism
- FTB Quests
- LootJS
- KubeJS
- Lootr
- Easy NPC (if compatible)
- Yggdrasils
- Cataclysm
- Blue Skies
- Mowzie's Mobs
- Bosses of Mass Destruction
- Deeper and Darker
- Explorify
- Structory
- ChoiceTheorem's Overhauled Village
- Tectonic
- Sky Villages
- Incendium
- Explorer's Compass
- Nature's Compass
- Jade
- JourneyMap
- Carry On
- Controlling
- Better Advancements
- Inventory HUD+
- Equipment Compare
- Better Ping Display
- Archers (RPG Series)
- Paladins and Priests (RPG Series)
- Rogues and Warriors (RPG Series)
- Armory (RPG Series)

## Approved Decoration Mods

- Supplementaries
- Amendments
- Decorative Blocks
- Chipped
- Handcrafted
- Another Furniture
- Beautify

## Explicitly Excluded Mods

- Epic Fight
- Artifacts
- BetterEnd
- Ocean's Delight
- Twilight Forest
- The Graveyard
- L_Ender's Cataclysm Additions
- Inventory Profiles Next
- Better Recipe Book

## Dependency Policy

- Include all required libraries and API dependencies for confirmed mods.
- Prefer stable releases over bleeding-edge beta builds.
- Lock versions after first integration pass to reduce breakage.
- Add only mods that support server stability and do not conflict with core loop.

## Admission Checklist for Additional Mods

1. Supports at least one project pillar.
2. Works on NeoForge 21.1.234 and Minecraft 1.21.1.
3. No known severe server memory or tick issues.
4. Does not invalidate Guild Coin economy.
5. Does not bypass Guild Rank progression.
6. Compatible with current worldgen stack.
