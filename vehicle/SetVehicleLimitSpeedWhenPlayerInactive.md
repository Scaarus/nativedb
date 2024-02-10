---
ns: VEHICLE
aliases: ["0xc50ce861b55eab8b"]
---
## SET_VEHICLE_LIMIT_SPEED_WHEN_PLAYER_INACTIVE

```c
// 0xC50CE861B55EAB8B
void SET_VEHICLE_LIMIT_SPEED_WHEN_PLAYER_INACTIVE(Vehicle vehicle, bool Val);
```

Disable the limiting of player vehicle speed when the player loses control

Sets whether a player controlled vehicle will limit it's speed when the player's control is disabled (used in cutscenes etc). Default is to limit

