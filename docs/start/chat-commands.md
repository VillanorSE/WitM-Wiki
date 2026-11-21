# Chat Commands

!!! abstract "Quick facts"
    - Players use two commands: `/alliance` (pick a side) and `/assist` (plane Flight Assist).
    - Every `/witm` command is for admins only.

## Player commands

| Command | Who | What it does |
|---|---|---|
| `/alliance GRAY` | Faction leader | Ally your faction with Gray; Green becomes your enemy. From the AllianceRepHelper mod. |
| `/alliance GREEN` | Faction leader | Ally your faction with Green; Gray becomes your enemy. |
| `/assist` | Any pilot | Toggle Flight Assist for yourself. |
| `/assist on` / `/assist off` | Any pilot | Turn Flight Assist on or off for yourself. |
| `/assist status` | Any pilot | Show whether it is on, with a short pitch report for your current plane. |
| `/assist log` | Any pilot | Write a flight log (above 100 m/s) to the game log, for reporting problems. |

`/flightassist` works the same as `/assist`. Flight Assist is explained on [Building](../economy/building.md#flight-assist).

## Admin commands

| Command | What it does |
|---|---|
| `/assist server on` / `off` | Turn Flight Assist on or off for everyone. |
| `/witm refresh` | Dry run: what a refresh of the permanent installations would do. Changes nothing. |
| `/witm refresh go [all\|ports\|airfields\|depots\|<site>]` | Replace the live port, airfield or depot grids with fresh spawns, one site at a time. Sites with player grids or players nearby are skipped. |
| `/witm refresh status` / `cancel` | Progress of a running refresh, or stop it. |
| `/witm supply` | Table of every port, airfield and depot: stock, band, owner and convoy routes. |
| `/witm supply set <site> <n>` | Set a site's Home stock. |
| `/witm supply onward <site> <n>` | Set a port's Onward stock. |
| `/witm supply hour` | Run one hourly supply tick now. |

The mods underneath (MES, Ship Core, WeaponCore, Water Mod) have their own commands; see their Workshop pages.
