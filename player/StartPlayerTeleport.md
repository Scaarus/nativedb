---
ns: PLAYER
aliases: ["0xad15f075a4da0fde"]
---
## START_PLAYER_TELEPORT

```c
// 0xAD15F075A4DA0FDE
void START_PLAYER_TELEPORT(Player player, Vector3 Position, float heading, bool teleportVehicle, bool snapToGround, bool fadePlayerOut);
```

Starts a player teleport to the given coordinates. More...

This function handles map and population loading. [`UPDATE_PLAYER_TELEPORT`](#_0xE23D5873C2394C61) should be queried for completion.


## Parameters
* **player**: 
* **Position**: 
* **heading**: 
* **teleportVehicle**: (Default value: `True`)
* **snapToGround**: (Default value: `True`)
* **fadePlayerOut**: (Default value: `True`)
