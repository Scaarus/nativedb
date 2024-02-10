---
ns: VEHICLE
aliases: ["0x6ebfb22d646ffc18"]
---
## SET_VEHICLE_STOP_INSTANTLY_WHEN_PLAYER_INACTIVE

```c
// 0x6EBFB22D646FFC18
void SET_VEHICLE_STOP_INSTANTLY_WHEN_PLAYER_INACTIVE(Vehicle vehicle, bool Val);
```

Allow/prevent the player vheicle loss all its velocity instantly when the player loses control

Sets whether a player controlled vehicle will stop instantly when the player's control is disabled (used in cutscenes etc). Default is to stop instantly

