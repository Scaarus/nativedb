---
ns: PLAYER
aliases: ["0x6e4361ff3e8cd7ca"]
---
## IS_PLAYER_VEHICLE_WEAPON_TOGGLED_TO_NON_HOMING

```c
// 0x6E4361FF3E8CD7CA
bool IS_PLAYER_VEHICLE_WEAPON_TOGGLED_TO_NON_HOMING(Player player);
```

```
Checks to see if a player's currently selected vehicle weapon has been toggled to 'Non-Homing' through the weapon selector NOTE: Will return false if the player does not have a vehicle weapon selected, or the weapon does not have the ability to be homing toggled.
```
