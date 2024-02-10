---
ns: PLAYER
aliases: ["0xefd79fa81dfba9cb"]
---
## SET_PLAYER_FALL_DISTANCE_TO_TRIGGER_RAGDOLL_OVERRIDE

```c
// 0xEFD79FA81DFBA9CB
void SET_PLAYER_FALL_DISTANCE_TO_TRIGGER_RAGDOLL_OVERRIDE(Player player, float Distance);
```

```
Allows the script to modify the minimum fall height that causes the ped to trigger ragdoll.

Distance (m): Must be greater or equal to 0.0. The default fall distance trigger is between 6m and 8.5m (depending on strength stat).

This function alters the minimum fall height that causes the ped to trigger ragdoll.
```
