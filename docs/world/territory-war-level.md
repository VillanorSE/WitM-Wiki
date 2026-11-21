# Territory and War Level

!!! abstract "Quick facts"
    - Each side has **three anchor ports**. Each anchor has a territory circle that grows from **5 km to 35 km** in
      seven steps.
    - Territory grows when the *other* side loses grids, and when your side's cargo arrives. It shrinks when your side
      loses grids.
    - Airfields and depots belong to whichever side's territory covers them, and stay with the first owner while
      both sides cover them.
    - The **War Level** (1 to 5) rises as NPC grids get attacked anywhere, and never drops on its own.
    - NPCs only spawn dynamically inside their own side's territory (wrecks excepted).

## Anchors

| <span class="gray-side">Gray</span> anchors | <span class="green-side">Green</span> anchors |
|---|---|
| La Spezia (HQ) | Toulon (HQ) |
| Rome (Civitavecchia port) | Oran |
| Tripoli | Alexandria |

Anchors are permanent and can't be captured. Each one keeps its own points total, so the war can go well for Gray
around Tripoli and badly around La Spezia at the same time.

## Territory tiers

| Tier | Radius | Points needed (total) |
|---|---|---|
| 1 | 5 km | 0 |
| 2 | 10 km | 100 |
| 3 | 15 km | 325 |
| 4 | 20 km | 725 |
| 5 | 25 km | 1,350 |
| 6 | 30 km | 2,250 |
| 7 | 35 km | 3,475 |

Radius is measured along the planet's surface.

## Earning and losing territory points

When a grid is destroyed, its side loses the grid's value at **all three** of its anchors, and the other side gains
the same value at all three of its anchors. A grid that despawns cleanly or finishes a delivery is never counted as a
loss.

| Grid type | Value |
|---|---|
| Carrier | 100 |
| Battleship | 80 |
| Heavy cruiser | 50 |
| Cruiser | 40 |
| Destroyer | 20 |
| Submarine | 15 |
| Corvette, naval utility | 10 |
| Factory | 10 |
| Utility plane, bomber | 5 |
| Attacker | 4 |
| Fighter | 3 |
| Hangar | 2 |
| Medium or heavy tank | 2 |
| Light tank, gun emplacement | 1 |
| Armored car | 0 |

Deliveries add points one-sided, with no loss to the enemy:

- a **cargo ship** finishing its 5-minute unload: +100 at the destination anchor;
- a **cargo plane** finishing its delivery: +20 at its side's anchor nearest that airfield.

## Who owns an airfield or depot

1. An unowned site goes to a side when **only** that side's territory covers it.
2. An owned site keeps its owner while the owner's territory still covers it, even if the enemy's also does.
3. It flips when only the enemy covers it, and becomes unowned when neither does.

On a flip the site changes colours and owner, its stores restock for the new owner, and its supply starts **Low**.

## War Level

The War Level is one number for the whole world. It comes from a hidden counter, **War Activity**, which goes up when
an NPC grid is attacked for the first time (once per grid), or destroyed without ever being attacked. It uses the
same values as the territory table. Nothing lowers it.

| War Level | War Activity |
|---|---|
| 1 | 0 |
| 2 | 100 |
| 3 | 200 |
| 4 | 400 |
| 5 | 700 |

Each new level is announced once in chat.

### What each level brings

| From | At sea | In the air | On the ground and in stores |
|---|---|---|---|
| WL1 | Corvettes, cargo ships | Single MS.406 and Re.2000 fighters | AB41, Panhard 178; Fiat 626, Renault AHN |
| WL2 | Destroyers (Spica, Francesco Crispi, Bougainville) | D.520, Re.2001, Ba.65, Ro.43, Loire 130 | AB43, L6/40, R35; destroyers in port stores |
| WL3 | Comandante Margottini, Le Triomphant | Attackers and bombers: FC.20, SM.79, Potez 630, V-156-F | M13/40, Somua S35; bombers in airfield stores |
| WL4 | Cruisers: Trento, Émile Bertin, Algérie | Fighters come in flights of three; Ba.65 in pairs | P26/40, Char B1 |
| WL5 | Battleship Strasbourg, carriers Aquila and Béarn; destroyers in pairs, no more lone corvettes | | Strasbourg on sale at Green ports |

See [At Sea](../encounters/sea.md), [In the Air](../encounters/air.md) and [Rosters](../combat/rosters.md) for details.
