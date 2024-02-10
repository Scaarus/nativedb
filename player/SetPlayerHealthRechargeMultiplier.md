---
ns: PLAYER
aliases: ["0x5db660b38dd98a31"]
---
## SET_PLAYER_HEALTH_RECHARGE_MULTIPLIER

```c
// 0x5DB660B38DD98A31
void SET_PLAYER_HEALTH_RECHARGE_MULTIPLIER(Player player, float Mult);
```

Allows the script to modify how quickly the players health recharges

This function alters how quicky the players health can recharge


## Parameters
* **player**: 
* **Mult**: 1.0 uses the default rate, lower being slower, higher being quicker. e.g. 1.5 is 50% quicker, 0.0 doesn't recharge
