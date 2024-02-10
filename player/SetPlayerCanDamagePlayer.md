---
ns: PLAYER
aliases: ["0x55fcc0c390620314"]
---
## SET_PLAYER_CAN_DAMAGE_PLAYER

```c
// 0x55FCC0C390620314
void SET_PLAYER_CAN_DAMAGE_PLAYER(Player player, Player player, bool AllowDamageFlag);
```

Sets if a player ped can be damaged by a specific player (network game only). NOTE: This must be set up locally on all machines, no information here is synced (same as SET_PED_CAN_BE_TARGETTED_BY_PLAYER). PARAMS PlayerIndex - Player index. TargetPlayerIndex - Target player index.

