# Salvage and Special Components

!!! abstract "Quick facts"
    - Three **special components** gate progression: **Industrial**, **Military**, and **Advanced Military**.
    - They can't be bought or looted directly. You assemble them from **Salvage Alloy** plus ordinary ingots.
    - Salvage Alloy is refined from **Battle Wreckage**, which you loot from wrecks and destroyed NPC grids.
    - **Salvaged Ordnance** is looted from bigger kills and is needed for the heaviest naval ammunition.

## The chain

```
Battle Wreckage (ore)  ──refinery──▶  Salvage Alloy (ingot)  ──assembler + ingots──▶  special components
```

| Step | Input | Output | Time |
|---|---|---|---|
| Refine | 1 Battle Wreckage | 5 Salvage Alloy, 2 Iron, 1 Nickel | 3 s |
| Assemble | 5 Salvage Alloy, 40 Iron, 10 Nickel, 5 Cobalt, 5 Magnesium | 1 **Industrial Component** | 9 s |
| Assemble | 10 Salvage Alloy, 8 Cobalt, 3 Silver, 6 Magnesium, 2 Uranium | 1 **Military Component** | 20 s |
| Assemble | 20 Salvage Alloy, 4 Platinum, 15 Silver, 30 Silicon, 8 Gold, 15 Magnesium | 1 **Advanced Military Component** | 60 s |

Battle Wreckage refines in any refinery, including the basic one. The components are made in an ordinary assembler.
Times are base times before refinery and assembler speed.

## Where to find salvage

| Source | Battle Wreckage | Salvaged Ordnance |
|---|---|---|
| Wrecked Golos, corvettes, and destroyers on the coasts | Yes | Bigger wrecks |
| Destroyed NPC grids (cargo holds) | Yes | Medium-sized grids and up |
| Port Goods stores | No | Bought and sold, base 1,500 |

Loot is rolled in size tiers (small, medium, large, huge): bigger grids have bigger and richer holds. Salvaged
Ordnance never appears in the smallest tier.

## What needs which component

| Component | Used for |
|---|---|
| Industrial | Speed and yield modules (4 each), Services Terminal (8), water propellers (8 each), air propellers (1 each), the largest wheels (2 each), the Outpost core (4) |
| Military | Attacker (2), Light Tank (2), Medium Tank (4) and Destroyer (40) cores; stronger basic weapons (20 mm guns, 1 each); lighter guns in the Weapons class |
| Advanced Military | Bomber (4), Heavy Tank (4), Cruiser (20), Heavy Cruiser (30), Battleship (40) and Carrier (50) cores; the strongest guns |

In the game's item lists these appear with vanilla's Prototech icons, renamed: Industrial Components are Prototech
Machinery, Military Components are Prototech Frames, Advanced Military Components are Prototech Circuitry.
