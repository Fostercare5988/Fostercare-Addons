# Fostercare's WoW Addons

Addons for **World of Warcraft 1.12.1** (build 5875, Interface 11200). Every
maintained addon needs [ClassicAPI](https://github.com/brues-code/ClassicAPI);
a few also need SuperWoW or NamPower and say so in their README. Each public
repository has a release zip to extract into `Interface/AddOns`.

The addons are being rebuilt one by one: written new for ClassicAPI, waking
only when something changes, with their settings on a page in **Game Menu >
AddOn Options**. Seven are done; nine still run their older code.

## Rebuilt for ClassicAPI

| Addon | What it does | Settings |
| --- | --- | --- |
| [**ActionBars**](https://github.com/Fostercare5988/ActionBars) | Modern action bars on the same slots and keys, up to 10 extra bars for spells, items, macros and equipment sets, and named profiles of every bar. Replaces ActionBarProfiles. | `/fbars` |
| [**Auras**](https://github.com/Fostercare5988/Auras) | Watched auras, a light WeakAuras: your chosen buffs and your target's debuffs, each its own icon with the time left; Only mine; a buff's cooldown after it ends. | `/auras` |
| [**AutoLazy**](https://github.com/Fostercare5988/AutoLazy) | Auto-rolls farm items, accepts bind-on-pickup, hides roll spam, Shift turns in quests, and gathers the minimap buttons into one tray. | `/al` |
| [**Mail**](https://github.com/Fostercare5988/Mail) | Opens all mail in one click, sends many items at once and completes recipient names. | nothing to set |
| [**RaidFrames**](https://github.com/Fostercare5988/RaidFrames) | One grid for party and raid: click targeting, missing health, range, aggro and heal-over-time corners, buffs and debuffs. | `/fraid` |
| [**Tweaks**](https://github.com/Fostercare5988/Tweaks) | Item tooltips (sell prices, compare, quality borders), Sell Junk, chat, the minimap, the world map and Auto Stance. | `/ft` |
| [**UnitFrames**](https://github.com/Fostercare5988/UnitFrames) | Blizzard's player, target and pet frames: class colours, exact numbers, cast bars, energy ticks, auras under the frames, the top-right buffs and weapon enchants. | `/ffr` |

## Waiting for their rebuild

They work and need ClassicAPI, but still run their older code.

| Addon | What it does |
| --- | --- |
| [**!ErrorLog**](https://github.com/Fostercare5988/ErrorLog) | Catches every Lua error in a copyable window and finds what makes the game stutter or freeze (`/err`, `/lag`, `/trace`). |
| [**AutoBG**](https://github.com/Fostercare5988/AutoBG) | Battleground queues, timers, flag carriers and enemy tracking. |
| [**Bagnon**](https://github.com/Fostercare5988/Bagnon) | Unified bags and bank, sorting and cached character inventories. |
| [**BrainwasherPro**](https://github.com/Fostercare5988/BrainwasherPro) | Named talent specs at the Goblin Brainwashing Device, with an ActionBars profile per spec (based on Horyoshi's BrainwasherPro). |
| [**EasyPoisons**](https://github.com/Fostercare5988/EasyPoisons) | Plan a batch of rogue poisons and buy the missing reagents in one click (based on Horyoshi's EasyPoisons). |
| [**FostercareBattleText**](https://github.com/Fostercare5988/FostercareBattleText) | Scrolling combat text, healing, resource gains and alerts (formerly Mik's Scrolling Battle Text). |
| [**FostercareNameplates**](https://github.com/Fostercare5988/FostercareNameplates) | Separate nameplate appearance and cast displays; enable it on purpose in the addon list. |
| [**GearRack**](https://github.com/Fostercare5988/GearRack) | Equipment sets, trinket priorities and weapon swapping. |
| [**ThreatMeter**](https://github.com/Fostercare5988/ThreatMeter) | Group threat bars, how much more threat pulls aggro, and a warning before you do. |

## Ignored for now

Installed and in use, but not worked on.

| Addon | What it does |
| --- | --- |
| [**AtlasLoot**](https://github.com/Fostercare5988/AtlasLoot) (private) | Loot tables for dungeons, raids, world bosses and other sources. |
| [**aux-addon**](https://github.com/Fostercare5988/aux-addon) | Auction-house searches, buying, selling and price history. |
| [**BigWigs**](https://github.com/Fostercare5988/BigWigs) (private) | Boss encounter warnings and timer bars. |
| **ShaguDPS** | Damage and DPS meter (Shagu's addon; no repository here). |
| [**SuperAPI**](https://github.com/Fostercare5988/SuperAPI) (private) | Companion addon for the SuperWoW extension. |
| [**UnitXP_SP3_Addon**](https://github.com/Fostercare5988/UnitXP_SP3_Addon) (private) | Settings menu for the UnitXP SP3 extension. |

Private repositories are customized for one setup and are not meant for general use.

## Engineering

[VanillaForge](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering)
holds the engineering guidance, API references, tests and tools behind these
addons. They are built and tested against the latest releases of ClassicAPI,
SuperWoW, NamPower and UnitXP SP3, pinned in one place:
[UPSTREAM_VERSIONS.json](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering/blob/main/UPSTREAM_VERSIONS.json).

This repository is only the overview: each addon keeps its source, history and
downloads in its own repository.
