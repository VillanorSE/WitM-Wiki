# Factions and Sides

!!! abstract "Quick facts"
    - Two warring sides: <span class="gray-side">Gray</span> (Axis, Italian for now) and <span class="green-side">Green</span>
      (Allies, French for now).
    - Two neutral NPC factions: **Traders** (Valencia trade post) and the holder of unclaimed installations.
    - A faction leader picks a side with `/alliance GRAY` or `/alliance GREEN`.
    - Damage costs reputation with the victim and earns half as much with its enemy.

## The sides

| Side | Today | Description in game |
|---|---|---|
| <span class="gray-side">Gray</span> | Italy: Regia Marina, Regia Aeronautica, Regio Esercito | An alliance intent on expanding its territory, even by force. |
| <span class="green-side">Green</span> | France: Marine nationale, Armée de l'air, Armée de terre | An alliance intent on containing Gray, ready to fight any who fight it. |
| Traders | Neutral trade post at Valencia | Not aligned with either side, open to all. |
| Unowned | Airfields and depots no side holds yet | Passive, no reputation stake, no automatic hostility. |

Germany (under Gray) and Britain (under Green) are the planned first additions. Every vehicle is researched against
what that nation actually fielded in the period.

## Picking a side

New player factions start hostile to both sides. Your faction leader types `/alliance GRAY` or `/alliance GREEN`
(AllianceRepHelper mod). That sets your faction friendly to the chosen side and hostile to the other.

Allied standing lets you:

- buy and sell at that side's ports, airfields, depots and factories;
- pass its installations without its turrets firing on you;
- see that side's supply runs in full on the Supply Runs LCD.

Gray and Green have no starting reputation of their own, so a saved standing is never reset at load.

## Reputation

Reputation changes when you hurt NPC grids. Both changes apply to everyone in your faction who is part of the attack.

| Event | Victim side | Its enemy |
|---|---|---|
| First damage to a grid (then at most once every 15 minutes per grid) | −10 | +5 |
| Shooting down a plane, or sinking a cargo ship | −100 | +50 |
| Sinking a warship (corvette and up) | −250 | +125 |

The 15-minute window means a machine gun earns no more than a single shell: what counts is *that* you attacked, not
how fast you fire. Vanilla's own damage, grinding and stealing reputation are switched off; only the table above
applies.

!!! warning "Strikes on your base"
    From War Level 2, players at **−1000** or worse with a side can have their bases inside that side's territory
    raided from the air. Attacking a side's factory or ammo depot brings a reprisal flight at any War Level. See
    [In the Air](../encounters/air.md#strikes-and-reprisals).
