---
ns: NETWORK
aliases: ["0xea23c49eaa83acfb"]
---
## NETWORK_RESURRECT_LOCAL_PLAYER

```c
// 0xEA23C49EAA83ACFB
void NETWORK_RESURRECT_LOCAL_PLAYER(Vector3 Pos, float Heading, int invicibilityTime, bool leaveDeadPed, bool unpauseRenderPhase, int spawnLocation, int spawnReason);
```

Revives our local player who was previously dead. CALL THIS ONCE WHEN YOU WANT TO RESURRECT THE PLAYER (THIS DOES NOT NEED TO BE CALLED EVERY FRAME)


## Parameters
* **Pos**: 
* **Heading**: 
* **invicibilityTime**: this is the length of time in millisecs that the player will be invincible for after resurrection
* **leaveDeadPed**: 
* **unpauseRenderPhase**: 
* **spawnLocation**: enum PLAYER_SPAWN_LOCATION for telemetry
* **spawnReason**: 
