# World Settings

!!! abstract "Quick facts"
    - World speed cap **150 m/s** through Relative Top Speed; each Ship Core sets its own share of it.
    - Ship Core Framework is on; NPC grids are exempt from its limits.
    - Vanilla encounters, cargo ships and planetary installations are switched off.
    - Respawn: Fiat 626 or Renault AHN truck, 15-minute cooldown each.

## Relative Top Speed

Set in the world's `RelativeTopSpeed.cfg`:

| Setting | Value |
|---|---|
| SpeedLimit | 150 |
| RemoteControlSpeedLimit | 150 |
| LargeGrid MaxBoostSpeed | 120 |
| SmallGrid MaxBoostSpeed | 150 |

World drag is raised so planes slow down without thrust.

## Ship Core Framework

- Ship Core is on for players and NPC grids are exempt.
- The SCF speed boost is off on every WitM core.
- The world must have the **No Core** profile selected (admin: `/core select No Core`), or planes without a core
  can't be flown.

## Reputation

- Gray and Green are non-static factions with no starting reputation.
- Vanilla reputation for damaging, grinding, stealing and killing is zero; the scenario's own rules apply
  ([Factions and Sides](../world/factions.md#reputation)).

## AllianceRepHelper

The world's AllianceRepHelper config lists `Factions = GRAY, GREEN` and `AllowOnlyNpcFactions = false`.

## Safe zones

Player safe zones need no Zone Chips to build or run, have a fixed 200 m radius and draw almost no power. Sieges
still cost Zone Chips.
