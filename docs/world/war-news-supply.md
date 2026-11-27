# War News and Supply

!!! abstract "Quick facts"
    - Three LCD scripts come with the mod: **War News**, **War Score**, and **Supply Runs**. Set any LCD to one of them.
    - Every port, airfield, and depot holds **supply**. Supply pays for that site's defenders and raids.
    - A site's supply band (**Low**, **Normal**, **Full**) changes its store prices and stock, and whether it can
      launch attacks.
    - Supply arrives by cargo ship, truck convoy, and cargo plane. Sinking or ambushing them starves the enemy.

## LCD scripts

| Script | Shows |
|---|---|
| War News | The news feed: captures, raids, supply shortages, War Level changes, plus both sides' scores |
| War Score | Just the two sides' scores, as large as the screen allows |
| Supply Runs | Your side's active truck columns and cargo ships: route, trucks, km to go, and a GPS of the lead vehicle so you can escort it. The enemy's runs appear only as reports, such as "cargo ships at sea originating from Tripoli". |

War News can also give you GPS markers, some with a countdown, for events such as incoming raids.

The Supply Runs LCD uses its owner's side: your faction if it is Gray or Green, otherwise whichever side your
personal or faction standing is friendly with (above 500). With neither, it asks you to pick a side.

## Supply at each site

| Site | Starts at | Capacity | Low below | Full above | Upkeep per hour |
|---|---|---|---|---|---|
| Port (Home stock) | 120 | 200 | 60 | 180 | 4 |
| Airfield | 60 | 100 | 30 | 80 | 2 |
| Site just captured | 20 | | | | |

Ports also keep an **Onward** stock (up to 400) that ships and trucks load from. Supply moves like this:

1. The two headquarters, **La Spezia** and **Toulon**, produce 20 supply an hour.
2. Cargo ships carry it from the headquarters to the other ports of their side.
3. Truck convoys drive it from each port to its side's airfields and depots, but only while the port's side holds
   the destination.
4. Cargo planes move spare supply from Full airfields to others.

A delivery to a port is split between its Home and Onward stock. A full site wastes what doesn't fit. Trucks and
ships removed intact (for example when a route closes) give their load back.

## What supply does

| Band | Store prices | Store stock | Attacks |
|---|---|---|---|
| Low | Sells at +30% | Half | Defense spawns refused at depots; no offensive spawns |
| Normal | Normal | Normal | Normal |
| Full | Sells at −15%, buys at −10% | One and a half times | Normal |

Spawning defenders and raids costs supply. At depots: 2 per armored car and 3 per tank for defense; 2 per armored
car and 4 per tank for patrols (refunded if the patrol comes home intact). Airfields pay 3 for a defense spawn, 4
for a single offensive plane, 5 for a bomber, and 3 per plane in a group.

A site dropping into Low makes the news, and so does it recovering.
