# [NMRiH] Movable Ammo
Allows players to lift ammo when it doesn't fit in their inventories

[AlliedModders thread](https://forums.alliedmods.net/showthread.php?t=340795)


https://user-images.githubusercontent.com/11559683/206853984-b2cfad32-fe23-4625-9017-c5b65610fe35.mp4



## Installation
- Install [Sourcemod](https://www.sourcemod.net/downloads.php?branch=stable)
- Extract the zip file in [releases](https://github.com/dysphie/nmrih-movable-ammo/releases) to your server's `addons/sourcemod` directory
- Refresh your plugins list (`sm plugins refresh`)

## ConVars

ConVars are saved to `cfg/sourcemod/movable-ammo.cfg`

- `sv_movable_ammo` (1/0) (Default: 1) - Toggles movable ammo

- `sv_movable_ammo_pickup_delay` (Default: 1.0) - Seconds that must pass after a player becomes full before we attempt to lift ammo (avoids accidental pickups when spamming `+use`)

## Compiling

If you wish to compile the code yourself, you need [VScript Proxy](https://github.com/dysphie/nmrih-vscript-proxy)
