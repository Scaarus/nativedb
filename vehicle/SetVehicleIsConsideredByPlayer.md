---
ns: VEHICLE
aliases: ["0x31b927bbc44156cd"]
---
## SET_VEHICLE_IS_CONSIDERED_BY_PLAYER

```c
// 0x31B927BBC44156CD
void SET_VEHICLE_IS_CONSIDERED_BY_PLAYER(Vehicle vehicle, bool ConsideredByPlayerFlag);
```

Sets if the player can enter a vehicle pressing triangle.

ConsideredByPlayerFlag default = true

Passing FALSE to this command will make the player not consider this vehicle when pressing triangle to enter a vehicle. The player will instead pick the next closest vehicle to steal/enter.

