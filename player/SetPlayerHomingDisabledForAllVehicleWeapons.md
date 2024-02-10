---
ns: PLAYER
aliases: ["0xee4ebdd2593ba844"]
---
## SET_PLAYER_HOMING_DISABLED_FOR_ALL_VEHICLE_WEAPONS

```c
// 0xEE4EBDD2593BA844
void SET_PLAYER_HOMING_DISABLED_FOR_ALL_VEHICLE_WEAPONS(Player player, bool DisableHoming);
```

Sets a player targeting bool that disables homing for all vehicle weapons on the vehicle this player is in. NOTE: Weapons that were always homing will show the '(Homing Off)' prefix. Weapons that could toggle between homing and non-homing will only show the '(Homing Off)' version.

