---
ns: PLAYER
aliases: ["0xb6997a7eb3f5c8c0"]
---
## GET_PLAYERS_LAST_VEHICLE

```c
// 0xB6997A7EB3F5C8C0
Vehicle GET_PLAYERS_LAST_VEHICLE();
```

Returns the last vehicle that the player has been in.

if the player is currently in a vehicle that vehicle will be returned. If the player has not been in a vehicle yet or it somehow got destroyedremoved the value returned will be NULL.

