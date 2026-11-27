# Chat Commands

!!! abstract "Quick facts"
    - WitM's own commands start with `/`: `/alliance` (pick a side) and `/assist` (plane Flight Assist).
    - Server commands start with `!`: fix a stuck ship, claim your vote reward, list your grids, and more.

## WitM commands

| Command | Who | What it does |
|---|---|---|
| `/alliance GRAY` | Faction leader | Ally your faction with Gray; Green becomes your enemy. From the AllianceRepHelper mod. |
| `/alliance GREEN` | Faction leader | Ally your faction with Green; Gray becomes your enemy. |
| `/assist` | Any pilot | Toggle Flight Assist for yourself. |
| `/assist on` / `/assist off` | Any pilot | Turn Flight Assist on or off for yourself. |
| `/assist status` | Any pilot | Show whether it is on, with a short pitch report for your current plane. |
| `/assist log` | Any pilot | Write a flight log (above 100 m/s) to the game log, for reporting problems. |

`/flightassist` works the same as `/assist`. Flight Assist is explained on [Building](../economy/building.md#flight-assist).

## Server commands

The server runs three plugins with commands for players. Type them in chat.

| Command | What it does |
|---|---|
| `!fixship` | Fix the stuck ship you are looking at: the server stops it and puts it back in place. Works on grids you own most of. |
| `!fixship <name>` | The same, for a ship you name. |
| `!reward` | Claim your reward after voting for the server. |
| `!grids list` | List the grids you own at least half of. |
| `!motd` | Show the server's message of the day. |
| `!w <player>` | Send a private message to another player. |
| `!entities refresh` | Reload the grids and objects around you, if something looks out of sync. |
| `!vote <name>` | Start a vote the server has set up. `!yes` and `!no` cast your vote; `!vote cancel` stops it. |

`!fixship` fails while a connector or landing gear is locked, or while anyone is sitting in a seat or cryo pod on the
ship. Unlock and get everyone out first. It has a cooldown between uses.

The mods underneath (MES, Ship Core, WeaponCore, Water Mod) have their own commands; see their Workshop pages.
