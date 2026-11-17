# Fostercare's WoW Addons

A quick overview of 21 addons for **World of Warcraft 1.12.1, build 5875, Interface 11200**: 15 that are maintained and 6 that are ignored for now. Open a repository below for its source, requirements and installation instructions; each public one has a release zip ready to extract into `Interface/AddOns`. Private repositories are heavily customized for one setup and are not meant for general use.

## Addon overview

| Addon | Purpose | Repository |
| --- | --- | --- |
| **!ErrorLog** | Catches every Lua error in a copyable window and finds what makes the game stutter or freeze (`/err`, `/lag`, `/trace`). | [Open repository](https://github.com/Fostercare5988/ErrorLog) |
| **AutoBG** | Battleground queues, timers, flag carriers and enemy tracking. | [Open repository](https://github.com/Fostercare5988/AutoBG) |
| **AutoLazy** | Loot-message filtering, farm-item rolls, a minimap tray and quest turn-ins. | [Open repository](https://github.com/Fostercare5988/AutoLazy) |
| **Bagnon** | Unified bags and bank, sorting and cached character inventories. | [Open repository](https://github.com/Fostercare5988/Bagnon) |
| **BrainwasherPro** | Named talent specs at the Goblin Brainwashing Device, with an action bar profile per spec (based on Horyoshi's BrainwasherPro). | [Open repository](https://github.com/Fostercare5988/BrainwasherPro) |
| **EasyPoisons** | Plan a batch of rogue poisons and buy the missing reagents in one click (based on Horyoshi's EasyPoisons). | [Open repository](https://github.com/Fostercare5988/EasyPoisons) |
| **FostercareBars** | Modern action bars on the same slots and keys, up to 10 extra bars for spells, items, macros and equipment sets, and named profiles of every bar (replaces ActionBarProfiles). | [Open repository](https://github.com/Fostercare5988/FostercareBars) |
| **FostercareBattleText** | Scrolling combat text, healing, resource gains and alerts (formerly Mik's Scrolling Battle Text). | [Open repository](https://github.com/Fostercare5988/FostercareBattleText) |
| **FostercareFrames** | Blizzard's player, target and pet frames: class colours, exact numbers, cast bars, energy ticks, auras under the frames, the top-right buffs and weapon enchants, and watched auras. | [Open repository](https://github.com/Fostercare5988/FostercareFrames) |
| **FostercareNameplates** | Separate nameplate appearance and cast displays; enable deliberately in the addon list. | [Open repository](https://github.com/Fostercare5988/FostercareNameplates) |
| **FostercareRaid** | One grid for party and raid: click targeting, missing health, range, aggro and heal-over-time corners, buffs and debuffs. | [Open repository](https://github.com/Fostercare5988/FostercareRaid) |
| **FostercareTweaks** | Item tooltips (sell prices, compare, quality borders), Sell Junk, chat, the minimap, the world map and Auto Stance. Since 1.0.0 its unit frames are FostercareFrames and its grid FostercareRaid. | [Open repository](https://github.com/Fostercare5988/FostercareTweaks) |
| **GearRack** | Equipment sets, trinket priorities and weapon swapping. | [Open repository](https://github.com/Fostercare5988/GearRack) |
| **Mail** | Open all mail in one click, send many items at once, complete recipient names. | [Open repository](https://github.com/Fostercare5988/Mail) |
| **ThreatMeter** | Group threat bars, how much more threat pulls aggro, and a warning before you do. | [Open repository](https://github.com/Fostercare5988/ThreatMeter) |

## Ignored for now

Installed and in use, but not being worked on at the moment.

| Addon | Purpose | Repository |
| --- | --- | --- |
| **AtlasLoot** | Loot tables for dungeons, raids, world bosses and other sources. | [Open private repository](https://github.com/Fostercare5988/AtlasLoot) |
| **aux-addon** | Auction-house searches, buying, selling and price history. | [Open repository](https://github.com/Fostercare5988/aux-addon) |
| **BigWigs** | Boss encounter warnings and timer bars. | [Open private repository](https://github.com/Fostercare5988/BigWigs) |
| **ShaguDPS** | Damage and DPS meter. | Shagu's addon; no repository here |
| **SuperAPI** | Companion addon for the SuperWoW extension. | [Open private repository](https://github.com/Fostercare5988/SuperAPI) |
| **UnitXP_SP3_Addon** | Settings menu for the UnitXP SP3 extension. | [Open private repository](https://github.com/Fostercare5988/UnitXP_SP3_Addon) |

## Engineering and client support

[VanillaForge](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering) holds engineering guidance, API references and validation tools. The 15 maintained addons run on the latest releases of ClassicAPI, SuperWoW, NamPower and UnitXP SP3, plus DXVK for graphics. Each of them requires ClassicAPI; the addons that also need SuperWoW, NamPower or UnitXP SP3 say so in their own README. The exact versions they are built and tested against are pinned in one place, [UPSTREAM_VERSIONS.json](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering/blob/main/UPSTREAM_VERSIONS.json).

## About this repository

This repository is the navigation hub. Each addon keeps its own source, history and downloads in the linked repository. The overview contains no addon packages and performs no installation or synchronization.
