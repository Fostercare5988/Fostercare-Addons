# Fostercare's WoW Addons

Addons for **World of Warcraft 1.12.1** (build 5875, Interface 11200). Every
maintained addon needs [ClassicAPI](https://github.com/brues-code/ClassicAPI);
a few also need SuperWoW or NamPower and say so in their README. Each public
repository has a release zip to extract into `Interface/AddOns`.

The addons are being rebuilt one by one: written new for ClassicAPI, waking
only when something changes, with their settings on a page in **Game Menu >
AddOn Options**. Six are done; nine still run their older code.

## Rebuilt for ClassicAPI

| Addon | What it does | Settings | Repository |
| --- | --- | --- | --- |
| **Auras** | Watched auras, a light WeakAuras: your chosen buffs and your target's debuffs, each its own icon with the time left; Only mine; a buff's cooldown after it ends. | `/auras` | [Auras](https://github.com/Fostercare5988/Auras) |
| **AutoLazy** | Auto-rolls farm items, accepts bind-on-pickup, hides roll spam, Shift turns in quests, and gathers the minimap buttons into one tray. | `/al` | [AutoLazy](https://github.com/Fostercare5988/AutoLazy) |
| **FostercareBars** | Modern action bars on the same slots and keys, up to 10 extra bars for spells, items, macros and equipment sets, and named profiles of every bar. Replaces ActionBarProfiles. | `/fbars` | [FostercareBars](https://github.com/Fostercare5988/FostercareBars) |
| **FostercareFrames** | Blizzard's player, target and pet frames: class colours, exact numbers, cast bars, energy ticks, auras under the frames, the top-right buffs and weapon enchants. | `/ffr` | [FostercareFrames](https://github.com/Fostercare5988/FostercareFrames) |
| **FostercareRaid** | One grid for party and raid: click targeting, missing health, range, aggro and heal-over-time corners, buffs and debuffs. | `/fraid` | [FostercareRaid](https://github.com/Fostercare5988/FostercareRaid) |
| **FostercareTweaks** | Item tooltips (sell prices, compare, quality borders), Sell Junk, chat, the minimap, the world map and Auto Stance. | `/ft` | [FostercareTweaks](https://github.com/Fostercare5988/FostercareTweaks) |
| **Mail** | Opens all mail in one click, sends many items at once and completes recipient names. | nothing to set | [Mail](https://github.com/Fostercare5988/Mail) |

## Waiting for their rebuild

They work and need ClassicAPI, but still run their older code.

| Addon | What it does | Repository |
| --- | --- | --- |
| **!ErrorLog** | Catches every Lua error in a copyable window and finds what makes the game stutter or freeze (`/err`, `/lag`, `/trace`). | [ErrorLog](https://github.com/Fostercare5988/ErrorLog) |
| **AutoBG** | Battleground queues, timers, flag carriers and enemy tracking. | [AutoBG](https://github.com/Fostercare5988/AutoBG) |
| **Bagnon** | Unified bags and bank, sorting and cached character inventories. | [Bagnon](https://github.com/Fostercare5988/Bagnon) |
| **BrainwasherPro** | Named talent specs at the Goblin Brainwashing Device, with a FostercareBars profile per spec (based on Horyoshi's BrainwasherPro). | [BrainwasherPro](https://github.com/Fostercare5988/BrainwasherPro) |
| **EasyPoisons** | Plan a batch of rogue poisons and buy the missing reagents in one click (based on Horyoshi's EasyPoisons). | [EasyPoisons](https://github.com/Fostercare5988/EasyPoisons) |
| **FostercareBattleText** | Scrolling combat text, healing, resource gains and alerts (formerly Mik's Scrolling Battle Text). | [FostercareBattleText](https://github.com/Fostercare5988/FostercareBattleText) |
| **FostercareNameplates** | Separate nameplate appearance and cast displays; enable it on purpose in the addon list. | [FostercareNameplates](https://github.com/Fostercare5988/FostercareNameplates) |
| **GearRack** | Equipment sets, trinket priorities and weapon swapping. | [GearRack](https://github.com/Fostercare5988/GearRack) |
| **ThreatMeter** | Group threat bars, how much more threat pulls aggro, and a warning before you do. | [ThreatMeter](https://github.com/Fostercare5988/ThreatMeter) |

## Ignored for now

Installed and in use, but not worked on.

| Addon | What it does | Repository |
| --- | --- | --- |
| **AtlasLoot** | Loot tables for dungeons, raids, world bosses and other sources. | [AtlasLoot](https://github.com/Fostercare5988/AtlasLoot) (private) |
| **aux-addon** | Auction-house searches, buying, selling and price history. | [aux-addon](https://github.com/Fostercare5988/aux-addon) |
| **BigWigs** | Boss encounter warnings and timer bars. | [BigWigs](https://github.com/Fostercare5988/BigWigs) (private) |
| **ShaguDPS** | Damage and DPS meter. | Shagu's addon; no repository here |
| **SuperAPI** | Companion addon for the SuperWoW extension. | [SuperAPI](https://github.com/Fostercare5988/SuperAPI) (private) |
| **UnitXP_SP3_Addon** | Settings menu for the UnitXP SP3 extension. | [UnitXP_SP3_Addon](https://github.com/Fostercare5988/UnitXP_SP3_Addon) (private) |

Private repositories are customized for one setup and are not meant for general use.

## Engineering

[VanillaForge](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering)
holds the engineering guidance, API references, tests and tools behind these
addons. They are built and tested against the latest releases of ClassicAPI,
SuperWoW, NamPower and UnitXP SP3, pinned in one place:
[UPSTREAM_VERSIONS.json](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering/blob/main/UPSTREAM_VERSIONS.json).

This repository is only the overview: each addon keeps its source, history and
downloads in its own repository.
