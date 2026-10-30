# Fostercare's WoW Addons

A quick overview of 20 addons for **World of Warcraft 1.12.1, build 5875, Interface 11200**. Open a repository below for its source, requirements and installation instructions. Private repositories are heavily customized for one setup and are not meant for general use.

## Addon overview

| Addon | Purpose | Repository |
| --- | --- | --- |
| **!ErrorLog** | Catches every Lua error in a copyable window and finds what makes the game stutter (`/err`, `/lag`). | [Open repository](https://github.com/Fostercare5988/ErrorLog) |
| **ActionBarProfiles** | Save and restore action-bar layouts. | [Open private repository](https://github.com/Fostercare5988/ActionBarProfiles) |
| **AtlasLoot** | Loot tables for dungeons, raids, world bosses and other sources. | [Open private repository](https://github.com/Fostercare5988/AtlasLoot) |
| **AutoBG** | Battleground queues, timers, flag carriers and enemy tracking. | [Open repository](https://github.com/Fostercare5988/AutoBG) |
| **AutoLazy** | Loot-message filtering, farm-item rolls, a minimap tray and quest turn-ins. | [Open repository](https://github.com/Fostercare5988/AutoLazy) |
| **aux-addon** | Auction-house searches, buying, selling and price history. | [Open repository](https://github.com/Fostercare5988/aux-addon) |
| **Bagnon** | Unified bags and bank, sorting and cached character inventories. | [Open repository](https://github.com/Fostercare5988/Bagnon) |
| **BetterCharacterStats** | Additional melee, ranged, spell and defensive character statistics. | [Open repository](https://github.com/Fostercare5988/BetterCharacterStats) |
| **BigWigs** | Boss encounter warnings and timer bars. | [Open private repository](https://github.com/Fostercare5988/BigWigs) |
| **BrainwasherPro** | Named talent specs at the Goblin Brainwashing Device, with an action bar profile per spec (based on Horyoshi's BrainwasherPro). | [Open repository](https://github.com/Fostercare5988/BrainwasherPro) |
| **EasyPoisons** | Plan a batch of rogue poisons and buy the missing reagents in one click (based on Horyoshi's EasyPoisons). | [Open repository](https://github.com/Fostercare5988/EasyPoisons) |
| **FostercareAuras** | Personal ability, aura, item and resource trackers. | [Open private repository](https://github.com/Fostercare5988/FostercareAuras) |
| **FostercareNameplates** | Separate nameplate appearance and cast displays; enable deliberately in the addon list. | [Open repository](https://github.com/Fostercare5988/FostercareNameplates) |
| **FostercareTweaks** | Action bars, party and raid frames, improvements to Blizzard's unit frames and interface tweaks. | [Open repository](https://github.com/Fostercare5988/FostercareTweaks) |
| **GearRack** | Equipment sets, trinket priorities and weapon swapping. | [Open repository](https://github.com/Fostercare5988/GearRack) |
| **MikScrollingBattleText** | Scrolling combat text, healing, resource gains and alerts. | [Open repository](https://github.com/Fostercare5988/MikScrollingBattleText) |
| **OctoMail** | Open all mail, recipient autocomplete, a mail log and marked-up auction mail. | [Open repository](https://github.com/Fostercare5988/OctoMail) |
| **SuperAPI** | Companion addon for SuperWoW: interface compatibility and a minimap menu for its settings. | [Open private repository](https://github.com/Fostercare5988/SuperAPI) |
| **TWThreat** | Threat bars, target indicators, alerts and a tank-mode view. | [Open repository](https://github.com/Fostercare5988/TWThreat) |
| **UnitXP_SP3_Addon** | Settings menu for the UnitXP SP3 extension. | [Open private repository](https://github.com/Fostercare5988/UnitXP_SP3_Addon) |

## Engineering and client support

[VanillaForge](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering) holds engineering guidance, API references and validation tools. All 20 addons run on the latest releases of ClassicAPI, SuperWoW, NamPower and UnitXP SP3, plus DXVK for graphics. Every addon requires ClassicAPI; the addons that also need SuperWoW, NamPower or UnitXP SP3 say so in their own README. The exact versions they are built and tested against are pinned in one place, [UPSTREAM_VERSIONS.json](https://github.com/Fostercare5988/VanillaForge-Addon-Engineering/blob/main/UPSTREAM_VERSIONS.json).

## About this repository

This repository is the navigation hub. Each addon keeps its own source, history and downloads in the linked repository. The overview contains no addon packages and performs no installation or synchronization.
