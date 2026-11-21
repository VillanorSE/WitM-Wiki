# Building

!!! abstract "Quick facts"
    - The build menu (G) is sorted into War in the Mediterranean tabs; blocks out of period are hidden.
    - No thrusters or reactors: planes and ships move on propellers, power comes from engines and batteries.
    - Every grid needs a [Ship Core](../combat/ship-cores.md) to work.
    - Player planes get **Flight Assist** by default. Large ships can use the **Ship Control** script.

## The build menu

The G menu is reorganised when the world loads. Tabs, in order:

Ship Cores · Weapons: Naval · Weapons: Ground · Weapons: Air & AA · Armor (4, 12, 25, 50, 75 and 100 mm) ·
Aircraft Parts · Ground Vehicle Parts · Naval Parts · Cockpits & Seats · Engines & Power · Optics & Electronics ·
Logistics · Lights & Doors · Decor & Structure · Production & Utility · Other

All other categories are hidden.

## Block restrictions

Blocks that don't belong in the period are disabled for players by the Block Restrictions mod. NPCs keep them. These
are **defaults**: a server owner can turn any of them back on in the world's Block Restrictions config.

## Flight Assist

Flight Assist flies your plane's gyros for you. Mouse movement sets a turn rate, the plane rolls into turns, and it
eases back to level when you let go. It works above 30 m/s.

| Setting (cockpit Custom Data, section `[Flight Assist]`) | Default |
|---|---|
| Enabled | true |
| Pitch rate at full mouse (deg per s) | 60 |
| Yaw rate at full mouse (deg per s) | 30 |
| Roll rate at full roll (deg per s) | 100 |
| Roll into turns (0-1, negative reverses) | 0.8 |
| Return to level (0-1) | 0.3 |
| Level dead zone (degrees of bank) | 3 |
| Level fades out by (degrees of bank; 180 always rolls upright) | 150 |
| Max nose angle from flight path (degrees; 180 off) | 25 |
| Assist above speed (m/s) | 30 |
| Mouse smoothing (seconds) | 0.08 |

Turn it off for yourself with `/assist off`. WitM planes steer by gyro; Draygo's movable control surfaces are
optional and not used by the scenario's planes.

## Ship Control

!!! note "Next update"
    A Programmable Block script for large ships: **W/S** step the throttle, **A/D** turn, and the ship holds itself
    level. The throttle setting shows on your HUD (needs the Text HUD API mod, already pulled in).

    Rudders from the Ship Rudders mod will only work where a rudder belongs: in the rear 15% of the hull, in the
    water, with open water behind or below. A rudder that fails switches off and says why in its terminal info.

## Respawn trucks

If the Water Mod moves your respawn truck to a safe landing spot, the mod puts its wheels back on. If wheels still
come off, report it.
