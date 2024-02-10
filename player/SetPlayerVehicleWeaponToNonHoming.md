---
ns: PLAYER
aliases: ["0x237440e46d918649"]
---
## SET_PLAYER_VEHICLE_WEAPON_TO_NON_HOMING

```c
// 0x237440E46D918649
void SET_PLAYER_VEHICLE_WEAPON_TO_NON_HOMING(Player player);
```

Switches a weapon that can be toggled between homing and non-homing ('HomingToggle' weapon flag) to the non-homing state NOTE: Will do nothing if the weapon does not have the homing toggle ability, or the weapon is already in the non-homing state

