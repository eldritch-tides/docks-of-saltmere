# ⚓ Deep Sea Fishing — The Docks of Saltmere

> *A browser-based fishing RPG with quests, a port system, crafting, and a mermaid.*

![Deep Sea Fishing Banner](banner.png)

---

## Overview

Deep Sea Fishing is a fully self-contained single-file HTML/CSS/JS game inspired by the fishing skill in RuneScape 3. You start with a small net on the docks of Saltmere, catch fish to level up from 1–99, meet eccentric NPCs with branching dialogue, send ships on deep-sea voyages crewed by hired sailors, and craft items from the strange things you pull out of the water.

No server. No install. No dependencies. Just open the `.html` file in any browser.

---

## Features

### 🎣 Fishing (Levels 1–99)
- Full RS3-accurate XP table from crayfish to sailfish
- 9 fishing spots unlocked progressively by level — Shallows, Pier End, Coral Reef, Open Water, Deep Waters, DSF Platform, Blue Zone, Frenzy Spot, and Sailfish Run
- Fishing Frenzy mechanic with a streak bonus up to +20% XP that decays if you go idle
- 8% base loot drop chance per catch — pull up pearls, sea runes, pirate maps, and the occasional Drowned Crown
- Rod upgrades at the Sea Trader that reduce catch time, boost XP, or increase loot chance
- Full outfit system for XP bonuses

### 📜 Quests (15 total)
**Main arc — Saltmere story (10 quests):**
A fisherman's tale that starts with catching shrimp for an old captain and ends with binding an ancient sea god beneath the waves to save the town. Features Captain Aldric, Harbormaster Vex, Weatherwitch Nara, Captain Red the pirate, Widow Sela, and Ghost Sal.

**Little Mermaid arc — Hans Christian Andersen inspired (5 quests):**
Ariel surfaces at your reef and wants to trade. Ursula emerges from under the dock with a contract. A loophole in an ancient deal, a memory vessel, a drowned crown, and a choice at the water's edge. All five quests weave through the crafting and loot systems.

Each quest has branching dialogue with 2–4 choices, voiced NPC personalities, and objectives that connect directly to fishing, voyages, and crafting.

### ⚓ Port System
- **5 ship types:** Rowboat → Sloop → Brigantine → Galleon → Phantom Vessel (quest-locked)
- **6 routes:** Coastal Waters → Trade Winds → Deep Blue → Maelstrom Pass → The Abyss → Cursed Shallows (quest-locked)
- **8 hireable crew members**, each with real mechanical bonuses — survival rate, speed multipliers, gold bonuses, rare cargo chance
- Real-time voyage progress with ETA countdown
- Mid-voyage random events: storms, sea monsters, treasure finds
- Survival roll on return — ships can be lost at sea
- Ships bring back rare fish, gold, trade goods, and quest items you cannot catch yourself

### ⚒️ Crafting (Workbench)
11 recipes across 5 categories using loot drops as ingredients:

| Recipe | Ingredients | Effect |
|--------|-------------|--------|
| Pearl Necklace | 3× Pearl, 1× Driftwood | Sells for 320 gp |
| Sea Charm | 2× Sea Glass, 1× Rusted Ring | Sells for 180 gp |
| Driftwood Lure | 2× Driftwood, 1× Crab Claw | +3% loot for 5 min |
| Pirate Compass | Torn Map, Ring, Driftwood | Sells for 800 gp |
| Wyrm Ward | Wyrm Fragment, Sea Rune, Triton Shard | Sells for 3500 gp |
| Ursula's Brew *(quest)* | Triton Shard, Sea Rune, Seaweed | Required for Legs Potion |
| Memory Vessel *(quest)* | Message Bottle, Coin Pouch | Required for Ariel quest |
| Legs Potion *(quest)* | Ursula's Brew, Mermaid Scale, Sea Rune | Completes Little Mermaid arc |
| Mermaid Lure *(quest reward)* | Mermaid Scale, Driftwood, Pearl | +10% loot, +5% rare fish for 10 min |

Quest recipes unlock through the Little Mermaid quest line. Active crafting boosts show a live countdown timer.

### 📖 Collection Log
- Every fish and loot item tracked with first-catch date and total count
- Grayed-out silhouettes for undiscovered entries
- Stats panel: unique fish caught, loot found, rod bonuses, voyage count, lifetime gold

---

## How to Play

1. Download `deep_sea_fishing.html`
2. Open it in any modern browser
3. Fishing starts automatically at the Shallows
4. Click any glowing spot on the water or use the row of spot buttons to change location
5. Visit the **Quest** tab to talk to NPCs and start quest lines
6. Visit the **Port** tab to buy ships, hire crew, and send voyages
7. Visit the **Crafting** tab to combine loot drops into sellable items or quest items
8. Visit the **Collection** tab to track your progress

---

## Tabs

| Tab | Contents |
|-----|----------|
| 🎣 Fishing | Skill panel, fishing scene, inventory, Sea Trader, activity log |
| 📜 Quests | Quest list, NPC dialogue with choices, objectives tracker |
| ⚓ Port | Fleet management, voyage planner, crew hiring, active voyages, cargo returns |
| ⚒️ Crafting | Recipe list, ingredient checker, active boosts, crafted items log |
| 📖 Collection | Fish log, loot log, lifetime stats |

---

## Fish Reference

| Fish | Level | XP | Sell |
|------|-------|----|------|
| Crayfish / Shrimp | 1 | 10 | 2–3 gp |
| Sardine | 5 | 20 | 5 gp |
| Herring | 10 | 30 | 8 gp |
| Anchovies | 15 | 40 | 12 gp |
| Trout | 20 | 50 | 18 gp |
| Salmon | 30 | 70 | 28 gp |
| Tuna | 35 | 80 | 40 gp |
| Lobster | 40 | 90 | 55 gp |
| Swordfish | 50 | 100 | 80 gp |
| Minnow | 68 | 26 | 10 gp |
| Green Jellyfish | 68 | 75 | 120 gp |
| Shark | 76 | 110 | 150 gp |
| Manta Ray | 79 | 115 | 200 gp |
| Sea Turtle | 79 | 115 | 180 gp |
| Great White | 79 | 120 | 220 gp |
| Blue Jellyfish | 91 | 140 | 260 gp |
| Sailfish | 97 | 160 | 400 gp |
| Kraken Beak *(ship only)* | — | — | 1200 gp |
| Deep Anglerfish *(ship only)* | — | — | 800 gp |
| Ghost Eel *(ship only)* | — | — | 600 gp |

---

## Loot Rarity

| Rarity | Examples | Base Drop Rate |
|--------|----------|---------------|
| Common | Seaweed, Driftwood, Old Boot | High |
| Uncommon | Pearl, Sea Glass, Rusted Ring, Message Bottle | Medium |
| Rare | Coin Pouch, Torn Map, Triton Shard, Sea Rune | Low |
| Legendary | Drowned Crown, Wyrm Scale Fragment, Captain's Compass | Very rare |

Base loot chance is 8% per catch, increased by rod upgrades and crafted lures.

---

## Technical

- Single `.html` file — no build step, no server, no dependencies
- Vanilla HTML/CSS/JavaScript (ES5 compatible)
- Mobile responsive — stacks vertically on small screens, side-by-side panels on desktop (768px+)
- All game state in memory — refreshing the page resets progress
- ~138 KB total

---

## Credits

Inspired by the Deep Sea Fishing hub and fishing skill in **RuneScape 3** by Jagex. Quest narrative inspired by Hans Christian Andersen's *The Little Mermaid* (1837). Built entirely in one HTML file with no frameworks or libraries.

---

*The sea will remember you, fisherman.*
