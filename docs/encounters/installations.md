# Installations

!!! abstract "Quick facts"
    - **Permanent:** 7 ports (6 faction anchors plus neutral Valencia), 7 airfields, 6 vehicle depots. They can't be
      destroyed.
    - **Temporary:** factories, garages, hangars, the Manufactory and ammo depots spawn inside their side's territory
      and eventually despawn.
    - Most installations are crewed by armed bots and call in defenders when a hostile player gets close.
    - Attacking a factory or ammo depot brings a reprisal raid. Garages and hangars don't.

## Permanent installations

### Ports

| Port | Side | Stores |
|---|---|---|
| La Spezia, Civitavecchia, Tripoli | <span class="gray-side">Gray</span> | Goods, vehicles |
| Toulon, Oran, Alexandria | <span class="green-side">Green</span> | Goods, vehicles |
| Valencia | Traders (neutral) | Goods, vehicles from both sides |

Ports send cargo ships to the other ports of their side, start truck convoys to their side's airfields and depots,
and scramble defenders against hostile players. Each has a **Goods** store and a **Vehicles** store
(see [Stores and Prices](../economy/stores.md)). Valencia has no defenders and takes no side.

### Airfields

Gibraltar, Casablanca, Bizerte, Tripoli, Foggia, Benghazi and Tobruk. Ownership follows territory
([rules](../world/territory-war-level.md#who-owns-an-airfield-or-depot)). An owned airfield:

- sells its side's planes, more types as the War Level rises;
- has a supply store;
- launches offensive planes that roam its side's territory, unless its supply is Low;
- sends and receives cargo planes;
- scrambles defenders when a hostile player gets close.

An unowned airfield sells nothing.

### Vehicle depots

Benghazi, Tunis, Tobruk, Abruzzo, Mascara and Sirte. Ownership works exactly like airfields. An owned depot:

- sells ground vehicles and has a supply store;
- sends patrols along its roads every 45 to 60 minutes (Normal or Full supply only);
- sends defenders when a hostile player is within **2 km**;
- has gun emplacements and a garage bay.

| War Level | Depot defense |
|---|---|
| 1 | 1 armored car |
| 2 | 1 armored car or light tank |
| 3 | 1 light or medium tank |
| 4 | 2 medium tanks |
| 5 | 1 heavy tank and 1 to 3 medium tanks |

Patrols come in the same sizes.

## Temporary installations

These spawn only inside their own side's territory.

| Installation | What it holds | Notes |
|---|---|---|
| Hangar | One or two planes you can steal | Light bot guard. Gray hangars also sell the Ju 52, Green ones the F.222. |
| Garage | One or two ground vehicles you can steal | Light bot guard. Vehicles match the War Level. |
| Plane factory | Several planes of one type, a store selling that plane, a supply store | Bots and defenders. Calls cargo planes, which complete the projected blocks on arrival. |
| Ground factory | Vehicles of one type, a store selling it, a supply store | Heavy factories hold two tanks. Unlocks by War Level (below). |
| Manufactory | Component loot in its cargo boxes; production blocks you can grind for components | 10 bots, a defense spawn, a component store. From WL1. |
| Ammo depot | Ammunition | Defensive guns. Attacking it brings a reprisal raid. |

| Ground factory | <span class="gray-side">Gray</span> | <span class="green-side">Green</span> |
|---|---|---|
| WL1 | AB41 | Panhard 178 |
| WL2 | AB43, L6/40 | R35 |
| WL3 | M13/40 | Somua S35 |
| WL4 | P26/40 | Char B1 |

Plane factories: Gray Re.2000, Re.2001, FC.20, SM.79 bomber; Green MS.406, D.520, Potez 630, V-156-F bomber.

## Wrecks

Wrecked Golos, corvettes (Gabbiano, La Malouine) and destroyers (Francesco Crispi, Comandante Margottini, Spica,
Bougainville, Le Triomphant) lie half-buried along the coasts. They have no crew. Their cargo holds hold Battle
Wreckage and, on the bigger ones, Salvaged Ordnance. See [Salvage](../economy/salvage.md).
