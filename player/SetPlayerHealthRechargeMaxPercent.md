---
ns: PLAYER
aliases: ["0xc388a0f065f5bc34"]
---
## SET_PLAYER_HEALTH_RECHARGE_MAX_PERCENT

```c
// 0xC388A0F065F5BC34
void SET_PLAYER_HEALTH_RECHARGE_MAX_PERCENT(Player player, float Percent);
```

```
Allows the script to modify the max percentage that a player's health can recharge to

This function alters the maximum percentage that a player's health can recharge to
```

## Parameters
* **player**: 
* **Percent**: Must be greater than 0.0, and equal or less than 1.0. Default percentage set in code is 0.5 (50%)
