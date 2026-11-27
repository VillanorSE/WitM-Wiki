# Ship Cores and Block Limits

!!! abstract "Quick facts"
    - Every grid you build needs a **Ship Core**. The core sets its block count, PCU, dry mass, top speed and how
      many of each functional block it may carry.
    - Utility cores, the Base, the Miner, Armored Car, Fighter and Corvette cores cost only basic components.
      Everything stronger needs [special components](../economy/salvage.md).
    - Over the mass cap the grid is slowed and penalised; blocks over a limit don't work.
    - Some cores are capped per player and per faction (a carrier: 1 per player, 3 per faction).

The cores come from the Ship Core Framework mod; War in the Mediterranean supplies its own set. Place the core block
on your grid and it shows, on its HUD and terminal, how close you are to each limit.

## Cores at a glance

Top speed is the cap for that class of grid. Max dry mass counts the build components of every block, not cargo,
ammo or fuel, so it works as an **armour budget**: you choose between thick plate and more guns.

| Core | Max blocks | Max PCU | Max dry mass | Top speed | Per player / faction | Special components to build |
|---|---|---|---|---|---|---|
| Ground Utility | 1,500 | 6,000 | 80.0 t | 45 m/s | – / – | Basic only |
| Armored Car | 400 | 2,500 | 21.0 t | 45 m/s | – / – | Basic only |
| Light Tank | 400 | 3,000 | 24.5 t | 35 m/s | – / – | 2 Military |
| Medium Tank | 500 | 3,500 | 45.3 t | 30 m/s | 10 / 20 | 4 Military |
| Heavy Tank | 650 | 4,500 | 80.5 t | 25 m/s | 5 / 10 | 4 Advanced Military |
| Plane Utility | 3,000 | 12,000 | 100.0 t | 90 m/s | – / – | Basic only |
| Fighter | 300 | 2,500 | 7.5 t | 147 m/s | 10 / 40 | Basic only |
| Attacker | 450 | 4,000 | 12.8 t | 121 m/s | 6 / 20 | 2 Military |
| Bomber | 1,000 | 7,000 | 19.9 t | 118 m/s | 4 / 12 | 4 Advanced Military |
| Naval Utility | 4,000 | 15,000 | 1,000.0 t | 18 m/s | – / – | Basic only |
| Corvette | 650 | 4,000 | 218.0 t | 22 m/s | 3 / 15 | Basic only |
| Destroyer | 1,500 | 8,000 | 890.0 t | 45 m/s | 3 / 15 | 40 Military |
| Cruiser | 4,500 | 21,000 | 1,530.0 t | 44 m/s | 3 / 10 | 20 Advanced Military |
| Heavy Cruiser | 5,000 | 21,000 | 2,500.0 t | 44 m/s | 2 / 6 | 30 Advanced Military |
| Battleship | 8,500 | 25,000 | 2,720.0 t | 39 m/s | 2 / 5 | 40 Advanced Military |
| Carrier | 9,250 | 29,000 | 4,070.0 t | 34 m/s | 1 / 3 | 50 Advanced Military |
| Base | 6,000 | 20,000 | – | static | – / 2 | Basic only |
| Outpost | 1,200 | 6,000 | – | static | – / 8 | 4 Industrial |

## Weapon limits

Guns are counted by calibre class. The classes stack: a Medium limit counts medium *and bigger* guns, and every gun
also counts toward **Weapons**.

| Class | Naval guns | Ground guns |
|---|---|---|
| Weapons (light) | Below 150 mm | Below 54 mm |
| Medium | 150 to 155 mm | 54 to 77 mm |
| Heavy | 203 mm | 84 mm and up |
| Capital | 254 mm and up | |

**Basic weapons** are the lightest guns, such as machine guns, and have their own count. **Special** covers the
remaining weapon blocks; the core's terminal lists which blocks fall in each group.

| Core | Basic weapons | Weapons | Medium | Heavy | Capital | Special |
|---|---|---|---|---|---|---|
| Ground Utility | 1 | 0 | – | – | – | 0 |
| Armored Car | 2 | 1 | 1 | 0 | – | 0 |
| Light Tank | 3 | 1 | 0 | 0 | – | 0 |
| Medium Tank | 4 | 2 | 2 | 0 | – | 0 |
| Heavy Tank | 5 | 3 | 2 | 1 | – | 1 |
| Plane Utility | 3 | 0 | – | – | – | 0 |
| Fighter | 5 | 1 | – | – | – | 0 |
| Attacker | 8 | 2 | – | – | – | 4 |
| Bomber | 6 | 1 | – | – | – | 4 |
| Naval Utility | 6 | 2 | 0 | 0 | 0 | 0 |
| Corvette | 9 | 3 | 0 | 0 | 0 | 0 |
| Destroyer | 16 | 6 | 0 | 0 | 0 | 6 |
| Cruiser | 20 | 12 | 12 | 0 | 0 | 5 |
| Heavy Cruiser | 24 | 20 | 6 | 4 | 0 | 5 |
| Battleship | 29 | 23 | 23 | 4 | 4 | 7 |
| Carrier | 44 | 20 | 0 | 0 | 0 | 5 |
| Base | 24 | 8 | 8 | 2 | 0 | 0 |
| Outpost | 8 | 4 | 2 | 1 | 0 | 0 |

## Propulsion and other blocks

| Core | Propellers | Engines | Wheels | Gyros | Batteries | Seats | Cargo | Safe zones | Siege drives |
|---|---|---|---|---|---|---|---|---|---|
| Ground Utility | – | 3 | 10 | 2 | 6 | 12 | 18 | 0 | 0 |
| Armored Car | – | 2 | 6 | 1 | 2 | 3 | 5 | 0 | 0 |
| Light Tank | – | 1 | 14 | 1 | 3 | 3 | 5 | 0 | 0 |
| Medium Tank | – | 2 | 20 | 2 | 4 | 4 | 8 | 0 | 0 |
| Heavy Tank | – | 2 | 24 | 2 | 4 | 5 | 8 | 0 | 0 |
| Plane Utility | 4 | 6 | – | 1 | 8 | 10 | 21 | 0 | 0 |
| Fighter | 2 | 2 | – | 1 | 3 | 2 | 6 | 0 | 0 |
| Attacker | 3 | 4 | – | 1 | 4 | 4 | 8 | 0 | 0 |
| Bomber | 4 | 6 | – | 1 | 6 | 5 | 10 | 0 | 0 |
| Naval Utility | 7 | 16 | – | 3 | 8 | – | 15 | 0 | 0 |
| Corvette | 5 | 2 | – | 2 | 2 | – | 4 | 0 | 0 |
| Destroyer | 6 | 4 | – | 3 | 4 | – | 10 | 0 | 0 |
| Cruiser | 10 | 24 | – | 4 | 7 | – | 36 | 0 | 0 |
| Heavy Cruiser | 10 | 24 | – | 5 | 8 | – | 40 | 0 | 1 |
| Battleship | 10 | 20 | – | 6 | 7 | – | 45 | 0 | 1 |
| Carrier | 10 | 16 | – | 6 | 10 | – | 48 | 0 | 1 |
| Base | – | 3 | – | – | 8 | – | 24 | 1 | 0 |
| Outpost | – | 1 | – | – | 2 | – | 8 | 0 | 1 |

Naval cores may carry no navigation computers.

– means the core sets no limit for that block. 0 means it may carry none.

## Siege drives and safe zones

The Heavy Cruiser, Battleship, Carrier and Outpost cores may carry one **siege drive**. Only the Base core may carry a
**safe zone** (fixed 200 m radius, no Zone Chips to build or run; a siege still costs chips).

## Speeds in this world

The world speed cap is 150 m/s (Relative Top Speed mod). Each core sets its own share of that. Ground cores are set
by role, lighter being faster; naval cores follow the historical speed of their class. NPC planes fly a little slower
than yours. Planes lose speed quickly without thrust, because world drag is high.
