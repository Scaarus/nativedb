---
ns: PLAYER
aliases: ["0xdccfd3f106c36ab4"]
---
## IS_PLAYER_FREE_FOR_AMBIENT_TASK

```c
// 0xDCCFD3F106C36AB4
bool IS_PLAYER_FREE_FOR_AMBIENT_TASK(Player player);
```

Returns TRUE if the player is currently not in combat, climbing, jumping or firing a gun.

Note it might work best if ambient tasks make sure the player has been free for an ambient task for a few seconds depending on the situation. (E.g. if the player hasn't done anything interesting for 5 seconds, allow cab hailing)

