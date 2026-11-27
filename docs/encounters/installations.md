# Installations

!!! abstract "Quick facts"
    - **Permanent:** 7 ports (6 faction anchors plus neutral Valencia), 7 airfields, 6 vehicle depots. They can't be
      destroyed.
    - **Temporary:** factories, garages, hangars, the Manufactory, and ammo depots spawn inside their side's territory
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

Gibraltar, Casablanca, Bizerte, Tripoli, Foggia, Benghazi, and Tobruk. Ownership follows territory
([rules](../world/territory-war-level.md#who-owns-an-airfield-or-depot)). An owned airfield:

- sells its side's planes, more types as the War Level rises;
- has a supply store;
- launches offensive planes that roam its side's territory, unless its supply is Low;
- sends and receives cargo planes;
- scrambles defenders when a hostile player gets close.

An unowned airfield sells nothing.

### Vehicle depots

Benghazi, Tunis, Tobruk, Abruzzo, Mascara, and Sirte. Ownership works exactly like airfields. An owned depot:

- sells ground vehicles and has a supply store;
- sends patrols along its roads roughly hourly (Normal or Full supply only);
- sends defenders when a hostile player approaches;
- has a garage bay that spawns a ground vehicle corresponding to war level.
- patrol vehicles and defenders escalate with war level.

## Temporary installations

These spawn only inside their own side's territory.

| Installation | Notes |
|---|---|
| Hangar | A plane you can steal, lightly guarded by soldiers. |
| Garage | One or two ground vehicles you can steal, lightly guarded by soldiers. |
| Plane factory | Several planes of one type, a store selling that plane, and a supply store. Defended by soldiers and planes. Calls cargo planes, which complete the projected blocks on arrival. |
| Ground factory | Vehicles of one type, a store selling it, and a supply store. Defended by soldiers and planes. |
| Manufactory | Component loot in its cargo boxes; production blocks you can grind for components; and a component store. Defended by soldiers. |
| Ammo depot | Ammunition in containers and defended with guns and soldiers. Attacking it brings a reprisal raid. |

Ground and plane factories contain multiple vehicles of the same type and their contents scale with war level.

## Wrecks

Wrecked cargo ships, corvettes, and destroyers lie half-buried along the coasts. They have no crew. Their cargo holds hold Battle
Wreckage and, on the bigger ones, Salvaged Ordnance. See [Salvage](../economy/salvage.md).
