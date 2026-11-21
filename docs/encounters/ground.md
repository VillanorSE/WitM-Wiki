# On the Ground

!!! abstract "Quick facts"
    - Ground NPCs live around the **vehicle depots**: patrols drive the roads, defenders come out to meet you.
    - **Truck convoys** carry supply from ports to airfields and depots along the roads.
    - A disabled NPC vehicle stops for good but its turrets keep shooting.
    - Bots (AiEnabled) guard most installations on foot.

## Depot patrols and defenders

Each owned depot sends a patrol every 45 to 60 minutes along its road loop. Patrols and defenders use the
vehicles of their side at the current War Level (table on [Installations](installations.md#vehicle-depots)).

On contact they leave the road and fight, circling the target at roughly **150 to 250 m**. With no target left they
go back to their patrol or their depot. NPC ground units stay near their own depot: they don't drive across the map.

## Truck convoys

Columns of Fiat 626 (Gray) or Renault AHN (Green) trucks drive from a port to an airfield or depot of their side, and
only while that side holds the destination. Each truck carries supply loaded from the port. Your side's columns
appear on the **Supply Runs** LCD with a GPS on the lead truck.

If a truck is disabled the trucks behind it stop too. If the destination is lost, the trucks on the road turn back
and despawn, and their load returns to the port.

## Disabled vehicles

An NPC ground vehicle stops for good when:

- none of its engines works (destroyed, damaged below functional, switched off, or out of fuel), or
- it runs on wheels (AB41, AB43, Panhard 178, the trucks) and loses a wheel.

It stays where it is with its turrets still firing, so finish the guns before you walk up. A disabled truck despawns
once no player is within 1 km. Disabled vehicles are a good source of salvage, or you can
[capture](../combat/capturing.md) them.

## Bots

Installations carry crews of AiEnabled bots. The Manufactory, battleship and carriers carry the biggest crews (10).
